# Tadas Martišius

I’m based in Kaunas, Lithuania, and graduated from a vocational program in Java programming. My focus is Linux systems administration and database reliability. I put both into practice in an Oracle Cloud homelab that I designed, deployed and maintain.

## Oracle Cloud homelab

I run a static website and a whitelist-only Minecraft server on one Ubuntu ARM virtual machine. Separate Docker Compose projects let me update the website while players stay connected. I administer both services over Tailscale.

The workloads share a boot disk, so a scheduled job on my Windows PC pulls a snapshot over SSH and stores it in an encrypted restic repository. During a restore test, I verified 353 file hashes and ran SQLite’s `PRAGMA quick_check` on all seven restored 1Panel databases. [Architecture](https://github.com/noonforme/oracle-cloud-homelab/blob/main/docs/architecture.md) · [Restore results](https://github.com/noonforme/oracle-cloud-homelab/blob/main/docs/operations.md#verification-and-restore)

## Software projects

- **LifeOS** is a local-first Linux desktop app for tracking work schedules, shifts and pay agreements. It uses Flutter, Dart and SQLite, with tests for database migrations and backup restoration. [Project and build instructions](https://github.com/noonforme/lifeManager)
- **Java coursework** includes two shop models. One tracks inventory and a shopping cart. The other models customers, orders and product discounts. [Java source](https://github.com/noonforme/kitm/tree/main/java)

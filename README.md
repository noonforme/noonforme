# Tadas Martišius

I’m building an online store for acrylic charms, magnets, and prints on metal. I host the site on an Ubuntu server that also runs a private Minecraft world. Each has its own Docker Compose project, so I can update the shop while people are playing.

## Oracle Cloud homelab

I administer the server over Tailscale and keep nightly encrypted backups on a separate PC. [Homelab architecture](https://github.com/noonforme/oracle-cloud-homelab/blob/main/docs/architecture.md) · [Backup and recovery](https://github.com/noonforme/oracle-cloud-homelab/blob/main/docs/operations.md#verification-and-restore)

## Software projects

I’m based in Kaunas, Lithuania, and graduated from a vocational program in Java programming. I also build desktop software for Linux.

### LifeOS

[![LifeOS Linux build and tests](https://github.com/noonforme/lifeManager/actions/workflows/linux.yml/badge.svg?branch=main)](https://github.com/noonforme/lifeManager/actions/workflows/linux.yml?query=branch%3Amain)

LifeOS is a Linux desktop app for tracking shifts, schedules and pay agreements. It uses Flutter and Dart for the interface and stores data locally in SQLite. A Python script runs the migration and backup-restore tests before the Linux app is packaged. [Project and build instructions](https://github.com/noonforme/lifeManager) · [Python build and test script](https://github.com/noonforme/lifeManager/blob/main/tool/ci/run.py)

### Java coursework

My Java coursework includes two shop models. One tracks inventory and a shopping cart. The other models customers, orders and product discounts. [Java source](https://github.com/noonforme/kitm/tree/main/java)

---
slug: /
sidebar_position: 1
title: Home
sidebar_label: Home
tags: [overview]
---

# Homelab Documentation

**Purpose:** Gaining hands-on experience with various tools and tech, documenting where appropriate.  
**Owner:** Ben Bream  
**Status:** Active  
**Tech stack summary:** pfSense, Proxmox, Terraform, much more to come  
**Last updated:** 2026-02-13

This was deployed to GitHub Pages using Docusaurus. 

Welcome to my homelab documentation site. Use the sidebar to navigate architecture, inventory, runbooks, infrastructure code, monitoring, and how-to guides.

## Quick links
- [Architecture](./architecture/diagram)
- [Inventory](./inventory)
- [Runbooks](./runbooks/backup-restore)
- [Infrastructure (IaC)](./infra)
- [Monitoring](./monitoring)
- [How to add a VM](./howto/add-vm)

## Contributing
- Branch from main, create a feature branch named `docs/<topic>`.
- Open a PR with a short description and link to any related infra changes.
- Use Markdown lint; CI will run checks on push.

## Local preview
```bash
npm install
npm run start
```

## Deploy to GitHub Pages
```bash
npm run build
GIT_USER=<your-username> USE_SSH=true npm run deploy
```

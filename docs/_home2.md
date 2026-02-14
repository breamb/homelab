## index.md frontmatter + content (Docusaurus)

---
title: Test
sidebar_label: Home
tags: [overview]
slug: /
sidebar_position: 1
---

# Homelab Documentation

**Purpose:** Learning, testing, and running home services.  
**Owner:** Your Name (optional)  
**Status:** Active  
**Tech stack summary:** Proxmox, Docker, Kubernetes, Terraform, Ansible, Prometheus, Grafana, Vault, nginx  
**Last updated:** 2026-02-13

Welcome to the homelab documentation site. Use the sidebar to navigate architecture, inventory, runbooks, infrastructure code, monitoring, and how-to guides.

## Quick links
- [Architecture](./architecture)
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

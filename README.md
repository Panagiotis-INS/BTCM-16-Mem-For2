# BTCMP-16 — Digital Forensics Lab Environment - Xubuntu
applied to BTCMP-16- Memory Forensics Evidence Gathering
## Overview

This lab environment is built around **Digital Forensics** scenarios.

---

## Topology

| Host | Role | Network | CIDR | IP |
|------|------|---------|------|----|
| uvm | Analyst Workstation (Xubuntu Noble) | access-switch | 10.10.10.0/24 | 10.10.10.5 |
| router | Network Router (Debian 12) | access-switch | 10.10.10.0/24 | 10.10.10.1 |

---

## Machines

### UVM — Analyst Workstation (Xubuntu Noble)
User `LocalAdmin` / `Password123!` (admin).

**Provisioning:**
- `unzip`, `curl`, `ca-certificates` installed via apt.
- Memory dump archive fetched from Dropbox, extracted, and the `.mem` file placed on `LocalAdmin`'s Desktop (`/home/LocalAdmin/Desktop/`).

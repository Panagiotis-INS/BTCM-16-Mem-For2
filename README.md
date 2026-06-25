# BTCMP-16 — Digital Forensics Lab Environment - Kali
applied to BTCMP-16- Memory Forensics Evidence Gathering
## Overview

This lab environment is built around **Digital Forensics** scenarios.

---

## Topology

| Host | Role | Network | CIDR | IP |
|------|------|---------|------|----|
| uvm | Analyst Workstation (Kali 2026.1) | access-switch | 10.10.10.0/24 | 10.10.10.5 |
| router | Network Router (Debian 12) | access-switch | 10.10.10.0/24 | 10.10.10.1 |

---

## Machines

### UVM — Analyst Workstation (Kali 2026.1)
User `LocalAdmin` / `Password123!` (admin).

**Provisioning:**
- `unzip`, `curl`, `ca-certificates` installed via apt.
- Memory dump archive fetched from Dropbox, extracted, and the `.mem` file placed on `LocalAdmin`'s Desktop (`/home/LocalAdmin/Desktop/`).

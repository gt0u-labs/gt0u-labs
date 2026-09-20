# Andrea Ronconi — GT0u Labs

### Technical Support & Infrastructure · Linux · Proxmox · Docker · Monitoring

![Linux](https://img.shields.io/badge/Linux-Ubuntu_|_Arch_|_Kali-2bbc8a?style=for-the-badge&logo=linux&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Loki_&_Promtail-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Location](https://img.shields.io/badge/Bucharest-Open_to_Ticino_&_Italy-white?style=for-the-badge&logo=googlemaps&logoColor=red)

---

## About

Self-taught technical profile focused on Linux systems, virtualization, containers
and network troubleshooting.

I run a two-node homelab, break it on purpose, and document how I diagnosed and
fixed it. The point isn't running services — it's reading logs, detecting
failures, restoring service and writing down what actually happened.

Italian citizen, based in Bucharest. Open to roles in Ticino (Switzerland) and Italy.

**Currently working toward:** junior technical support, NOC and infrastructure
operations, with an active move into defensive security (SOC / log analysis).

**Languages:** Italian (native) · Spanish (native) · Romanian (fluent) ·
English (B2) · German (A1, self-study)

---

## 🏠 The lab

**Node 1 — Application & monitoring server**
Ubuntu Server (headless, SSH-managed) · Docker & Docker Compose ·
Grafana + Loki + Promtail centralized logging · Uptime Kuma

**Node 2 — Virtualization host**
Proxmox VE bare-metal hypervisor · Ubuntu Server VM · Kali Linux VM for network
reconnaissance · GPU passthrough to a dedicated VM for local LLM inference
(Ollama + Open WebUI)

Both nodes managed remotely over SSH and the Proxmox web interface.

→ [gt0u-labs/homelab-notes](https://github.com/gt0u-labs/homelab-notes)

---

## 🔧 Selected work

### Centralized log monitoring — Grafana, Loki, Promtail
Self-hosted log stack on a Linux server, shipping logs from multiple Docker
services into searchable dashboards.
`centralized logging` · `log-volume dashboards` · `multi-service log shipping`

### Incident response lab — Docker Compose, Nginx, Uptime Kuma
Simulated a service outage, detected the failure through monitoring alerts,
restored the service and produced a written incident report with timeline and
root-cause notes.
`monitoring` · `outage detection` · `service recovery` · `incident reporting`

### GPU passthrough troubleshooting (VFIO)
Diagnosed a PCI ROM signature error through `dmesg`, resolved it with a
card-specific VBIOS via `romfile=`, reassigned USB devices and corrected the VM
boot order. Includes the mistake that cost me a full rebuild, and why it was one.
`VFIO` · `PCI passthrough` · `dmesg diagnosis` · `structured troubleshooting`

→ [Read the write-up](https://github.com/gt0u-labs/security-learning-log/blob/main/writeups/proxmox-gpu-passthrough.md)

### Responsible disclosure — Valve
Reviewed CVEs and dependency vulnerabilities; submitted a responsible disclosure
report to Valve regarding an outdated FFmpeg dependency in the Steam Link Linux
client (triaged).

---

## 🔐 Security training

Ongoing hands-on defensive security work across HTB Academy, HTB Labs and
TryHackMe — 64 modules and labs completed, organized by role with notes on what
each one covered.

**Blue team focus:** alert triage · log analysis · phishing and email header
analysis (SPF/DKIM/DMARC) · traffic analysis · defensive security fundamentals

→ [gt0u-labs/security-learning-log](https://github.com/gt0u-labs/security-learning-log)

---

## Technical stack

| Area | Technologies |
| --- | --- |
| Systems | Linux (Ubuntu, Arch, Kali), Windows, macOS, WSL |
| Virtualization | Proxmox VE, VM provisioning, LVM, PCI/GPU passthrough |
| Containers | Docker, Docker Compose |
| Networking | SSH, DNS, NAT & port forwarding, reverse proxies, Tailscale, Nginx |
| Monitoring | Grafana, Loki, Promtail, Uptime Kuma |
| Security | Nmap, Burp Suite, CVE & dependency review |
| Scripting | Bash, Python, JavaScript/Electron |
| Tools | Git, VS Code |

---

## Desktop tools

Earlier self-built utilities, kept for reference.

**HighlighterTXT** — Offline Electron utility for text annotation, highlighting
and local workspace management, with a custom encrypted file format.

**AetherMask** — Windows utility for inspecting local network adapter
configuration and system telemetry.

---

## Contact

📧 andrea.ronconi.jobs@gmail.com
💼 [linkedin.com/in/andrearonconi](https://www.linkedin.com/in/andrearonconi)
🌐 [gt0u-labs.github.io](https://gt0u-labs.github.io/)

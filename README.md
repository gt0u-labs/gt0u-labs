# Andrea Ronconi — GT0u Labs

### Technical Support · Infrastructure · Linux · Proxmox · Docker · Monitoring

![Linux](https://img.shields.io/badge/Linux-Ubuntu_|_Arch_|_Kali-2bbc8a?style=for-the-badge&logo=linux&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-Loki_&_Promtail-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Location](https://img.shields.io/badge/Bucharest-Open_to_Ticino_&_Italy-white?style=for-the-badge&logo=googlemaps&logoColor=red)

---

## About

Self-taught technical profile focused on **Linux systems, virtualization,
containers, monitoring and infrastructure troubleshooting**.

I learn by building systems, breaking them, reading logs and documenting how I
fixed them.

Built and operated a two-node homelab using **Ubuntu Server, Proxmox VE, Docker,
Grafana, Loki, Promtail and Uptime Kuma**.

**Currently targeting:** Junior Technical Support · NOC · Infrastructure ·
System Administration, with an active move toward Defensive Security / SOC.

🇮🇹 Italian citizen · Based in Bucharest · Open to relocation to **Ticino & Italy**

**Languages:** Italian (native) · Spanish (native) · Romanian (fluent) ·
English (B2) · German (A1)

---

## 🏠 Homelab

### Node 1 — Ubuntu Server

`Docker` · `Docker Compose` · `Grafana` · `Loki` · `Promtail` · `Uptime Kuma`

Centralized logging, service monitoring and self-hosted infrastructure.

### Node 2 — Proxmox VE

`VM provisioning` · `LVM` · `GPU passthrough` · `USB passthrough`

Kali Linux and Ubuntu Server VMs used for infrastructure, networking and
security labs.

→ [Explore the homelab](https://github.com/gt0u-labs/homelab-notes)

---

## 🔧 Selected Work

### GPU Passthrough Troubleshooting — Proxmox / VFIO

Diagnosed a PCI ROM signature error using `dmesg`, resolved it with a
card-specific VBIOS via `romfile=`, configured USB passthrough and corrected
VM boot/display configuration.

→ [Read the write-up](https://github.com/gt0u-labs/security-learning-log/blob/main/writeups/proxmox-gpu-passthrough.md)

### Service Monitoring & Recovery

Simulated an Nginx outage, detected it through Uptime Kuma, restored the service
and verified recovery through monitoring and HTTP checks.

→ [View the incident lab](https://github.com/gt0u-labs/homelab-notes/tree/main/projects/service-monitoring-incident)

### Support Playbook

A small first-response runbook for service outages, SSH connectivity,
resource problems and log-driven troubleshooting.

→ [View the playbook](https://github.com/gt0u-labs/homelab-notes/tree/main/support-playbook)

---

## 🔐 Security

Hands-on training across **HTB Academy, HTB Labs and TryHackMe**, focused on:

`Alert triage` · `Log analysis` · `Phishing analysis` · `Traffic analysis` ·
`Networking` · `IAM` · `Web security fundamentals`

64 modules, rooms and machines completed, documented with notes on what each
one covered.

→ [Security learning log](https://github.com/gt0u-labs/security-learning-log)

### Valve / HackerOne

Identified an outdated FFmpeg dependency in the Steam Link Linux client and
mapped it to CVE-2020-22015.

The report was submitted through Valve's HackerOne program and closed as
**Informative** because exploitability was not demonstrated with a working PoC.

The main takeaway: identifying a vulnerable dependency is not the same as
demonstrating that the vulnerable code path is reachable.

---

## 🛠 Stack

`Linux` · `Windows` · `Proxmox VE` · `Docker` · `Docker Compose` ·
`Grafana` · `Loki` · `Promtail` · `Nginx` · `SSH` · `DNS` · `Nmap` ·
`Burp Suite` · `Bash` · `Python` · `JavaScript` · `Git`

---

## 📫 Contact

📧 **andrea.ronconi.jobs@gmail.com**

💼 [LinkedIn](https://www.linkedin.com/in/andrearonconi)

🌐 [Portfolio](https://gt0u-labs.github.io/)

---

<p align="center">
  <sub>Built through hands-on labs, troubleshooting and a lot of broken configurations.</sub>
</p>

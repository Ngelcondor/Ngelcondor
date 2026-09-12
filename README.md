## Giuseppe Diana

Computer Engineering student at UOC, Barcelona — working toward offensive
security. Currently on **HTB CPTS**, then OSCP. I hold **TryHackMe PT1**.

Most of what I build is infrastructure and tooling for my own practice: a lab I
have to keep running, recon that has to be safe to point at a live bug bounty
program, and notes I'll still understand in six months.

---

### What's here

| | |
|---|---|
| **[pt1-pentest-report](https://github.com/Ngelcondor/pt1-pentest-report)** | The report from my TryHackMe PT1 practical exam — a 48-hour engagement across web, network and Active Directory, all ten findings exploited. Redacted, published as a writing sample: report writing is half the job and rarely shows up in a portfolio. |
| **[pentest-lab-infra](https://github.com/Ngelcondor/pentest-lab-infra)** | IaC for a self-hosted pentest lab on bare metal — GOAD Active Directory range on Proxmox, passive recon stack in Docker, Ansible host hardening. One internet-facing port by design. |
| **[bb-recon-toolkit](https://github.com/Ngelcondor/bb-recon-toolkit)** | Bug bounty recon in Bash. Passive and active are separate, active gates on scope acknowledgement, conservative rate limits, no intrusive templates. Plus the report templates I submit with. |
| **[ctf-writeups](https://github.com/Ngelcondor/ctf-writeups)** | HTB, Vulnlab and TryHackMe machines. Mostly Active Directory — a lot of it ends in AD CS abuse. Flags redacted, published only where the platform allows. |
| **[giuseppe-dashboard](https://github.com/Ngelcondor/giuseppe-dashboard)** | The thing I actually run in production. FastAPI + Celery + PostgreSQL behind a Next.js PWA, containerised, TLS, background sync from Apple Health and open banking. Designed around an ADHD/ASD-friendly low-stimulation mode rather than bolting accessibility on afterwards. |
| **[pentest-notes-agent](https://github.com/Ngelcondor/pentest-notes-agent)** | Turns raw terminal output into structured Obsidian notes, and curates reusable commands into cheatsheets. Python, Textual TUI, MIT. |
| **[cyberpunk-ctf-terminal](https://github.com/Ngelcondor/cyberpunk-ctf-terminal)** | My Kali working environment — tmux, Dracula, Starship, a four-pane layout built around how an HTB session actually goes. |

---

### What I'm working with

**Offensive** — nmap, ffuf, feroxbuster, Burp Suite, sqlmap, nuclei, subfinder,
httpx · **AD** — impacket, NetExec, BloodHound, certipy, Rubeus, evil-winrm ·
**Credentials** — hashcat, john, kerbrute · **Post-ex** — ligolo-ng, chisel,
linpeas/winpeas

**Building** — Python, Bash, Ansible, Docker, Proxmox, Terraform/Packer

---

### Where I'm going

Junior penetration tester, with a bias toward Active Directory and internal
network work. I'm also interested in the security of AI systems — which is
partly why my lab runs a local model against its own recon output, and partly
why I keep ending up reading about prompt injection instead of sleeping.

Everything I publish comes from labs I own, platforms I hold an account with, or
bug bounty programs with scope I've read.

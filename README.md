<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:161b22&height=120&section=header" width="100%" />

</div>

<div align="center">

```
   ___  _____   __  _____ _____ ___   _   _ _____ _____ 
  |_  |/ _ \ \ / / /  ___|_   _/ _ \ | \ | |_   _/  ___|
    | / /_\ \ V /  \ `--.  | |/ /_\ \|  \| | | | \ `--. 
    | |  _  |\ /    `--. \ | ||  _  || . ` | | |  `--. \
/\__/ / | | || |   /\__/ / | || | | || |\  | | | /\__/ /
\____/\_| |_/\_/   \____/  \_/\_| |_/\_| \_/ \_/ \____/ 
```

**Associate Principal Network Engineer · NetDevOps · Infrastructure Automation · AI Systems**

*Building the bridge between network engineering and software development.*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jay-stants/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:jay.stants@sutherlandglobal.com)

</div>

---

### `> whoami`

```yaml
name:     Jay Stants
role:     Associate Principal Network Engineer
focus:    NetDevOps · SD-WAN · Enterprise Infrastructure · AI Systems
mindset:  Automate everything. Document everything. Break nothing.
```

I work at the intersection of **network engineering** and **software development** — designing scalable enterprise infrastructure, then writing the tools to manage it. Currently building out a NetDevOps practice: CI/CD pipelines for network configs, Python automation frameworks, and GitOps workflows for infrastructure as code.

On the side, I'm building **OB1** — a self-hosted, local-first AI workspace with persistent memory, local LLM inference, and an n8n-powered automation layer. No cloud dependency. No data leaving the box.

---

### `> tech_stack`

<div align="center">

#### 🌐 Network

![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![SD-WAN](https://img.shields.io/badge/SD--WAN-00BCEB?style=for-the-badge&logo=cisco&logoColor=white)
![Meraki](https://img.shields.io/badge/Meraki-67B346?style=for-the-badge&logo=cisco&logoColor=white)
![Cisco ISE](https://img.shields.io/badge/Cisco_ISE-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Catalyst Center](https://img.shields.io/badge/Catalyst_Center-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Cisco Wireless](https://img.shields.io/badge/Cisco_Wireless-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![BGP](https://img.shields.io/badge/BGP-4A4A4A?style=for-the-badge&logoColor=white)

#### ⚙️ Automation & Dev

<a href="https://skillicons.dev">
  <img src="https://skillicons.dev/icons?i=py,ansible,gitlab,docker,flask,react,bash,git,fastapi,github&theme=dark&perline=5" />
</a>

![NetBox](https://img.shields.io/badge/NetBox-00857D?style=for-the-badge&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)

#### 🤖 AI & Local LLMs

![Ollama](https://img.shields.io/badge/Ollama-2D2D2D?style=for-the-badge&logoColor=white)
![LiteLLM](https://img.shields.io/badge/LiteLLM-5046E4?style=for-the-badge&logoColor=white)
![Open WebUI](https://img.shields.io/badge/Open_WebUI-1C1C1C?style=for-the-badge&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Claude API](https://img.shields.io/badge/Claude_API-CC785C?style=for-the-badge&logoColor=white)

#### 🖥️ Infrastructure

![Linux](https://img.shields.io/badge/Linux-2B2B2B?style=for-the-badge&logo=linux&logoColor=FCC624)
![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![GitLab CE](https://img.shields.io/badge/GitLab_CE-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![YAML](https://img.shields.io/badge/YAML-CB171E?style=for-the-badge&logo=yaml&logoColor=white)

</div>

---

### `> ob1_system`

<div align="center">

**OB1 — Open Brain** &nbsp;·&nbsp; *Self-hosted · Local-first · Private AI Workspace*

</div>

A personal AI system with persistent memory and no cloud dependency. Built on a 7-service microservice architecture, running on a dedicated workstation (RTX 5060 Ti). Local LLM inference via Ollama, semantic memory via PostgreSQL + pgvector, and n8n as the automation backbone.

```
Request Flow
──────────────────────────────────────────────────────────────
  User → Gateway (8000) → Orchestrator (8001) → Worker (8002)
                                                     ↕          ↕
                                               Memory (8003)  Tools (8004)
                                                        ↓
                                               Observer (8005) → Result
```

```yaml
inference:   Ollama (primary)  →  LiteLLM router  →  OpenRouter (cloud fallback)
memory:      PostgreSQL + pgvector  (fully local, replaced Supabase)
interface:   Open WebUI  +  Claude via Cowork (complex reasoning tasks)
automation:  n8n (self-hosted)
tools:       ClickUp · Thoughts · Projects · Contacts · Household · Meals · Maintenance
```

**Active n8n workflows:**

```
▸  SOUL serve       /webhook/soul          — SOUL.md prepended to every Open WebUI session
▸  Memory Governor  /webhook/store-memory  — handles persistent memory write operations
▸  Spark            weekdays @ 8:45 AM ET  — morning context briefing
▸  Weekly Review    Sundays  @ 9:00 AM ET  — retrospective and planning digest
```

---

### `> current_projects`

```
▸  OB1 — Open Brain             — Self-hosted private AI: 7-service arch, local LLMs, RAG memory
▸  NetDevOps Pipeline Framework — CI/CD standards for network config management
▸  SD-WAN Topology Visualizer   — Python/SVG tooling for network diagram generation
▸  Infrastructure Automation    — Ansible playbooks for enterprise network ops
▸  AAA Migration                — Enterprise-wide ISE deployment replacing legacy RADIUS/TACACS
▸  Homelab                      — Proxmox-based dev/test environment
```

---

### `> github_stats`

<div align="center">

<img src="https://streak-stats.demolab.com?user=jay-stants&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff&sideLabels=c9d1d9&dates=c9d1d9&currStreakNum=c9d1d9&sideNums=c9d1d9" height="150" />

</div>

---

<div align="center">

*"The network is the computer — so let's write better software for it."*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:161b22,100:0d1117&height=80&section=footer" width="100%" />

</div>

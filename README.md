<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:050d1a,100:003566&height=220&section=header&text=Mirko%20Olivares&fontSize=58&fontColor=00d4ff&animation=twinkling&fontAlignY=40&desc=Fullstack+Developer+%7C+SOC+Analyst&descSize=21&descAlignY=63&descColor=90e0ef" />

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=900&color=00D4FF&center=true&vCenter=true&width=540&lines=Fullstack+Developer+%7C+SOC+Analyst;Node.js+%7C+React+%7C+FastAPI+%7C+Angular;Wazuh+%7C+Suricata+%7C+TheHive+%7C+MISP;Building+things+%26+defending+them." />
</p>

<p align="center">
  <a href="https://linkedin.com/in/mirko-olivares-43b3412a6">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:fehusentinel@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <img src="https://komarev.com/ghpvc/?username=FehuSentinel&color=00d4ff&style=for-the-badge&label=PROFILE+VIEWS" />
</p>

---

## `$ whoami`

```yaml
name    : Mirko Daniel Olivares Pérez
role    : Fullstack Developer & SOC Analyst
degree  : Analista Programador Fullstack — INACAP (2024)
study   : Ingeniería en Informática — INACAP (2023–2026)
lab     : SOC on Proxmox → Wazuh · Suricata · TheHive 5 · MISP · Cortex
location: Santiago, Chile 🇨🇱
```

> I build web applications and defend the infrastructure they run on.
> Rare combo: I understand how systems are built — and how they break.

---

## `$ ls skills/`

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,python,fastapi,django,cs&perline=6" />
  <br/>
  <img src="https://skillicons.dev/icons?i=react,angular,js,ts,html,css&perline=6" />
  <br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,sqlite,redis,graphql&perline=6" />
  <br/>
  <img src="https://skillicons.dev/icons?i=aws,gcp,docker,git,linux,azure&perline=6" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Wazuh_SIEM-005571?style=for-the-badge&logo=elastic&logoColor=white" />
  <img src="https://img.shields.io/badge/Suricata_IDS-EF7D17?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/TheHive_5-FF7900?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/MISP-003087?style=for-the-badge&logoColor=white" />
  <img src="https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white" />
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white" />
  <img src="https://img.shields.io/badge/MITRE_ATT%26CK-E60026?style=for-the-badge&logoColor=white" />
</p>

---

## `$ cat projects/soc-lab.md`

<details>
<summary><b>🏗️ SOC Personal Lab — Click to expand</b></summary>

<br/>

> Full defensive security stack deployed on Proxmox — designed, built, and maintained by me.

```
┌──────────────────────────────────────────────────────────────┐
│                     PROXMOX HYPERVISOR                       │
│                                                              │
│   Network Layer                                              │
│   ┌────────────┐   ┌────────────┐   ┌──────────────────┐   │
│   │  Suricata  │   │  Zeek/Bro  │   │  PfSense / VLANs │   │
│   │  IDS/IPS   │   │  Net Meta  │   │  WireGuard VPN   │   │
│   └─────┬──────┘   └─────┬──────┘   └──────────────────┘   │
│         └───────┬─────────┘                                  │
│                 ▼                                            │
│   ┌─────────────────────┐                                   │
│   │     Wazuh SIEM      │  ← agents on all hosts            │
│   │  custom rules +     │  ← correlation + alerting         │
│   │  correlation engine │                                    │
│   └──────────┬──────────┘                                   │
│              │                                               │
│              ▼                                               │
│   ┌──────────────────┐    ┌──────────────────────────────┐  │
│   │   TheHive 5      │───▶│  Cortex (auto-analyzers)     │  │
│   │  incident mgmt   │    │  VirusTotal · AbuseIPDB      │  │
│   │  case tracking   │    └──────────────┬───────────────┘  │
│   └──────────────────┘                   │                  │
│                                          ▼                   │
│                              ┌───────────────────────┐      │
│                              │  MISP (Threat Intel)  │      │
│                              │  IOC management       │      │
│                              └───────────────────────┘      │
└──────────────────────────────────────────────────────────────┘
```

**What I built:**
- Custom Wazuh correlation rules & detection logic
- Automated pipeline: `Wazuh → TheHive → Cortex → MISP`
- IOC enrichment via VirusTotal & AbuseIPDB APIs
- Incident response playbooks documented end-to-end
- Network segmentation with VLANs + WireGuard VPN

</details>

---

## `$ git log --oneline projects/`

| Project | Stack | Highlights |
|---------|-------|------------|
| 🏗️ **SOC Personal Lab** | Wazuh · Suricata · TheHive · MISP · Proxmox | Full defensive stack, automated pipeline |
| 🛒 **E-commerce (×2)** | Express · FastAPI · React · Angular · PostgreSQL | Payment gateway, full CRUD |
| 📊 **ETL + Auto Alerts** | Python · C# | Data pipeline + email alerting on change |
| 🏢 **Enterprise Dashboard** | Node.js · Angular · MySQL · SQL Server | Multi-DB platform, built in production |

---

## `$ cat certifications.txt`

<p align="center">

| Certification | Issuer |
|:---|:---|
| 🔐 Analista de Ciberseguridad | Google / Coursera |
| 🔴 Ethical Hacker | Cisco Networking Academy |
| 🛡️ Introducción a Ciberseguridad | Cisco |
| 🌐 Redes Básicas | Cisco |
| ☁️ AWS Cloud Foundations | Amazon Web Services |

</p>

---

## `$ cat stats.json`

<p align="center">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=FehuSentinel&show_icons=true&hide_border=true&bg_color=0d1117&title_color=00d4ff&icon_color=00d4ff&text_color=c9d1d9&include_all_commits=true&count_private=true" />
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=FehuSentinel&layout=compact&hide_border=true&bg_color=0d1117&title_color=00d4ff&text_color=c9d1d9&langs_count=8" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=FehuSentinel&theme=tokyonight&hide_border=true&background=0D1117&stroke=00D4FF&ring=00D4FF&fire=ff6b35&currStreakLabel=00D4FF&sideLabels=c9d1d9&dates=c9d1d9" />
</p>

---

## `$ cat trophies.log`

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=FehuSentinel&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&row=1&column=7" />
</p>

---

## `$ tail -f contributions.log`

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=FehuSentinel&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00d4ff&line=00d4ff&point=ffffff&area=true&area_color=003566" />
</p>

---

## `$ ./snake.sh --eat-contributions`

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FehuSentinel/FehuSentinel/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/FehuSentinel/FehuSentinel/output/snake.svg" />
    <img alt="contribution snake animation" src="https://raw.githubusercontent.com/FehuSentinel/FehuSentinel/output/snake-dark.svg" />
  </picture>
</p>

---

<p align="center">
  <i>"I build the systems. I also know how they fall."</i>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:003566,50:050d1a,100:0d1117&height=130&section=footer" />

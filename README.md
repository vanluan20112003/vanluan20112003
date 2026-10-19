<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:020617,55:0F172A,100:2563EB&text=LE%20VAN%20LUAN&fontColor=E2E8F0&fontSize=52&fontAlignY=38&desc=Fullstack%20%C2%B7%20Data%20Systems%20%C2%B7%20Infrastructure&descSize=17&descAlignY=58&animation=fadeIn" width="100%" alt="Le Van Luan" />

<a href="https://github.com/vanluan20112003">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=3200&pause=900&color=38BDF8&center=true&vCenter=true&width=720&lines=Building+university+data+platforms+end-to-end;From+database+schema+to+dashboards+leadership+trusts;Syncing+national+education+data+with+HEMIS;AI+analytics+that+cites+its+numbers;Linux+%C2%B7+Docker+%C2%B7+Wazuh+%C2%B7+Open+edX" alt="Typing intro" />
</a>

<p>
  <a href="https://github.com/vanluan20112003"><img src="https://img.shields.io/badge/GitHub-vanluan20112003-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
  <img src="https://img.shields.io/badge/Based_in-Ho_Chi_Minh_City-0F172A?style=for-the-badge&logo=googlemaps&logoColor=38BDF8" alt="Ho Chi Minh City"/>
  <img src="https://img.shields.io/badge/Open_to-Collaboration-0F172A?style=for-the-badge" alt="Open to collaboration"/>
</p>

</div>

```yaml
whoami:
  name: Le Van Luan
  role: Fullstack Developer · Data & Systems
  works_on:
    - University data platform (HR, students, reporting)   # HUFLIT DataSystem
    - National education data sync                         # HEMIS integration
    - Online learning infrastructure                       # Open edX · H5P
    - Endpoint monitoring & security                       # Wazuh
  stack_of_choice: [Python, Django, PHP, Laravel, React, Next.js, PostgreSQL, MySQL, Docker, Linux]
  believes: "A number on a dashboard is only as good as the pipeline behind it."
```

---

## ⚡ What I do

I build systems **end to end**: model the data, write the APIs, ship the UI, then run it on Linux servers and keep it observable.
Most of my work lives where **software meets institutional data**: messy source records, strict reporting rules, and leaders who need numbers they can trust.

<table>
<tr>
<td width="50%" valign="top">

**🧱 Build**
- Backend & REST APIs (Django, Laravel)
- Admin dashboards & reporting UIs (React)
- Data models, validation, integration contracts

</td>
<td width="50%" valign="top">

**📊 Data**
- Staging → warehouse → reporting layers
- Data-quality rules & anomaly checks
- AI-assisted analysis grounded in real queries

</td>
</tr>
<tr>
<td width="50%" valign="top">

**🐧 Run**
- Linux server administration
- Docker / Tutor deployments, Nginx
- Video pipelines (FFmpeg → HLS)

</td>
<td width="50%" valign="top">

**🛡️ Secure**
- Wazuh endpoint monitoring
- SSH activity & process tracing
- Role-based access & privacy-aware reporting

</td>
</tr>
</table>

---

## 🛠️ Tech Stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=py,php,ts,js,html,css,bash&perline=7" alt="Languages"/>

**Frameworks**<br/>
<img src="https://skillicons.dev/icons?i=django,fastapi,laravel,wordpress,react,nextjs,tailwind&perline=7" alt="Frameworks"/>

**Data & Infrastructure**<br/>
<img src="https://skillicons.dev/icons?i=postgres,mysql,redis,supabase,docker,nginx,linux,ubuntu&perline=8" alt="Data and infrastructure"/>

**Tooling & Observability**<br/>
<img src="https://skillicons.dev/icons?i=git,github,githubactions,prometheus,grafana,vscode&perline=6" alt="Tooling"/>

<br/>

<img src="https://img.shields.io/badge/Open_edX-Tutor-0F172A?style=flat-square" alt="Open edX"/>
<img src="https://img.shields.io/badge/Wazuh-SIEM%2FEDR-0F172A?style=flat-square&logo=wazuh&logoColor=38BDF8" alt="Wazuh"/>
<img src="https://img.shields.io/badge/FFmpeg-HLS-0F172A?style=flat-square&logo=ffmpeg&logoColor=22C55E" alt="FFmpeg"/>
<img src="https://img.shields.io/badge/H5P-Interactive_content-0F172A?style=flat-square" alt="H5P"/>
<img src="https://img.shields.io/badge/Claude_Code-AI_engineering-0F172A?style=flat-square&logo=anthropic&logoColor=F97316" alt="Claude Code"/>

</div>

---

## 🚀 Featured Work

### 🏛️ HUFLIT DataSystem — University Data & Reporting Platform
<img src="https://img.shields.io/badge/status-active_development-2563EB?style=flat-square" alt="status"/>

A data platform for managing university personnel and organizational data, and turning it into reports leadership can act on.

```mermaid
flowchart LR
    A[(HR & org<br/>source data)] --> B[Staging<br/>+ validation rules]
    B --> C[(Reporting<br/>warehouse)]
    C --> D[📊 KPI dashboards<br/>drill-down by unit]
    C --> E[🤖 AI analyst<br/>read-only, cites numbers]
    C --> F[🔄 HEMIS sync<br/>Ministry of Education]
    B -. quality report .-> G[⚠️ Data-quality<br/>checks & anomalies]
```

- **Workforce dashboards**: headcount, qualifications, succession risk and productivity, with year-over-year trends and drill-down to each faculty.
- **Data-quality layer**: rule-based checks (missing unit, invalid birth dates, contract gaps) surfaced to users instead of silently skewing reports.
- **AI-assisted analysis**: an analyst that only reads the warehouse, writes findings with charts, and checks every number it states against the source data.
- **Privacy by design**: small-group suppression for sensitive breakdowns and access scoped by role.
- **HEMIS integration**: national education data sync using OAuth2 plus an XML digital-signature session, followed by JSON sync APIs.

`Django` `PostgreSQL` `React` `Data Warehouse` `ETL` `LLM` `System Integration`

---

### 🎓 MOOC VNU — Open edX Learning Platform
<img src="https://img.shields.io/badge/status-contributing-22C55E?style=flat-square" alt="status"/>

Development and operations for a university MOOC platform built on Open edX.

- Deploy and configure services with **Tutor** on Docker.
- Extend Django-based platform components and integrations for learning workflows.

`Python` `Django` `Open edX` `Tutor` `Docker` `Linux`

---

### 🛡️ Wazuh Endpoint Monitoring → EDR
<img src="https://img.shields.io/badge/status-active_R%26D-F59E0B?style=flat-square" alt="status"/>

Extending an existing Wazuh deployment toward EDR capabilities instead of buying a commercial product.

- Log analysis and predictive risk alerts for monitored endpoints.
- **SSH session visibility**: who logged in and what they did afterwards, traced through process relationships.
- Separate monitoring pipelines for SSH activity and high-volume web traffic.

`Wazuh` `Linux` `Log Correlation` `Security Automation`

---

### 🎬 H5P Video Infrastructure
<img src="https://img.shields.io/badge/status-in_operation-22C55E?style=flat-square" alt="status"/>

Delivering video-based interactive learning content on constrained servers.

- Multi-resolution transcoding with **FFmpeg** and **HLS** adaptive streaming.
- Balancing concurrent encoding jobs against CPU and storage limits.

`WordPress` `H5P` `PHP` `FFmpeg` `HLS` `Linux`

---

### 🏡 Nhà Đất Luyện Phát — Real Estate Website
<a href="https://github.com/vanluan20112003/NhaDatLuyenPhat"><img src="https://img.shields.io/badge/repo-NhaDatLuyenPhat-0F172A?style=flat-square&logo=github" alt="repo"/></a>

A production website on a **$0 infrastructure budget**.

- Next.js static export, deployed to GitHub Pages through GitHub Actions.
- Supabase for Postgres, image storage and Edge Functions, with Row Level Security policies.

`Next.js` `Supabase` `PostgreSQL` `GitHub Actions`

---

## 📈 GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=vanluan20112003&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0F172A&title_color=38BDF8&icon_color=38BDF8&rank_icon=github" alt="GitHub stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=vanluan20112003&layout=compact&theme=tokyonight&hide_border=true&bg_color=0F172A&title_color=38BDF8" alt="Top languages"/>

<img src="https://streak-stats.demolab.com?user=vanluan20112003&theme=tokyonight&hide_border=true&background=0F172A&ring=38BDF8&fire=F97316&currStreakLabel=38BDF8" alt="Contribution streak"/>

</div>

---

## 🧭 Engineering Principles

```diff
+ Understand the domain before writing the schema.
+ Make data trustworthy: validate, trace, and show your sources.
+ Design for the next maintainer: clear boundaries, explicit contracts.
+ Measure, don't guess: test assumptions and monitor what you ship.
- Ship a dashboard nobody can explain.
```

## 🔭 Currently Leveling Up

| Area | Focus |
|---|---|
| **Data Engineering** | Staging layers, slowly changing dimensions, analytical models |
| **AI & Analytics** | Text-to-SQL, RAG, evidence-based reporting with LLMs |
| **DevOps** | Container orchestration, reverse proxies, centralized logging |
| **Quality** | API & end-to-end testing, secure development practices |

---

<div align="center">

### 🤝 Let's build something reliable

Interested in **data platforms**, **digital transformation in education**, and **infrastructure**? Let's connect.

<a href="https://github.com/vanluan20112003"><img src="https://img.shields.io/badge/Follow_on_GitHub-0F172A?style=for-the-badge&logo=github&logoColor=white" alt="Follow"/></a>
<!-- Add more contact badges when ready, e.g.:
<a href="https://www.linkedin.com/in/YOUR-ID"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:YOUR-EMAIL"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
-->

<img src="https://komarev.com/ghpvc/?username=vanluan20112003&style=flat-square&color=2563EB&label=profile+views" alt="Profile views"/>

<img src="https://capsule-render.vercel.app/api?type=waving&height=110&color=0:2563EB,55:0F172A,100:020617&section=footer" width="100%" alt="footer"/>

</div>

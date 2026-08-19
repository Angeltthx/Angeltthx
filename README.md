<img width="1774" height="887" alt="image" src="https://github.com/user-attachments/assets/7d164d5e-a854-4f11-862d-5723cc22e8df" />
<p align="center">

</p>

<h1 align="center">Ángel García</h1>

<p align="center">
  <strong>Software Developer</strong><br>
  Backend · Full Stack · Cloud · Security
</p>

<p align="center">
  <a href="mailto:angelotthx@gmail.com">
    <img src="https://img.shields.io/badge/angelotthx@gmail.com-6E5BFF?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="www.linkedin.com/in/angel-garcia-dev">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <img src="https://img.shields.io/badge/Bogotá,%20Colombia-1F2233?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Bogotá, Colombia">
</p>

<br>

## About

I build software end to end — from the database and the business logic up to the
interface and the deployment environment. Most of my work has lived in that full
vertical: relational design and stored procedures on one side, APIs and
interfaces on the other.

What I care about is the part that doesn't show up in a demo: whether the system
still makes sense six months later, whether someone else can pick it up without
asking me what it does, and whether the decisions behind it were written down or
just happened.

Right now I'm building an intelligent cyber range as my degree project, which
has pushed me into infrastructure, virtualization and detection engineering —
territory I didn't expect to enjoy as much as I do.

<br>

---

## Featured work

### CyberRange — Intelligent cybersecurity training lab

An instructor describes a training scenario in plain language. The system turns
it into a validated definition, provisions it as real virtual machines, runs an
emulated attack chain against it, and the participant has to interpret what the
SIEM actually managed to detect.

The design decision I'd defend first: every scenario leaves at least one stage
deliberately uncovered by any correlation rule. An exercise where everything gets
detected teaches nothing about the gap between what happens and what a monitoring
stack can see.

- **Two interchangeable execution engines** behind one interface — real virtual
  machines, or a synthetic engine that reproduces the log byte for byte from a seed
- **Ports-and-adapters architecture**: the domain layer has no idea whether it's
  running on real hardware, which is what makes both modes possible from one script
- **Emulated techniques mapped to MITRE ATT&CK**, never real malware, on an
  isolated network with no outbound access
- **A language model that translates intent into a scenario** — from a closed
  catalog, schema-validated, and fully disableable so the system works offline

`Python` · `FastAPI` · `Pydantic` · `React` · `TypeScript` · `Wazuh` · `Proxmox VE` · `Ansible`

<a href="https://github.com/Angeltthx/Cyberrange"><b>View repository →</b></a>

<br>

### Territorios Vivos

Web platform presenting geographic and multimedia content through an interactive
interface. The interesting constraint was volume: a large catalog of video that
had to stay responsive without collapsing the initial load.

`React` · `TypeScript` · `Interactive maps` · `Vimeo API`

<a href="https://github.com/Angeltthx/[repo]"><b>View repository →</b></a>

<br>

### EnergyDistributionAPI

Backend system that processes, stores and analyzes electric power distribution
data, exposing the analytical layer through a REST API. Most of the work was in
the database architecture and in loading historical data efficiently.

`C#` · `.NET` · `SQL` · `REST API`

<a href="https://github.com/Angeltthx/[repo]"><b>View repository →</b></a>

<br>

### Payroll Management System

Payroll solution covering employees, contracts and settlements, with the business
rules implemented as database logic in PL/SQL. Relational design, stored
procedures and automated processes.

`Java` · `Oracle` · `PL/SQL`

<a href="https://github.com/Angeltthx/[repo]"><b>View repository →</b></a>

<br>

### ZonaFitGYM

Gym management application with client administration and CRUD operations exposed
through several interfaces over the same backend.

`Java` · `Spring Boot` · `JSF` · `PrimeFaces`

<a href="https://github.com/Angeltthx/[repo]"><b>View repository →</b></a>

<br>

---

## Tech stack

**Languages**

<p>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

**Backend & APIs**

<p>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotnet&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/PL%2FSQL-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
</p>

**Databases**

<p>
  <img src="https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white"/>
</p>

**Infrastructure & Tools**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black"/>
  <img src="https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
</p>

<br>

---

## How I work

**Decisions get written down, not just code.** Every architectural choice in my
current project has a short record: the context, the alternatives I discarded and
what each one costs. It makes the reasoning defensible instead of implicit.

**Tests protect promises, not lines.** A test earns its place when it guards
something the system claims to do. Reproducibility is the claim my current project
lives or dies by, so that's the test that runs on every change.

**"I'm not sure" is cheap in week one.** Finding out that a licence expires or a
dependency changed its terms costs almost nothing early and a great deal late.

<br>

---

## Currently

- Building the orchestrator layer of the CyberRange project — provisioning,
  execution lifecycle and SIEM integration
- Going deeper into detection engineering and log analysis
- Open to **internship and entry-level opportunities** in backend development,
  cloud, or security engineering

<br>

---

<h3 align="center">Let's connect</h3>

<p align="center">
  <a href="mailto:angelotthx@gmail.com">angelotthx@gmail.com</a><br>
  <sub>Bogotá, Colombia · open to remote</sub>
</p>

<p align="center">
  <a href="mailto:angelotthx@gmail.com">
    <img src="https://img.shields.io/badge/Email-6E5BFF?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/[verifica-tu-usuario]">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="https://github.com/Angeltthx">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  </a>
</p>

<p align="center">
  <img src="./assets/banner.png" alt="Developer — I code. I create. I explore." width="100%">
</p>

<h1 align="center">[Tu nombre completo]</h1>

<p align="center">
  <strong>Backend &amp; Security Engineering</strong> · Bogotá, Colombia
</p>

<p align="center">
  <a href="mailto:[tu-correo@ejemplo.com]">
    <img src="https://img.shields.io/badge/Email-informational?style=flat-square&logo=gmail&logoColor=white&color=6E5BFF" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/[tu-usuario]">
    <img src="https://img.shields.io/badge/LinkedIn-informational?style=flat-square&logo=linkedin&logoColor=white&color=0A66C2" alt="LinkedIn">
  </a>
</p>

---

## About

I'm a Systems Engineering student in Bogotá, working at the point where backend
development meets defensive security. Most of what I build starts from the same
question: what does this system actually do when something goes wrong, and how
would anyone find out?

I care about decisions being written down, claims being verifiable, and code
that someone else can pick up six months later without asking me what it does.

---

## Featured project

### CyberRange — Intelligent cybersecurity training lab

A degree project. An instructor describes a training scenario in plain language;
the system turns it into a structured definition, provisions it as real virtual
machines, runs an emulated attack chain against it, and the participant has to
interpret what the SIEM actually managed to detect.

The interesting part is what the SIEM *doesn't* see. Every scenario leaves at
least one stage deliberately uncovered by any correlation rule, so the exercise
teaches the detection gap instead of rewarding pattern matching.

**What it involves**

- Real infrastructure: virtual machines on a type 1 hypervisor, isolated network,
  no outbound access — attack techniques are emulated, never real malware
- Wazuh as the SIEM, with custom rules mapped to MITRE ATT&CK techniques
- A language model that translates intent into a validated scenario — from a
  closed catalog, schema-checked, and fully disableable
- Two interchangeable execution engines behind one interface: real virtual
  machines, or a synthetic engine that reproduces the log byte for byte from a seed
- Ports-and-adapters architecture, so the domain has no idea whether it's running
  on real hardware or not

**Stack** — Python · FastAPI · Pydantic · React · TypeScript · Vite · Wazuh ·
Proxmox VE · Ansible · SQLite

<p>
  <a href="https://github.com/Angeltthx/Cyberrange">
    <img src="https://img.shields.io/badge/View%20repository-6E5BFF?style=for-the-badge&logo=github&logoColor=white" alt="View repository">
  </a>
</p>

---

## Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

**Backend**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=for-the-badge&logo=pydantic&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**Infrastructure & Security**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-005C8A?style=for-the-badge&logoColor=white)
![MITRE ATT&CK](https://img.shields.io/badge/MITRE%20ATT%26CK-C7332F?style=for-the-badge&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## How I work

**I write down the decisions, not just the code.** Every architectural choice in
my current project has a short record: the context, the alternatives I discarded,
and what it costs me. It makes the reasoning defensible instead of implicit.

**I test the claims, not the lines.** A test earns its place when it protects a
promise the system makes. Reproducibility is the one my current project lives or
dies by, so that's the test that runs on every change.

**I'd rather say "I'm not sure" early.** Finding out a licence expires or a
dependency changed its terms is cheap in week one and expensive in week ten.

---

## Currently

- Building the orchestrator layer of the CyberRange project
- Learning more about detection engineering and log analysis at scale
- Open to [internship / entry-level / freelance] opportunities in backend
  development or security engineering

---

<p align="center">
  <sub>Bogotá, Colombia · <a href="mailto:[angelotthx@gmail.com]">[tu-correo@ejemplo.com]</a></sub>
</p>

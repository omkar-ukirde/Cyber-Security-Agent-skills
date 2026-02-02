# Security Skills

A comprehensive collection of AI-powered penetration testing skills following the [Agent Skills](https://agentskills.io) open standard.

## Overview

This repository contains structured skill files for AI agents to perform systematic security testing. Skills are organized using OWASP Top 10 categories for web and logical service groups for network.

## Directory Structure

```
security_skills/
├── README.md
├── skills/
│   ├── web/                    # Web application skills (OWASP-based)
│   │   ├── SKILL.md           # Web skills overview
│   │   ├── a01-broken-access-control/
│   │   │   ├── SKILL.md
│   │   │   └── references/
│   │   ├── a03-injection/
│   │   └── ...
│   ├── network/                # Network service skills
│   │   ├── SKILL.md           # Network skills overview
│   │   ├── reconnaissance/
│   │   │   ├── SKILL.md
│   │   │   └── references/
│   │   ├── databases/
│   │   └── ...
│   └── mobile/                 # Mobile security skills
```

## Agent Skills Format

Each skill folder follows the standard:
- **`SKILL.md`** - Required entrypoint with YAML frontmatter
- **`references/`** - Detailed skill files
- **`scripts/`** - Optional automation scripts

## Available Skills

### Web Application (32 skills in 11 categories)
- A01: Broken Access Control (IDOR, CSRF, CORS)
- A03: Injection (SQL, NoSQL, Command, SSTI)
- A07: Auth Failures (JWT, OAuth, 2FA Bypass)
- [View all web skills](skills/web/SKILL.md)

### Network Services (66 skills in 14 categories)
- Databases (MySQL, PostgreSQL, Redis, MongoDB)
- Containers (Docker, Kubernetes)
- Industrial IoT (Modbus, BACnet, OPC-UA)
- [View all network skills](skills/network/SKILL.md)

## Usage

```python
from security_agent import Agent

agent = Agent(skills_path="/path/to/security_skills")
agent.run("Perform security assessment of 10.10.10.1")
```

## Disclaimer

⚠️ **These skills are for authorized security testing only.**



# Security Skills

A comprehensive collection of AI-powered penetration testing skills for security assessment frameworks.

## Overview

This repository contains structured skill files that enable AI agents to perform systematic security testing. Each skill provides methodology, tools, commands, and guidance for specific attack techniques and services.

## Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/security_skills.git
cd security_skills
```

### 2. Directory Structure

```
security_skills/
├── README.md              # This file
├── TODO.md                # Pending tasks and roadmap
└── skills/                # Security testing skills
    ├── README.md          # Skill catalog
    └── network/           # Network pentesting skills (48 skills)
        ├── network_scanning.md
        ├── arp_spoofing.md
        ├── mysql_pentesting.md
        └── ...
```

### 3. Using with AI Agents

Configure your AI agent to use this skills directory:

```python
from security_agent import Agent

agent = Agent(
    skills_path="/path/to/security_skills"
)

# The agent will automatically use relevant skills based on context
agent.run("Perform security assessment of 10.10.10.1")
```

## Available Skills

### Network Pentesting (48 skills)

| Category | Skills |
|----------|--------|
| Core Methodology | Network scanning, ARP spoofing, VLAN hopping, IPv6 attacks, WiFi, IDS evasion |
| Databases | MySQL, PostgreSQL, MSSQL, Oracle, MongoDB, Redis, Elasticsearch |
| Authentication | Kerberos, LDAP, RDP, VNC, WinRM |
| Infrastructure | DNS, SNMP, NTP, DHCP |
| Analysis | Banner grabbing, SSL/TLS analysis, CVE lookup, Attack surface assessment |
| Other | Docker, MQTT, Modbus, Java RMI, IPMI, VoIP |

See [skills/README.md](skills/README.md) for complete skill catalog.

## Skill Format

Each skill follows a consistent markdown structure:

```markdown
# [Service] Pentesting Skill

## Goal
Brief description of what this skill accomplishes.

## Methodology
Step-by-step testing process.

## Tools
* Relevant tools with descriptions

## Example Commands
Practical, copy-paste ready commands.

## Guidance for AI
When to activate, key considerations, best practices.
```

## Contributing

### Adding New Skills

1. Create a new `.md` file in the appropriate directory
2. Follow the established skill format
3. Include practical command examples
4. Add "Guidance for AI" section
5. Update the relevant README

### Skill Guidelines

- **Be practical**: Include real, tested commands
- **Be comprehensive**: Cover discovery through exploitation
- **Be safe**: Include warnings for dangerous operations
- **Be legal**: Emphasize authorization requirements

## Roadmap

See [TODO.md](TODO.md) for planned additions:
- Web application testing skills
- Mobile security testing skills
- Cloud security skills (AWS, Azure, GCP)
- Active Directory attack chains

## Disclaimer

⚠️ **These skills are for authorized security testing only.**

- Always obtain proper written authorization
- Never test systems you don't own or have permission to test
- Misuse of these techniques may be illegal
- The authors are not responsible for misuse

## License

MIT License - See [LICENSE](LICENSE) for details.

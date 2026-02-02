# HackTricks Skills for Antigravity

This directory contains comprehensive penetration testing skills derived from the [HackTricks](https://book.hacktricks.xyz/) knowledge base for the Antigravity AI security testing framework.

## Directory Structure

```
hacktricks/
├── network/      # Network pentesting skills (43 skills)
├── web/          # Web application testing (planned)
└── mobile/       # Mobile security testing (planned)
```

## Network Skills (43 Total)

### Core Network Methodology

| Skill | Description |
|-------|-------------|
| [network_scanning.md](network/network_scanning.md) | Nmap, masscan, network reconnaissance |
| [arp_spoofing.md](network/arp_spoofing.md) | ARP cache poisoning, MITM attacks |
| [dhcp_attacks.md](network/dhcp_attacks.md) | DHCP starvation, rogue DHCP server |
| [llmnr_nbt_ns_poisoning.md](network/llmnr_nbt_ns_poisoning.md) | Local network credential capture, relay attacks |
| [vlan_hopping.md](network/vlan_hopping.md) | VLAN segmentation bypass, DTP attacks |
| [ipv6_attacks.md](network/ipv6_attacks.md) | IPv6 exploitation, RA attacks, mitm6 |
| [ids_ips_evasion.md](network/ids_ips_evasion.md) | Bypassing intrusion detection systems |
| [wifi_pentesting.md](network/wifi_pentesting.md) | WPA/WPA2 cracking, evil twin attacks |
| [tunneling_port_forwarding.md](network/tunneling_port_forwarding.md) | SSH tunnels, chisel, ligolo-ng, pivoting |

### Authentication & Remote Access

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [ssh_pentesting.md](network/ssh_pentesting.md) | 22 | SSH security testing |
| [telnet_pentesting.md](network/telnet_pentesting.md) | 23 | Telnet exploitation |
| [kerberos_pentesting.md](network/kerberos_pentesting.md) | 88 | AS-REP roasting, Kerberoasting, tickets |
| [ldap_pentesting.md](network/ldap_pentesting.md) | 389, 636 | LDAP/AD enumeration |
| [rdp_pentesting.md](network/rdp_pentesting.md) | 3389 | RDP attacks, BlueKeep |
| [vnc_pentesting.md](network/vnc_pentesting.md) | 5900+ | VNC authentication bypass |
| [winrm_pentesting.md](network/winrm_pentesting.md) | 5985, 5986 | Evil-WinRM, lateral movement |

### File Transfer & Sharing

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [ftp_pentesting.md](network/ftp_pentesting.md) | 21 | FTP security testing |
| [tftp_pentesting.md](network/tftp_pentesting.md) | 69 | TFTP file extraction |
| [nfs_pentesting.md](network/nfs_pentesting.md) | 2049 | NFS share exploitation |
| [smb_pentesting.md](network/smb_pentesting.md) | 445, 139 | SMB enumeration |
| [rsync_pentesting.md](network/rsync_pentesting.md) | 873 | Rsync access |

### Database Services

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [mysql_pentesting.md](network/mysql_pentesting.md) | 3306 | MySQL exploitation, UDF |
| [postgresql_pentesting.md](network/postgresql_pentesting.md) | 5432 | PostgreSQL RCE |
| [mssql_pentesting.md](network/mssql_pentesting.md) | 1433 | xp_cmdshell, linked servers |
| [oracle_pentesting.md](network/oracle_pentesting.md) | 1521 | SID enum, TNS attacks |
| [mongodb_pentesting.md](network/mongodb_pentesting.md) | 27017 | NoSQL injection |
| [redis_pentesting.md](network/redis_pentesting.md) | 6379 | Redis RCE |
| [couchdb_pentesting.md](network/couchdb_pentesting.md) | 5984 | CouchDB CVE chain |
| [elasticsearch_pentesting.md](network/elasticsearch_pentesting.md) | 9200 | Data extraction, RCE |
| [memcached_pentesting.md](network/memcached_pentesting.md) | 11211 | Cache data extraction |

### Network Infrastructure

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [dns_pentesting.md](network/dns_pentesting.md) | 53 | Zone transfer, subdomain enum |
| [snmp_pentesting.md](network/snmp_pentesting.md) | 161, 162 | SNMP enumeration |
| [ntp_pentesting.md](network/ntp_pentesting.md) | 123 | Monlist amplification |

### Email Services

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [smtp_pentesting.md](network/smtp_pentesting.md) | 25, 465, 587 | User enum, open relay |

### VPN & Tunneling

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [ipsec_ike_pentesting.md](network/ipsec_ike_pentesting.md) | 500, 4500 | IKE PSK cracking |

### Container & Cloud

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [docker_pentesting.md](network/docker_pentesting.md) | 2375, 2376 | Docker API, container escape |

### Message Queues & IoT

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [mqtt_pentesting.md](network/mqtt_pentesting.md) | 1883 | IoT message interception |
| [modbus_pentesting.md](network/modbus_pentesting.md) | 502 | ICS/SCADA exploitation |

### Other Services

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [java_rmi_pentesting.md](network/java_rmi_pentesting.md) | 1099 | RMI deserialization |
| [x11_pentesting.md](network/x11_pentesting.md) | 6000+ | X11 screenshot/keylog |
| [sip_voip_pentesting.md](network/sip_voip_pentesting.md) | 5060 | VoIP interception |
| [ipmi_pentesting.md](network/ipmi_pentesting.md) | 623 | BMC hash disclosure |

## Skill Format

Each skill file follows a consistent markdown format:

```markdown
# [Service] Pentesting Skill

## Goal
Brief description of what this skill helps accomplish.

## Methodology
1. Step-by-step methodology
2. Attack flow

## Tools
* List of relevant tools

## Example Commands
```bash
# Practical command examples
```

## Guidance for AI
* When to activate this skill
* Key considerations
* Best practices
```

## Usage with Antigravity

These skills are designed to be used by AI agents within the Antigravity framework. When a user requests network security testing, the AI will:

1. Select relevant skills based on the target
2. Follow the methodology in each skill
3. Execute commands in the appropriate environment
4. Document findings

## References

- [HackTricks](https://book.hacktricks.xyz/)
- [HackTricks GitHub](https://github.com/HackTricks-wiki/hacktricks)
- [Antigravity Framework](../)

## Contributing

To add new skills:
1. Follow the established skill format
2. Include practical examples and commands
3. Add "Guidance for AI" section
4. Update this README

## Disclaimer

These skills are for authorized security testing only. Always obtain proper authorization before testing any systems. Misuse of these techniques may be illegal.

# Network Security Skills

This directory contains comprehensive network penetration testing skills for AI-powered security assessment.

## Skills Catalog (48 Total)

### Core Network Methodology (13 skills)

| Skill | Description |
|-------|-------------|
| [network_scanning.md](network/network_scanning.md) | Nmap, masscan, network reconnaissance |
| [arp_spoofing.md](network/arp_spoofing.md) | ARP cache poisoning, MITM attacks |
| [dhcp_attacks.md](network/dhcp_attacks.md) | DHCP starvation, rogue DHCP server |
| [llmnr_nbt_ns_poisoning.md](network/llmnr_nbt_ns_poisoning.md) | Local network credential capture |
| [vlan_hopping.md](network/vlan_hopping.md) | VLAN segmentation bypass, DTP attacks |
| [ipv6_attacks.md](network/ipv6_attacks.md) | IPv6 exploitation, RA attacks, mitm6 |
| [ids_ips_evasion.md](network/ids_ips_evasion.md) | Bypassing intrusion detection systems |
| [wifi_pentesting.md](network/wifi_pentesting.md) | WPA/WPA2 cracking, evil twin attacks |
| [tunneling_port_forwarding.md](network/tunneling_port_forwarding.md) | SSH tunnels, chisel, ligolo-ng |
| [banner_grabbing.md](network/banner_grabbing.md) | Service version identification |
| [ssl_tls_analysis.md](network/ssl_tls_analysis.md) | TLS/cipher/certificate analysis |
| [plaintext_protocol_detection.md](network/plaintext_protocol_detection.md) | Unencrypted service detection |
| [attack_surface_assessment.md](network/attack_surface_assessment.md) | Service exposure evaluation |

### CVE & Vulnerability Lookup (1 skill)

| Skill | Description |
|-------|-------------|
| [cve_lookup.md](network/cve_lookup.md) | CVE database queries using CIRCL and NVD APIs |

### Authentication & Remote Access (6 skills)

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [ssh_pentesting.md](network/ssh_pentesting.md) | 22 | SSH security testing |
| [telnet_pentesting.md](network/telnet_pentesting.md) | 23 | Telnet exploitation |
| [kerberos_pentesting.md](network/kerberos_pentesting.md) | 88 | AS-REP roasting, Kerberoasting |
| [ldap_pentesting.md](network/ldap_pentesting.md) | 389, 636 | LDAP/AD enumeration |
| [rdp_pentesting.md](network/rdp_pentesting.md) | 3389 | RDP attacks, BlueKeep |
| [vnc_pentesting.md](network/vnc_pentesting.md) | 5900+ | VNC authentication bypass |
| [winrm_pentesting.md](network/winrm_pentesting.md) | 5985, 5986 | Evil-WinRM, lateral movement |

### File Transfer & Sharing (5 skills)

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [ftp_pentesting.md](network/ftp_pentesting.md) | 21 | FTP security testing |
| [tftp_pentesting.md](network/tftp_pentesting.md) | 69 | TFTP file extraction |
| [nfs_pentesting.md](network/nfs_pentesting.md) | 2049 | NFS share exploitation |
| [smb_pentesting.md](network/smb_pentesting.md) | 445, 139 | SMB enumeration |
| [rsync_pentesting.md](network/rsync_pentesting.md) | 873 | Rsync access |

### Database Services (9 skills)

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

### Network Infrastructure (3 skills)

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [dns_pentesting.md](network/dns_pentesting.md) | 53 | Zone transfer, subdomain enum |
| [snmp_pentesting.md](network/snmp_pentesting.md) | 161, 162 | SNMP enumeration |
| [ntp_pentesting.md](network/ntp_pentesting.md) | 123 | Monlist amplification |

### Email Services (1 skill)

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [smtp_pentesting.md](network/smtp_pentesting.md) | 25, 465, 587 | User enum, open relay |

### VPN & Tunneling (1 skill)

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [ipsec_ike_pentesting.md](network/ipsec_ike_pentesting.md) | 500, 4500 | IKE PSK cracking |

### Container & Cloud (1 skill)

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [docker_pentesting.md](network/docker_pentesting.md) | 2375, 2376 | Docker API, container escape |

### Message Queues & IoT (2 skills)

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [mqtt_pentesting.md](network/mqtt_pentesting.md) | 1883 | IoT message interception |
| [modbus_pentesting.md](network/modbus_pentesting.md) | 502 | ICS/SCADA exploitation |

### Other Services (4 skills)

| Skill | Port(s) | Description |
|-------|---------|-------------|
| [java_rmi_pentesting.md](network/java_rmi_pentesting.md) | 1099 | RMI deserialization |
| [x11_pentesting.md](network/x11_pentesting.md) | 6000+ | X11 screenshot/keylog |
| [sip_voip_pentesting.md](network/sip_voip_pentesting.md) | 5060 | VoIP interception |
| [ipmi_pentesting.md](network/ipmi_pentesting.md) | 623 | BMC hash disclosure |

## Skill Format

Each skill follows a consistent structure:
- **Goal**: What the skill accomplishes
- **Methodology**: Step-by-step testing process
- **Tools**: Relevant tools with descriptions
- **Example Commands**: Practical commands
- **Guidance for AI**: When and how to use the skill

## Usage

These skills are designed for AI agents to:
1. Select relevant skills based on target
2. Follow methodology in each skill
3. Execute commands appropriately
4. Document findings

## Disclaimer

These skills are for authorized security testing only. Always obtain proper authorization.

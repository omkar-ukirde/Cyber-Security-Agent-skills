# TODO - Security Skills Roadmap

## ✅ Completed

### Skills Restructure (Agent Skills Standard)
- [x] Reorganized to follow [Agent Skills](https://agentskills.io) open standard
- [x] OWASP Top 10 2021 categorization for web skills
- [x] Created SKILL.md entrypoints with YAML frontmatter for all categories
- [x] Hyphenated lowercase folder naming convention

---

### Web Application Skills (32 skills in 11 categories)

#### A01 - Broken Access Control
- [x] idor.md
- [x] csrf.md
- [x] cors-bypass.md
- [x] open-redirect.md

#### A03 - Injection
- [x] sql-injection.md
- [x] nosql-injection.md
- [x] command-injection.md
- [x] ssti.md
- [x] ldap-injection.md
- [x] xpath-injection.md
- [x] orm-injection.md
- [x] crlf-injection.md

#### A04 - Insecure Design
- [x] race-condition.md
- [x] parameter-pollution.md

#### A05 - Security Misconfiguration
- [x] xxe.md
- [x] file-upload.md
- [x] subdomain-takeover.md
- [x] cache-deception.md

#### A06 - Vulnerable Components
- [x] deserialization.md

#### A07 - Auth Failures
- [x] jwt-attacks.md
- [x] oauth-attacks.md
- [x] session-attacks.md
- [x] 2fa-bypass.md
- [x] password-reset-attacks.md

#### A08 - Data Integrity Failures
- [x] http-request-smuggling.md

#### A10 - SSRF
- [x] ssrf.md
- [x] websocket-attacks.md

#### XSS
- [x] xss.md
- [x] clickjacking.md

#### API Security
- [x] graphql-attacks.md
- [x] api-testing.md

#### File Attacks
- [x] file-inclusion.md

---

### Network Skills (66 skills in 14 categories)

#### Reconnaissance (5)
- [x] network-scanning.md
- [x] nmap-scan.md
- [x] banner-grabbing.md
- [x] attack-surface-assessment.md
- [x] cve-lookup.md

#### Layer 2 Attacks (5)
- [x] arp-spoofing.md
- [x] dhcp-attacks.md
- [x] llmnr-nbt-ns-poisoning.md
- [x] vlan-hopping.md
- [x] ipv6-attacks.md

#### Auth Services (8)
- [x] ssh-pentesting.md
- [x] telnet-pentesting.md
- [x] kerberos-pentesting.md
- [x] ldap-pentesting.md
- [x] rdp-pentesting.md
- [x] vnc-pentesting.md
- [x] winrm-pentesting.md
- [x] rlogin-rsh-rexec-pentesting.md

#### File Services (7)
- [x] ftp-pentesting.md
- [x] tftp-pentesting.md
- [x] nfs-pentesting.md
- [x] smb-pentesting.md
- [x] rsync-pentesting.md
- [x] afp-pentesting.md
- [x] svn-pentesting.md

#### Databases (11)
- [x] mysql-pentesting.md
- [x] postgresql-pentesting.md
- [x] mssql-pentesting.md
- [x] oracle-pentesting.md
- [x] mongodb-pentesting.md
- [x] redis-pentesting.md
- [x] couchdb-pentesting.md
- [x] elasticsearch-pentesting.md
- [x] memcached-pentesting.md
- [x] cassandra-pentesting.md
- [x] influxdb-pentesting.md

#### Email (3)
- [x] smtp-pentesting.md
- [x] pop3-pentesting.md
- [x] imap-pentesting.md

#### Infrastructure (6)
- [x] dns-pentesting.md
- [x] snmp-pentesting.md
- [x] ntp-pentesting.md
- [x] rpcbind-pentesting.md
- [x] netbios-pentesting.md
- [x] msrpc-pentesting.md

#### Containers (3)
- [x] docker-pentesting.md
- [x] docker-registry-pentesting.md
- [x] kubernetes-pentesting.md

#### Message Queues (3)
- [x] mqtt-pentesting.md
- [x] amqp-rabbitmq-pentesting.md
- [x] kafka-pentesting.md

#### Industrial IoT (4)
- [x] modbus-pentesting.md
- [x] bacnet-pentesting.md
- [x] ethernetip-pentesting.md
- [x] opcua-pentesting.md

#### VPN/Tunneling (2)
- [x] ipsec-ike-pentesting.md
- [x] tunneling-port-forwarding.md

#### Security Analysis (3)
- [x] ssl-tls-analysis.md
- [x] plaintext-protocol-detection.md
- [x] ids-ips-evasion.md

#### Wireless (1)
- [x] wifi-pentesting.md

#### Other Services (5)
- [x] java-rmi-pentesting.md
- [x] x11-pentesting.md
- [x] sip-voip-pentesting.md
- [x] ipmi-pentesting.md
- [x] omi-pentesting.md

---

## 🔮 Future Enhancements

### Mobile Security
- [ ] Android APK analysis
- [ ] iOS IPA analysis
- [ ] SSL pinning bypass

### Cloud Security
- [ ] AWS S3/IAM attacks
- [ ] Azure Blob/AD attacks
- [ ] GCP exploitation

### Active Directory
- [ ] AD enumeration
- [ ] Privilege escalation paths
- [ ] Lateral movement

---

**Total: 98 skills completed + 2 mobile skills**

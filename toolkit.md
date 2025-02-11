# Cybersecurity Toolkit

Below is a concise overview of both **Offensive (Red)** and **Defensive (Blue)** cybersecurity tools.  
Tools are color-coded by cost:

- **Green (🟢)**: Free / Open-Source  
- **Purple (🟣)**: Paid / Commercial  

---

## Offensive Arsenal (🔴)

### Initial Access

1. **[Metasploit](https://www.offsec.com/metasploit-unleashed/introduction/)**  
   - **Cost**: 🟢 Free (Community), 🟣 Pro (Paid)  
   - **Use**: Exploiting vulnerabilities & delivering payloads  

2. **[Cobalt Strike](https://www.cobaltstrike.com/)**  
   - **Cost**: 🟣 Paid  
   - **Use**: Post-exploitation, advanced adversary simulation  

3. **[SET - Social Engineering Toolkit](https://github.com/trustedsec/social-engineer-toolkit)**  
   - **Cost**: 🟢 Free  
   - **Use**: Phishing and other social engineering attacks  

### Credential Access

1. **[John the Ripper](https://www.openwall.com/john/)**  
   - **Cost**: 🟢 Free version, 🟣 Pro ($185)  
   - **Use**: Password cracking  

2. **[Mimikatz](https://www.wallarm.com/what/what-is-mimikatz)**  
   - **Cost**: 🟢 Free  
   - **Use**: Credential extraction from memory  

3. **[Hashcat](https://www.hypr.com/security-encyclopedia/hashcat)**  
   - **Cost**: 🟢 Free  
   - **Use**: Advanced password cracking (dictionary, brute force)  

### Exfiltration

1. **[Netcat](https://www.kali.org/tools/netcat/)**  
   - **Cost**: 🟢 Free  
   - **Use**: Reading/writing data across network connections  

2. **[DNSExfiltrator](https://github.com/Arno0x/DNSExfiltrator)**  
   - **Cost**: 🟢 Free  
   - **Use**: Tunneling data over DNS  

3. **[icmpsh](https://github.com/bdamele/icmpsh)**  
   - **Cost**: 🟢 Free  
   - **Use**: Covert data exfiltration via ICMP  

### Command & Control (C2)

1. **[PowerShell Empire](https://github.com/EmpireProject/Empire)**  
   - **Cost**: 🟢 Free  
   - **Use**: Post-exploitation, C2 framework (Windows/PowerShell)  

2. **[Covenant](https://github.com/cobbr/Covenant)**  
   - **Cost**: 🟢 Free  
   - **Use**: .NET-based C2 framework for red team ops  

3. **[Sliver](https://bishopfox.com/tools/sliver)**  
   - **Cost**: 🟢 Free  
   - **Use**: Open-source C2 (alternative to Cobalt Strike)  

### Data Collection

1. **[Wireshark](https://www.wireshark.org/)**  
   - **Cost**: 🟢 Free  
   - **Use**: Packet capture & network traffic analysis  

2. **[Logkeys](https://github.com/kernc/logkeys)**  
   - **Cost**: 🟢 Free  
   - **Use**: Keylogging / keystroke capture  

3. **[BloodHound](https://github.com/BloodHoundAD/BloodHound)**  
   - **Cost**: 🟢 Free  
   - **Use**: Active Directory relationship mapping & attack path detection  

---

## Defensive Arsenal (🔵)

### Identify

1. **[Tenable.io](https://www.tenable.com/products/vulnerability-management)**  
   - **Cost**: 🟣 $$ ($4K+)  
   - **Use**: Continuous vulnerability management & asset discovery  

2. **[InsightVM](https://www.rapid7.com/products/insightvm/)**  
   - **Cost**: 🟣 Varies by asset count  
   - **Use**: Real-time vulnerability assessment & prioritization  

3. **[Entra ID (Azure AD)](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-id)**  
   - **Cost**: 🟣 $6–$9 per user/month  
   - **Use**: Identity & access management (cloud & on-prem)  

### Protect

1. **NGFW (Fortinet, Palo Alto, Sophos)**  
   - **Cost**: 🟣 $$–$$$  
   - **Use**: Network firewall & threat prevention  

2. **[CrowdStrike Falcon](https://www.crowdstrike.com/platform/?srsltid=AfmBOop3sGFstORxNl5s8JmJgc2rcq3VxWAEsZHj2Gti-Chft9tGUdeJ)**  
   - **Cost**: 🟣 $$$  
   - **Use**: Endpoint protection platform (EPP) & EDR  

### Detect

1. **[Snort IDS](https://www.snort.org/)**  
   - **Cost**: 🟢 Free or low-cost subscription  
   - **Use**: Network intrusion detection  

2. **[Splunk Enterprise Security](https://www.splunk.com/)**  
   - **Cost**: 🟣 $$$ (ingestion-based)  
   - **Use**: SIEM for real-time security monitoring  

3. **[Burp Suite](https://www.kali.org/tools/burpsuite/)**  
   - **Cost**: 🟢 Community, 🟣 Pro ($499)  
   - **Use**: Web application security (scanning & testing)  

### Respond

1. **[TheHive](https://strangebee.com/)**  
   - **Cost**: 🟢 Free (Community), 🟣 Paid tiers  
   - **Use**: Incident response platform for case management  

2. **[Cortex XSOAR (Demisto)](https://www.paloaltonetworks.com/cortex/cortex-xsoar)**  
   - **Cost**: 🟣 $$$ (~$22.5K+)  
   - **Use**: SOAR platform for automated incident response  

3. **[ServiceNow Security Incident Response](https://www.servicenow.com/products/security-incident-response.html)**  
   - **Cost**: 🟣 $$$ ($21K+/month)  
   - **Use**: Large-scale enterprise incident management & response  

### Recover

1. **[Veeam Backup & Replication](https://www.veeam.com/products/veeam-data-platform/backup-recovery.html)**  
   - **Cost**: 🟣 $ (monthly subscription)  
   - **Use**: Backup & disaster recovery (virtual, physical, cloud)  

2. **[Acronis Cyber Backup](https://www.acronis.com/en-us/)**  
   - **Cost**: 🟣 ~$68/year (discounted)  
   - **Use**: Data protection & recovery for varied workloads  

3. **[Commvault](https://www.commvault.com/)**  
   - **Cost**: 🟣 $$$ ($3K+/month)  
   - **Use**: Enterprise-level data management & disaster recovery  

---

## Key Takeaways

- **Cost Variation**:  
  - Offensive tools frequently open-source (🟢), accessible for ethical hacking.  
  - Defensive enterprise solutions (🟣) can be expensive, especially for large-scale deployments.

- **Offensive Focus**:  
  - Tools like Metasploit and Mimikatz specialize in exploitation, credential harvesting, etc.

- **Defensive Focus**:  
  - Solutions like Snort, Splunk, and TheHive emphasize monitoring, detection, and incident response.

- **Overlap**:  
  - Some tools (e.g., Wireshark, Burp Suite) serve both offensive (vulnerability testing) and defensive (traffic analysis).

- **Affordability**:  
  - Smaller organizations can start with free solutions (Snort, Wireshark, Metasploit).  
  - Larger enterprises often opt for comprehensive (and costly) suites like Splunk or ServiceNow.

---

Good—network admin projects are actually some of the most valuable portfolio assets for UK infrastructure / SOC / NOC roles because they map directly to real enterprise operations (monitoring, troubleshooting, uptime, security, and automation).

Below is a **structured set of 10–15 Network Administrator automation projects** using **PowerShell + Python**, designed as a coherent portfolio (not random scripts).

---

# 🧠 Network Admin Automation Portfolio (10–15 Projects)

## Project 1 — Network Health Monitoring System (Core Project)

### Tech: Python + PowerShell

### What it does:

Continuously monitors network devices and services.

### Monitors:

* Ping (latency + packet loss)
* DNS resolution
* Gateway availability
* Internet uptime
* Device reachability (servers, printers, switches)

### Output:

* Real-time console dashboard
* HTML report
* Alert log

### Example output:

```text
DC01     ✓ Online     2ms
Firewall ✗ Down       Timeout
Switch1  ✓ Online     1ms
Printer  ✓ Online     3ms
```

---

## Project 2 — Subnet Scanner & IP Discovery Tool

### Tech: Python

### Features:

* Scan entire subnet (e.g. 192.168.1.0/24)
* Detect live hosts
* Resolve hostnames
* Identify MAC addresses
* Export to CSV

### Skills:

* ARP scanning
* ICMP requests
* Network enumeration

---

## Project 3 — Port Scanner for Internal Network

### Tech: Python

### Features:

* Scan open ports (1–1000 or custom range)
* Identify services (HTTP, SSH, RDP, SMB)
* Detect risky ports:

  * Telnet (23)
  * FTP (21)
  * SMBv1 (445)

### Output:

Security risk report

---

## Project 4 — DNS Monitoring & Troubleshooting Tool

### Tech: PowerShell

### Features:

* Check DNS resolution speed
* Compare multiple DNS servers:

  * 8.8.8.8
  * 1.1.1.1
  * Internal DNS
* Detect DNS failure or slow responses

---

## Project 5 — Network Latency Analyzer

### Tech: PowerShell

### Features:

* Continuous ping test
* Jitter calculation
* Packet loss percentage
* Route tracing (tracert automation)

### Output:

* Graph (CSV → Excel)
* Network stability report

---

## Project 6 — Firewall Rule Auditor

### Tech: PowerShell

### Features:

* Export Windows Firewall rules
* Detect:

  * Any-any rules
  * Open inbound ports
  * Disabled rules
* Highlight risky configurations

### Output:

HTML security report

---

## Project 7 — Active Directory Network Device Tracker

### Tech: PowerShell + AD

### Features:

* Track domain-joined devices
* Detect inactive machines
* Last logon time
* IP address mapping

---

## Project 8 — Bandwidth Usage Monitor

### Tech: Python

### Features:

* Monitor network adapter usage
* Track upload/download speed
* Identify bandwidth spikes
* Log per hour usage

### Output:

Graph + CSV

---

## Project 9 — DHCP Lease Analyzer

### Tech: PowerShell

### Features:

* Export DHCP leases
* Detect:

  * Expired leases
  * Duplicate IPs
  * Rogue devices
* Identify unused IPs

---

## Project 10 — VPN Connection Monitor

### Tech: PowerShell

### Features:

* Track VPN status
* Monitor connection drops
* Log session duration
* Auto-reconnect alert simulation

---

## Project 11 — Network Device Inventory System

### Tech: Python + SQL

### Tracks:

* Routers
* Switches
* Firewalls
* Access points
* Servers

### Fields:

* IP address
* MAC address
* Location
* Device type
* OS version
* Last seen

---

## Project 12 — Log Analyzer (Network Logs)

### Tech: Python

### Parses:

* Firewall logs
* VPN logs
* Router logs
* Windows event logs

### Detects:

* Failed logins
* Port scans
* Suspicious IPs
* Brute force attempts

---

## Project 13 — SNMP Device Monitor

### Tech: Python

### Features:

* Query SNMP devices
* Get:

  * CPU usage
  * Memory usage
  * Interface status
* Alerts if threshold exceeded

---

## Project 14 — Network Change Detection Tool

### Tech: PowerShell

### Features:

* Detect changes in:

  * IP addresses
  * DNS settings
  * Gateway changes
  * NIC configuration
* Logs before/after snapshots

---

## Project 15 — IT Network Admin Dashboard (Flagship)

### Tech: Python (Flask or FastAPI)

### Web Dashboard:

```text
NETWORK STATUS DASHBOARD
---------------------------------

✔ Servers Online: 24
✔ Devices Online: 128
✖ Devices Down: 3
⚠ Security Risks: 5

[ View Devices ]
[ View Alerts ]
[ View Logs ]
[ Run Scan ]
```

### Features:

* Live monitoring
* Device inventory
* Alerts system
* Network map view (optional)
* Admin controls

---

# 🧱 How to Structure Your Portfolio

Instead of separate random scripts:

```text
Network-Automation-Lab/
│
├── Monitoring/
├── Scanning/
├── Security/
├── Inventory/
├── Logs/
├── Dashboard/
├── Reports/
└── Tools/
```

Each project becomes a module.

---

# 🚀 Best 5 to build first (high impact for jobs)

If your goal is UK jobs (Network Engineer / SOC / NOC / IT Infrastructure):

### 1. Network Health Monitoring System ⭐

(Shows real-time infrastructure monitoring)

### 2. Subnet Scanner + IP Discovery ⭐

(Shows core networking fundamentals)

### 3. Port Scanner + Security Report ⭐

(Direct cybersecurity relevance)

### 4. DHCP + DNS Analyzer ⭐

(Real enterprise troubleshooting)

### 5. Network Dashboard (Python Web App) ⭐

(Portfolio centerpiece)

---

# 💼 Why these projects matter to employers

These projects prove you can:

* Troubleshoot real networks
* Understand TCP/IP deeply
* Automate repetitive admin tasks
* Detect security issues
* Work with enterprise infrastructure tools
* Build monitoring systems like real NOC engineers

---

# If you want next step

I can build the **first full working project for you (Network Health Monitoring System)** including:

* Complete Python script
* PowerShell version
* Dashboard output
* Logging system
* GitHub README
* Setup guide

Just tell me:

> “create project 1 full code”

and I’ll turn it into a production-style repository.

# DNS Enumeration Lab

## Objective

Learn how to enumerate DNS services running on a target system using Nmap.

---

## Target

Metasploitable 2

IP Address: 192.168.1.15

---

## Commands

```bash
nmap -sV -p 53 192.168.1.15

nmap -sV --script=dns-service-discovery -p 53 192.168.1.15

nmap -A -p 53 192.168.1.15

nmap -sU -p 53 192.168.1.15

nmap -sV -sU -p 53 192.168.1.15
```

---

## Findings

- Detected DNS service on port 53.
- Identified DNS server version (if available).
- Verified UDP DNS service accessibility.
- Gathered service information using Nmap scripts.
- Confirmed DNS is running on the target.

---

## Learning

- Learned DNS service enumeration.
- Performed TCP and UDP DNS scans.
- Used Nmap NSE scripts for DNS discovery.
- Practiced version detection and service identification.

---

## Screenshots

See the screenshots folder for command outputs.

# SMTP Enumeration Lab

## Objective

Learn how to enumerate an SMTP (Simple Mail Transfer Protocol) service using Nmap.

---

## Target

Metasploitable 2

IP Address: 192.168.1.15

---

## Commands

```bash
nmap -sV -p 25 192.168.1.15

nmap -sV --script smtp-commands -p 25 192.168.1.15

nmap --script smtp-enum-users -p 25 192.168.1.15

nmap --script smtp-commands -p 25 192.168.1.15

nmap -A -p 25 192.168.1.15
```

---

## Findings

- SMTP service detected on port 25.
- Identified SMTP server version.
- Enumerated supported SMTP commands.
- Attempted SMTP user enumeration.
- Gathered additional service information using Nmap.

---

## Learning

- Learned SMTP service enumeration.
- Used Nmap NSE scripts for SMTP.
- Identified SMTP capabilities and server information.

---

## Screenshots

See the screenshots included in this folder.

# MySQL Enumeration Lab

## Objective

Learn how to enumerate a MySQL service using Nmap and identify the database service running on the target system.

---

## Target

Metasploitable 2

IP Address: 192.168.1.15

---

## Commands

```bash
nmap -sV -p 3306 192.168.1.15

nmap -sV --script=mysql-info -p 3306 192.168.1.15

nmap --script=mysql-info -p 3306 192.168.1.15

nmap -A -p 3306 192.168.1.15

nmap -sU -p 3306 192.168.1.15
```

---

## Findings

- Detected MySQL service on port 3306.
- Identified the MySQL server version (if available).
- Gathered MySQL service information using the `mysql-info` NSE script.
- Performed comprehensive service detection.
- Checked UDP accessibility on port 3306.

---

## Learning

- Learned MySQL service enumeration using Nmap.
- Used the `mysql-info` NSE script.
- Identified service details and version information.
- Practiced database service reconnaissance.

---

## Screenshots

See the screenshots included in this folder.

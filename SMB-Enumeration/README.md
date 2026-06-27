# SMB Enumeration Lab

## Objective

Learn how to enumerate SMB services running on Metasploitable 2 using Nmap.

## Target

- Machine: Metasploitable 2
- IP Address: 192.168.1.15

## Commands Used

```bash
nmap -sV -p 139,445 192.168.1.15

nmap --script smb-os-discovery -p 139,445 192.168.1.15

nmap --script smb-protocols -p 139,445 192.168.1.15

nmap --script smb-security-mode -p 139,445 192.168.1.15

nmap --script smb-enum-shares -p 139,445 192.168.1.15
```

## Findings

- SMB service detected.
- Operating system identified.
- SMB protocol versions enumerated.
- Security mode identified.
- Shared folders enumerated.

## Learning Outcomes

- Learned SMB service enumeration.
- Learned SMB NSE scripts.
- Learned SMB share discovery.
- Learned SMB security assessment.

## Screenshots

See the screenshots folder for command outputs.

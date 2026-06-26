
# FTP Enumeration Lab

## Objective

Learn how to enumerate an FTP service and test anonymous login.

## Target

- **Target Machine:** Metasploitable 2
- **IP Address:** 192.168.1.15

## Commands Used

```bash
nmap -sV -p 21 192.168.1.15

ftp 192.168.1.15

# Username: anonymous
# Password: anonymous

pwd
ls
dir
help
status
binary
ascii
bye

nmap --script ftp-anon 192.168.1.15
```

## Findings

- FTP service detected on port 21
- Service version: vsFTPd 2.3.4
- Anonymous FTP login is enabled
- Successfully connected using anonymous credentials
- The FTP root directory contained no files
- FTP enumeration completed successfully

## Learning Outcomes

- Learned FTP enumeration techniques
- Tested anonymous FTP authentication
- Practiced common FTP client commands
- Used the Nmap NSE `ftp-anon` script

## Screenshots

See the **screenshots** folder for the lab images.

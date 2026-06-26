# Nmap - Basic Scan Lab

## Objective

Learn the basics of Nmap by scanning the local machine and understanding the results.

## Environment

- Operating System: Kali Linux
- Virtual Machine: VirtualBox
- Scanner: Nmap 7.98

## Commands Used

```bash
nmap localhost
nmap -sV localhost
nmap -O localhost
```

## Results

- Successfully scanned localhost.
- No open TCP ports were detected.
- Service detection completed successfully.
- OS detection was attempted, but Nmap could not determine the OS because there were not enough open ports.

## What I Learned

- How to perform a basic Nmap scan.
- How to detect services using `-sV`.
- How OS detection works with `-O`.
- Why OS detection may not always succeed.

## Conclusion

This lab introduced the basic functionality of Nmap and demonstrated how to perform reconnaissance against a host.

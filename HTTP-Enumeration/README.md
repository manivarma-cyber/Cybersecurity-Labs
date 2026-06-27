# HTTP Enumeration Lab

## Objective

Learn how to enumerate an HTTP service using Nmap and inspect a web server hosted on Metasploitable 2.

## Target

- Machine: Metasploitable 2
- IP Address: 192.168.1.15

## Commands Used

```bash
nmap -sV -p 80 192.168.1.15

nmap --script http-title -p 80 192.168.1.15

nmap --script http-headers -p 80 192.168.1.15

nmap --script http-methods -p 80 192.168.1.15

nmap -sC -p 80 192.168.1.15
```

## Findings

- HTTP service detected on port 80.
- Apache web server identified.
- HTTP page title enumerated.
- HTTP response headers collected.
- Supported HTTP methods identified.
- Default HTTP NSE scripts executed successfully.

## Learning Outcomes

- Learned HTTP service enumeration.
- Learned how to identify web server versions.
- Learned how to enumerate HTTP headers.
- Learned how to enumerate supported HTTP methods.
- Learned how to use Nmap HTTP NSE scripts.

## Screenshots

See the screenshots folder for all command outputs and the web page.

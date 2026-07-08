# Service Enumeration Lab

## Objective

Identify running services on a local machine using Nmap service detection.

## Tool Used

- Nmap (Kali Linux)
- Python HTTP Server

## Lab Setup

A simple Python web server was started on port 8080 using:

python3 -m http.server 8080

## Scan Command Used

nmap -sV localhost

## Results

Starting Nmap 7.98 ( https://nmap.org ) at 2026-07-08 07:59 -0400

Nmap scan report for localhost (127.0.0.1)

Host is up (0.0000080s latency).

Other addresses for localhost (not scanned): ::1

Not shown: 999 closed tcp ports (reset)

PORT     STATE SERVICE VERSION

8080/tcp open  http    SimpleHTTPServer 0.6 (Python 3.13.12)

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .

Nmap done: 1 IP address (1 host up) scanned in 6.60 seconds

## Findings

The scan identified an open TCP port 8080 running an HTTP service.

Nmap detected the service as Python SimpleHTTPServer version 0.6.

This shows how Nmap can be used to discover open ports and identify running services on a system.

## Skills Demonstrated

- Service enumeration
- Port scanning
- Nmap usage
- Linux command line
- Security reconnaissance

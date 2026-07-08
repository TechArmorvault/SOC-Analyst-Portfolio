# Local Network Scan Lab

## Objective
Perform a basic network scan using Nmap and understand discovered services.

## Tool Used
- Nmap (Kali Linux)

## Command Used

## Results
Starting Nmap 7.98 ( https://nmap.org ) at 2026-07-08 07:53 -0400
Nmap scan report for localhost (127.0.0.1)
Host is up (0.0000060s latency).
Other addresses for localhost (not scanned): ::1
All 1000 scanned ports on localhost (127.0.0.1) are in ignored states.
Not shown: 1000 closed tcp ports (reset)

Service detection performed. Please report any incorrect results at https://nmap.org/submit/ .
Nmap done: 1 IP address (1 host up) scanned in 0.34 seconds

## Findings

The Nmap scan confirmed that the localhost system (127.0.0.1) was reachable and active.

The scan checked the default 1000 TCP ports but found no open ports or running services. All scanned ports were closed, meaning there were no network services accepting connections on the local machine during the scan.

This demonstrates the use of Nmap for basic host discovery and service enumeration.

## Skills Demonstrated

- Network enumeration
- Port scanning
- Service identification
- Linux command line usage

```bash
nmap -sV localhost
## R

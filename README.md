# Network-scanning-for-open-ports
# Cyber Security Internship - Task 1

## Objective
Perform network reconnaissance using Nmap to find open ports and understand potential risks.

## Tools
- Nmap
- Wireshark (optional)

## Steps
1. Installed Nmap
2. Scanned local network: `nmap -sS 192.168.1.0/24`
3. Saved results in `scan_results.txt`
4. Analyzed open ports and their services

## Sample Findings
| IP Address | Open Port | Service | Risk |
|-------------|------------|----------|------|
| 192.168.1.1 | 80 | HTTP | Could expose router web interface |

## Outcome
Learned how to perform a basic port scan and analyze network exposure.

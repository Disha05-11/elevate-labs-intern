# Task 1 - Network Scan

## Objective
Scan local network for open ports using Nmap.

## Tool Used
- Nmap 7.99

## Command Used

```bash
nmap -sS 192.168.180.1

RESULT:-
| Port | Service        |
| ---- | -------------- |
| 135  | MSRPC          |
| 139  | NetBIOS-SSN    |
| 445  | Microsoft-DS   |
| 902  | ISS-Realsecure |
| 912  | Apex-Mesh      |


OUTPUT:-
Successfully identified open ports and understood network exposure.

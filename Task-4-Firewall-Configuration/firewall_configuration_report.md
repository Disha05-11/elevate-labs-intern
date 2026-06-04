# Firewall Configuration Report

## Objective
Configure and test a firewall rule using Windows Defender Firewall.

## Environment
Operating System: Windows 10/11

Firewall Tool: Windows Defender Firewall

## Steps Performed

### 1. Opened Windows Defender Firewall

Accessed Windows Defender Firewall with Advanced Security.

### 2. Viewed Existing Rules

Reviewed inbound and outbound firewall rules.

### 3. Created Block Rule

Configured a new inbound rule:

- Rule Type: Port
- Protocol: TCP
- Port Number: 23
- Action: Block the Connection

### 4. Verification

Verified that traffic directed to Port 23 would be blocked by the firewall.

### 5. Rule Removal

Removed the test rule after verification.

## Why Port 23 Was Blocked

Port 23 is used by Telnet.

Telnet transmits data in plain text and is considered insecure.

## Benefits of Firewall

- Blocks unauthorized access
- Filters network traffic
- Reduces attack surface
- Protects network services

## Conclusion

Successfully configured and reviewed firewall rules and gained understanding of network traffic filtering.

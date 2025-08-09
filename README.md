# Using-Firewall
# Task 4 - Setup and Use a Firewall (Windows/Linux)

## Objective
Configure and test basic firewall rules to allow or block traffic, demonstrating network traffic filtering skills.

## Steps Performed

### 1. List Current Firewall Rules
- **Windows:** Viewed in "Windows Defender Firewall with Advanced Security".
### 2. Block Inbound Traffic on Port 23 (Telnet)
Windows: Added inbound TCP rule for port 23 → Block connection.
### 3. Test the Rule
Tried connecting via Telnet:
#### *telnet localhost 23
Connection was blocked.
### 4. Remove Test Rule
Windows: Deleted the inbound port 23 rule.
### Screenshots
See /screenshots folder for:
- Before rules
- After block
- Connection test
- Rule removal

### Summary of Firewall Traffic Filtering
A firewall inspects network traffic based on defined rules, allowing or blocking connections by IP, port, or protocol. In this task, blocking port 23 prevented Telnet connections, demonstrating how specific ports can be secured against unauthorized access.

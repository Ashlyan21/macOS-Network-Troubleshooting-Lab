macOS Network Troubleshooting Lab
Project Overview
 - This project demonstrates basic network troubleshooting skills using the macOS Terminal. The objective is to understand IP addressing, network connectivity and DNS resolution.
Tools Used - macOS Terminal
Lab 1: Identifying the Local IP Address
  Command: ipconfig getifaddr en0
  Purpose: To identify the IPv4 address assigned to the Mac's network interface.
  Result: Successfully retrieved the local IP address
Lab 2: Testing Network Connectivity
  Command: ping -c 4 8.8.8.8
  Purpose: Test connectivity to a public DNS server using ICMP packets
  Result: Ping command executed with packet loss and response times recorded
Lab 3: Testing DNS Resolution
   Command: nslookup google.com
   Purpose: Verify that DNS can translate a domain name into an IP address.
   Result: Successfully resolved google.com to an IP address
Skills Demonstrated
  -macOS command line navigation
  - TCP/IP fundamentals
  - IP address identification
  - ICMP connectivity testing
  - DNS troubleshooting
  - Technical documentation
Lessons Learned
  The use of foundational network diagnostic commands to inspect local IP configuration, test connectivity to an external IP address, and verify DNS name resolution. 

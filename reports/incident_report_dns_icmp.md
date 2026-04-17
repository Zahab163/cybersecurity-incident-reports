# Cybersecurity Incident Report  
## Network Traffic Analysis – DNS/ICMP Case Study

### Part 1: Summary of the Problem
- The UDP protocol reveals that DNS queries to port 53 failed.
- ICMP error messages returned: "udp port 53 unreachable."
- Port 53 is used for DNS services.
- The DNS service was unavailable, preventing domain resolution.

### Part 2: Analysis of the Data
- Time incident occurred: 13:24:32
- Customers reported website inaccessible, error “destination port unreachable.”
- IT team used tcpdump to capture traffic.
- Findings: DNS queries failed, ICMP confirmed port 53 unreachable.
- Likely cause: DNS service down, blocked, or misconfigured.

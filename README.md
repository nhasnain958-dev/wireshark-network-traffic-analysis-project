# Wireshark Network Traffic Analysis

## Project Overview
This project demonstrates basic network traffic analysis using Wireshark. I captured network packets, identified common network protocols, applied display filters, and explored packet details.

## Objective
- Capture live network traffic.
- Identify common network protocols.
- Examine source and destination IP addresses.
- Apply Wireshark display filters.
- Understand basic packet analysis.

## Tools Used
- Wireshark
- Windows
- Command Prompt

## Protocols Analyzed
- **TCP:** Reliable data transmission.
- **UDP:** Connectionless data transmission.
- **DNS:** Resolves domain names to IP addresses.
- **ICMP:** Used for network diagnostics, including ping.
- **HTTP:** Web communication protocol.

## Display Filters Used

| Filter | Purpose |
|---|---|
| `tcp` | Display TCP packets |
| `udp` | Display UDP packets |
| `dns` | Display DNS traffic |
| `icmp` | Display ICMP packets |
| `http` | Display HTTP packets |

## Practical Screenshots

### 1. Network Packet Capture
![Network Packet Capture](01-packet-capture.png)

### 2. DNS Filter
![DNS Filter](02-dns-filter.png)

### 3. TCP Filter
![TCP Filter](03-tcp-filter.png)

### 4. UDP Filter
![UDP Filter](04-udp-filter.png)

### 5. ICMP Filter
![ICMP Filter](05-icmp-filter.png)

### 6. HTTP Filter
![HTTP Filter](06-http-filter.png)

### 7. Packet Details Analysis
![Packet Details](07-packet-details.png)

## Observations
- TCP and UDP packets were observed in the captured traffic.
- DNS traffic was examined using a display filter.
- ICMP packets were observed during ping testing.
- Source and destination IP addresses were examined.
- No HTTP packets appeared when the HTTP display filter was applied during this capture.

## Key Learnings
1. Learned how to capture network traffic using Wireshark.
2. Practiced identifying common network protocols.
3. Learned how to inspect source and destination IP addresses.
4. Applied display filters to analyze specific traffic.
5. Developed basic network packet analysis skills.

## Conclusion
This project provided practical experience in network traffic capture, protocol identification, display filtering, and packet inspection using Wireshark.

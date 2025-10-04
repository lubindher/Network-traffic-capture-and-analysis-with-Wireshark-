# Network-traffic-capture-and-analysis-with-Wireshark
## Lubindher S - 212222240056
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-10-04 132206" src="https://github.com/user-attachments/assets/932c6b5a-3e63-40df-807c-1c30be46cb1d" />

<img width="1920" height="1080" alt="Screenshot 2025-10-04 132247" src="https://github.com/user-attachments/assets/942bba31-d488-4c98-a091-ce22ddc4df08" />
<img width="1920" height="1080" alt="Screenshot 2025-10-04 132643" src="https://github.com/user-attachments/assets/1cdbd575-ba1f-44ef-bca0-bf5c2c9d161a" />

<img width="1920" height="1080" alt="Screenshot 2025-10-04 132743" src="https://github.com/user-attachments/assets/ba8756d5-e90b-442e-9eab-a69d31f67039" />
<img width="1920" height="1080" alt="Screenshot 2025-10-04 133023" src="https://github.com/user-attachments/assets/8ba65208-40d1-40f9-860c-de6cb1ab8d39" />

Captured Packets with Protocol Analysis and Detailed Packet Info

## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.

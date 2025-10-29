# Network-traffic-capture-and-analysis-with-Wireshark
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
Captured Packets with Protocol Analysis and Detailed Packet Info

<img width="1920" height="1080" alt="Screenshot 2025-10-12 172834" src="https://github.com/user-attachments/assets/8abcac2d-6012-4988-9170-f7e8884282e8" />

<img width="1920" height="1080" alt="Screenshot 2025-10-12 172943" src="https://github.com/user-attachments/assets/7d6689b3-5e6c-40c2-90d6-61f13df9b3f4" />

<img width="1920" height="1080" alt="Screenshot 2025-10-12 174242" src="https://github.com/user-attachments/assets/b2a3185f-129b-451b-aca7-86a1e44ec18b" />

<img width="1920" height="1080" alt="Screenshot 2025-10-12 174418" src="https://github.com/user-attachments/assets/7a8c4397-f343-4092-9ec5-1c0486108e5f" />

<img width="1920" height="1080" alt="Screenshot 2025-10-12 175253" src="https://github.com/user-attachments/assets/842de7d1-1f71-4f9c-b154-cdc9f4948f9c" />


<img width="1920" height="1080" alt="Screenshot 2025-10-12 175351" src="https://github.com/user-attachments/assets/bcf1f9b7-685d-40a6-8ef9-895278281d04" />









## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.

# ARP-Configuration
ARP in LAN (4 PCs) - CPT Sim
# Industrial Internet of Things (IIoT)
## Configuration of Address Resolution Protocol (ARP)

### Aim
To simulate and understand the working of the Address Resolution Protocol (ARP) within a LAN of four devices using Cisco Packet Tracer.

---

### Problem Statement
In a Local Area Network (LAN), devices communicate using IP addresses, but actual data transmission occurs via MAC addresses. The Address Resolution Protocol (ARP) bridges this gap by resolving IP addresses to MAC addresses. This project demonstrates the ARP process in a simple LAN environment using Cisco Packet Tracer with 4 PCs connected through a switch.

---

### Scope of the Solution
- Create a basic LAN consisting of 4 PCs connected to an 8-port switch.
- Configure each PC with a static IP in the same subnet.
- Use the `ping` command to initiate communication and trigger ARP.
- View the ARP table using `arp -a`.
- Use Simulation Mode to visualize ARP requests and replies.

---

### Overview / Architecture of the Solution
This simulation demonstrates ARP in action through a LAN topology where each PC is manually assigned an IP. The network is configured as follows:
PC0 (192.168.1.1) ───┐
PC1 (192.168.1.2) ──┼── Switch0 (8-Port)
PC2 (192.168.1.3) ──┤
PC3 (192.168.1.4) ───┘

Each device communicates over Ethernet using copper straight-through cables. When one PC sends a ping to another, the ARP protocol resolves the destination IP to its MAC address before transmission.

---

### Required Components

| Component               | Quantity | Description                          |
|-------------------------|----------|--------------------------------------|
| PCs                     | 4        | End devices                          |
| 8-Port Switch           | 1        | Layer 2 networking device            |
| Copper Straight Cables  | 4        | Used to connect each PC to the switch|
| Cisco Packet Tracer     | 1        | Simulation platform                  |

---

### Simulated Circuit
The complete logical layout is available in `screenshots/topology_4pcs.png`.

---

### Execution Video
A demonstration video is included in the `video/` folder.


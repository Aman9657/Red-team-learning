# What is Networking — Notes 

**Platform:** TryHackMe — Pre-Security Path  
**Room:** What is Networking  

## Summary
This room introduced the basic concepts of computer networking: how devices connect, how data is addressed and routed, and simple diagnostic techniques used to verify connectivity.

## Resources
- TryHackMe: What is Networking   
- Supporting video: "What is Networking? - Networking Basics" — https://youtu.be/42u_2e6eNF4?si=jJ0aoW6iRP2Zfl-Q

## Core concepts covered
- **Devices:** Hosts (clients), switches (layer-2), and routers (layer-3) and their roles in moving data.  
- **Addresses:** MAC (hardware) addresses operate at the link layer; IP addresses operate at the network layer and are used for routing between networks.  
- **Ports & services (intro):** Ports let a host run multiple services at once (e.g., web, SSH).  
- **How data moves:** Packets are forwarded by routers; switches forward frames based on MAC addresses on the local network.  
- **Basic troubleshooting:** Tools such as `ping` (ICMP) are used to check reachability and basic latency.

## Practical exposure (what I actually did)
- Used the lab-provided environment to **run basic connectivity checks** (ping) and observe responses.  
- Followed the guided exercise that demonstrated **changing the MAC address** within the lab to simulate how device identity can be altered for testing network access controls (guided, lab-only).  
- All practical actions were performed only in the TryHackMe lab environment and under the room’s instructions.

## Security relevance
- Understanding addressing and device roles is critical for both attackers and defenders: reconnaissance begins with discovering hosts and services.  
- MAC-address-based controls can be bypassed if an attacker spoofs an address; defenders should not rely on MAC filtering alone.  
- Ping and other diagnostics are commonly used in recon and troubleshooting; defenders monitor these patterns for anomalies.



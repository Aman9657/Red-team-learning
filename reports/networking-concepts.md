# Networking Concepts — Notes

**Platform:** TryHackMe (free room)  
**Room:** Networking Concepts

## Summary
This room covered core networking theory at a slightly deeper level than the introductory material. Topics included the OSI and TCP/IP models, IP addressing and subnets, transport protocols (TCP vs UDP), encapsulation, and a brief demonstration using Telnet.

## Key Concepts Learned
- **OSI vs TCP/IP models:** OSI is a 7-layer conceptual model useful for learning and troubleshooting; TCP/IP is the practical model used on the internet.  
- **IP addresses & subnets:** IPs identify hosts on networks; subnets segment networks and control routing. Understanding subnetting is important for mapping which hosts are reachable.  
- **TCP vs UDP:** TCP is connection-oriented and reliable (handshake, retransmission); UDP is connectionless and faster but unreliabile. Use cases differ by application needs.  
- **Encapsulation:** As data moves down the stack each layer wraps it with its own header; the reverse happens on receive. This explains why different tools operate at different layers.  
- **Telnet (demonstration):** The room used Telnet to show simple TCP connections for demonstration. I followed the guided steps but did not fully master all Telnet details yet.

## Practical exposure
- Followed guided practical steps in the lab to observe how packets/frames move and to try simple connectivity checks (Telnet demonstration).  
- Did not include screenshots in this report; I may re-run the lab later and add sanitized evidence if needed.

## Security relevance
- Layered models guide where to probe and where defenders should monitor (network versus application layer).  
- Misconfigured addressing or open services (TCP/UDP) increase attack surface.  
- Simple tools like Telnet illustrate how plain-text connections can expose information — defenders should prefer secure protocols.

## Key takeaway
This room strengthened the conceptual foundation for networking: models, addressing, transport behaviour, and encapsulation. These concepts are essential before moving to practical host discovery and service enumeration.

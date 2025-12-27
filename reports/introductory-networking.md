# Introductory Networking

## Overview
This report documents my learning from the **Introductory Networking** room on TryHackMe.  
This room was completed as a **free alternative** to the paid networking modules in the **TryHackMe Pre-Security path**.

The room introduced basic networking concepts, models, and commonly used networking tools at a beginner-friendly, surface level.

---

## Key Concepts Learned

### What is Networking
- Networking is the process of connecting devices so they can communicate with each other.
- Devices on a network exchange data using agreed rules called **protocols**.
- Networks can be small (local networks) or large (the internet).

---

### The OSI Model (Overview)
- The OSI model is a **conceptual model** used to understand how data travels across a network.
- It consists of **7 layers**, each with a specific responsibility.
- The OSI model helps with troubleshooting and understanding where problems occur.

---

### Encapsulation
- Encapsulation is the process of wrapping data with protocol information as it moves down the network layers.
- Each layer adds its own header before sending data.
- The receiving system removes these headers in reverse order.

---

### TCP/IP Model
- The TCP/IP model is a **practical networking model** used in real-world networking.
- It has fewer layers compared to the OSI model.
- TCP/IP focuses on how data is actually transmitted over networks and the internet.

---

## Networking Tools (Introductory Level)

### Ping
- `ping` is used to test connectivity between two systems.
- It checks whether a target host is reachable and measures response time.

---

### Traceroute
- `traceroute` shows the path data takes from the source to the destination.
- It helps identify where delays or failures occur in a network path.

---

### WHOIS
- WHOIS is used to retrieve information about a domain or IP address.
- It can show ownership details and registration information.

---

### Dig
- `dig` is a DNS lookup tool.
- It is used to query DNS servers and understand how domain names resolve to IP addresses.

---

## Practical Exposure
- Used basic networking tools such as **ping** and **traceroute**.
- Gained hands-on exposure to how connectivity and network paths are tested.
- Practiced simple command-line interaction with networking tools.

*(Screenshots and detailed practical evidence can be added later if labs are re-run.)*

---

## Key Takeaways
- Networking concepts are foundational for cybersecurity and ethical hacking.
- Understanding models like OSI and TCP/IP helps in troubleshooting and attack analysis.
- Simple tools like ping and traceroute are essential for initial network enumeration.

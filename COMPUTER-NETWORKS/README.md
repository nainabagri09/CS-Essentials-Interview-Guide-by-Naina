# 🌐 Computer Networks — Essential Interview Notes  

This document contains 20 frequently asked and beginner-friendly Computer Networks concepts explained in a simple way for interview revision.

---

## 1️⃣ Data Link Layer  
Ensures reliable communication between directly connected devices.  
Handles: framing, MAC addressing, error detection & correction.

---

## 2️⃣ Gateway vs Router  

| Feature | Gateway | Router |
|--------|---------|--------|
| Purpose | Connects different protocols | Connects similar networks |
| OSI Layer | Works on multiple layers | Layer 3 |
| Example | VoIP Gateway | Home router |

---

## 3️⃣ Ping Command  
`ping` sends **ICMP Echo Requests** to test if a host is reachable and measures round-trip time.

---

## 4️⃣ DNS, DNS Forwarder, NIC  
- **DNS** – Converts domain names → IP addresses.  
- **DNS Forwarder** – Sends unresolved queries to external DNS servers.  
- **NIC** – Hardware that connects your device to a network.

---

## 5️⃣ MAC Address  
A unique 48-bit hardware address assigned to every network interface.  
Used at Data Link Layer for local communication.

---

## 6️⃣ IP Address Types  
- **Private IP** – Used inside local networks (e.g., 192.168.x.x)  
- **Public IP** – ISP-assigned, globally reachable  
- **APIPA (169.254.x.x)** – Assigned automatically if DHCP fails  

---

## 7️⃣ IPv4 vs IPv6  

| Feature | IPv4 | IPv6 |
|--------|------|------|
| Size | 32-bit | 128-bit |
| Example | 192.168.1.1 | 2001:db8::1 |
| Security | Basic | IPSec built-in |
| Address Space | Smaller | Very large |

---

## 8️⃣ Subnet  
Dividing a network into smaller networks to improve security and reduce congestion.

Example:  
`192.168.1.0/24` → 256 addresses.

---

## 9️⃣ Firewalls  
Monitor and control incoming/outgoing traffic.  
Types:  
- Packet-filtering  
- Stateful  
- Proxy  
- Next-Gen Firewall (NGFW)

---

## 🔟 Types of Network Delays  
- **Processing Delay** – Time to process header  
- **Queuing Delay** – Time in queue  
- **Transmission Delay** – Time to send bits  
- **Propagation Delay** – Time signal takes to travel  

---

## 1️⃣1️⃣ TCP Three-Way Handshake  

1. **SYN** – Client sends connection request  
2. **SYN-ACK** – Server acknowledges  
3. **ACK** – Client confirms  

Connection established.

---

## 1️⃣2️⃣ Server-Side Load Balancer  
Distributes traffic among multiple servers.  
Improves availability, prevents overload.

---

## 1️⃣3️⃣ RSA Algorithm (Basics)  
Public-key encryption algorithm.  
Steps:  
1. Choose primes p, q  
2. Compute n = p × q  
3. Choose public key e  
4. Compute private key d  
Used for secure communication.

---

## 1️⃣4️⃣ HTTP vs HTTPS  

| Feature | HTTP | HTTPS |
|--------|------|--------|
| Security | No encryption | SSL/TLS encryption |
| Port | 80 | 443 |
| Use | General browsing | Secure transactions |

---

## 1️⃣5️⃣ SMTP Protocol  
Protocol for **sending emails**.  
Ports:  
- 25 → Unsecure  
- 465 → SSL  
- 587 → TLS  

---

## 1️⃣6️⃣ TCP vs UDP  

| Feature | TCP | UDP |
|--------|------|------|
| Type | Reliable | Unreliable |
| Connection | Yes | No |
| Speed | Slower | Faster |
| Use | Web, downloads | Gaming, streaming |

---

## 1️⃣7️⃣ How a Browser Loads a Website  
1. DNS lookup for IP  
2. TCP handshake  
3. TLS/SSL handshake (HTTPS)  
4. HTTP request sent  
5. Server returns webpage  
6. Browser renders UI  

---

## 1️⃣8️⃣ Hub vs Switch  

| Feature | Hub | Switch |
|--------|------|---------|
| Layer | Physical (L1) | Data Link (L2) |
| Collision | High | Low |
| Forwarding | Broadcast | Selective using MAC |
| Efficiency | Low | High |

---

## 1️⃣9️⃣ VPN — Advantages & Disadvantages  
**Advantages:**  
- Encrypts traffic  
- Hides IP  
- Bypasses geo-blocks  

**Disadvantages:**  
- Slower speed  
- Some sites block VPN  
- Requires setup  

---

## 2️⃣0️⃣ LAN (Local Area Network)  
A network covering a small geographic area like a home or office.  
Fast, secure, used for local sharing & communication.

---


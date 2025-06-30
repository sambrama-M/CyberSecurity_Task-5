# CyberSecurity_Task-5

# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
Capture live network packets using Wireshark and identify different types of protocols.

## Tool Used
- Wireshark (free network analyzer)

## Deliverables
- Packet capture files (.pcap)
- Short report of protocols identified

---

## Steps Performed

1. Installed and opened Wireshark.
2. Selected the active interface: Ethernet0.
3. Started capturing network traffic.
4. Visited YouTube, used the ping command, and opened a dummy HTTP website.
5. Entered test login credentials on the HTTP site: `username/admin123`.
6. Stopped the capture after about 1 minute.

---

## Key Observations

- Found the username and password in the HTTP packets.
- This shows how packet sniffing works.
- Learned that HTTP is not secure; always use HTTPS.

---

## Protocols Identified

- **TCP** – for YouTube and other reliable traffic.
- **UDP** – for fast, connectionless data.
- **ICMP** – from the ping command.
- **HTTP** – used by the dummy login site.

Saved filtered traffic into different `.pcap` files like `tcp_.pcap`, `udp_.pcap`, etc.

---

## What I Learned

- How to use Wireshark to capture and analyze packets.
- How to filter and save protocol-based traffic.
- The importance of using HTTPS for secure data transmission.

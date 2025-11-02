# Task 5 : Capture and Analyze Network Traffic Using Wireshark.

## Objective:
Capture live network packets and identify basic protocols and traffic types.

## Tools:
- **[Wireshark](https://www.wireshark.org/download.html) (free)**

## Table of contents:
- [Objective](#objective)
- [Install Wireshark](#install-wireshark)
- [Capturing packets](#capturing-packets)
    - [1. Open Wireshark](#1-open-wireshark)
    - [2. Start capturing Active Network Interface](#2-start-capturing-active-network-interface)
    - [3. Live Packet Capture](#3-live-packet-capture)
    - [4. Protocol filter](#4-protocol-filter) 
    - [5. Stop the capture](#5-stop-the-capture)
- [Save capture file (.pcap file)](#save-capture-file-pcap-file)
- [Findings and Summary](#findings-and-summary)

## Guide
1. Install Wireshark.
2. Start capturing on your active network interface.
3. Browse a website or ping a server to generate traffic.
4. Stop capture after a minute.
5. Filter captured packets by protocol (e.g., HTTP, DNS, TCP).
6. Identify at least 3 different protocols in the capture.
7. Export the capture as a .pcap file.
8. Summarize your findings and packet details.

---

## Install Wireshark
- **Go to https://www.wireshark.org/download.html**
- **Download and install Wireshark for macOS (or Windows/Linux if applicable)**
- **To verify installation, open terminal and run:**
    - wireshark --version

![Alt Text](images/InstallVerify.PNG)

---

## Capturing packets
### 1. Open Wireshark 
![Alt text](images/wireshark.PNG)

### 2. Start capturing Active Network Interface
- In Wireshark, double-click the active interface (usually en0).
- Wireshark will immediately start showing packets scrolling live, that's our network traffic being captured in real time.

![Alt text](images/active_interface.PNG)

### 3. Live Packet Capture
- While capture is running, create some network activity:
   1. Open a few websites (e.g, google.com, youtube.com)
   2. Or run a ping command as
      - ping google.com
![Alt text](images/ping.PNG)

![Alt text](images/capture_packets.PNG)
        
### 4. Protocol filter
- Applied 'dns' filter to view DNS traffic only
![Alt text](images/filtered_dns.PNG)

- Applied 'tcp' filter to view TCP traffic only
![Alt text](images/filtered_tcp.PNG)

- Applied 'udp' filter to view UDP traffic only
![Alt text](images/filtered_udp.PNG) 


### 5. Stop the capture
- After about 1 minute, click the red square (■) Stop button at the top.
- We'll see all captured packets frozen in the list     

---

## Save capture file (.pcap file)
- File: [Network_capture.pcap](NetworkCapture.pcapng)

---

### Findings and Summary

---

## Outcome:
Hands-on packet analysis skills and protocol awareness.
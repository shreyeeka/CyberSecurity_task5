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
    - [2. Start capturing](#2-start-capturing) 

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
1. Open Wireshark 
![Alt text](images/wireshark.PNG)

2. Start capturing
- In Wireshark, double-click the active interface (usually en0).
- Wireshark will immediately start showing packets scrolling live, that's our network traffic being captured in real time. 

---

## Outcome:
Hands-on packet analysis skills and protocol awareness.
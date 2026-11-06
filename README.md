# Cybersecurity Lab Deployment & Wireshark Investigation

## Introduction

This repository documents practical work involving virtual machine deployment, network configuration, and network security investigation.

The project uses Kali Linux in Oracle VirtualBox to establish a testing environment, followed by Wireshark exercises to examine network communication and identify potential security threats.

## 1. Virtual Lab Deployment

A virtual cybersecurity environment was prepared with the following configuration:

| Component | Configuration |
|---|---|
| Virtualization | Oracle VirtualBox |
| Operating System | Kali Linux |
| Network Mode | NAT Network |
| Network Range | `10.0.0.0/24` |
| Kali Linux IP | `10.0.0.2/24` |
| Shared Resources | Host-to-Guest shared folder |
| Connectivity | Internet and network connectivity testing |
| Recovery | Virtual machine snapshot |

Additional configuration included clipboard sharing and drag-and-drop support.

## 2. Wireshark Practical Exercises

Wireshark was used to inspect captured network traffic and explore several security scenarios.

### Port Scanning Detection
Investigated network traffic to identify port scanning activity and determine the source of suspicious requests.

### TCP Stream Analysis
Inspected TCP communication streams to understand how network sessions can be reconstructed and examined.

### HTTP Credential Exposure
Analyzed unencrypted HTTP traffic to understand how sensitive authentication information can become exposed.

### FTP Brute-Force Investigation
Examined repeated FTP authentication attempts, identified failed login responses, and investigated the successful authentication event.

### VoIP Traffic Analysis
Studied SIP and RTP traffic to understand call setup, voice transmission, and the security implications of unencrypted communication.

## 3. Technologies Used

- Kali Linux
- Oracle VirtualBox
- Wireshark
- TCP/IP
- FTP
- HTTP
- SIP
- RTP

## 4. Skills Practiced

- Virtual machine installation and configuration
- Network setup and connectivity verification
- Packet capture and protocol identification
- TCP session inspection
- Detection of suspicious network activity
- Authentication traffic investigation
- VoIP protocol analysis
- Basic security risk identification

## 5. Conclusion

This practical work provided experience in deploying a cybersecurity testing environment and using packet analysis to investigate network behavior.

It also demonstrated how network traffic analysis can help identify suspicious activities and security weaknesses, particularly when communication is not properly encrypted.

## Collaboration

In collaboration with: **Waqas Karim (CCIE)**

---

*All activities were conducted in a controlled educational lab environment.*

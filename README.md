# 🔐 Cybersecurity Virtual Lab – VirtualBox

## 📌 Project Overview

This project demonstrates the setup of a basic **Cybersecurity & Networking Virtual Lab** using Oracle VirtualBox.

The lab consists of multiple virtual machines running different operating systems, including **Kali Linux, Windows, and Android**. All the virtual machines were configured to communicate over the same virtual network.

This environment can be used for learning **networking, cybersecurity fundamentals, penetration testing concepts, and virtual machine management** in a controlled lab environment.

---

## 🖥️ Virtual Machines Used

| Operating System | Purpose |
|---|---|
| Kali Linux | Cybersecurity & penetration testing |
| Windows | Client/target machine for lab testing |
| Android | Mobile operating system & network testing |

---

## 🛠️ Technologies & Tools

- Oracle VirtualBox
- Kali Linux
- Windows
- Android
- Virtual Networking
- IP Addressing
- Ping / Network Connectivity Testing

---

## 🎯 Objectives

The main objectives of this project were:

- Learn how to create and manage Virtual Machines
- Install different operating systems in VirtualBox
- Creating NAT network 
- Assign and verify IP addresses
- Connect Kali Linux, Windows, and Android to the same network
- Test communication between virtual machines
- Understand basic virtual network troubleshooting
- Build a controlled environment for cybersecurity practice

---

## ⚙️ Lab Setup

The virtual lab was created using **Oracle VirtualBox**.

Lab Configuration

🧩 Component	⚙️ Configuration
🖥️ Host OS	Windows 10
🧠 Host RAM	8 GB
⚡ Processor	Intel Core i7
🧰 Hypervisor	VirtualBox 7.2
🐉 Security OS	Kali Linux 2026.2
🧠 Kali RAM	2048 MB
🌐 Virtual Network	NAT Network
📡 Network Address	10.0.0.0/24
🐧 Kali IP Address	10.0.0.2/24
🚪 Default Gateway	10.0.0.1
🌍 DNS Server	8.8.8.8
🔮 Future VM Range	10.0.0.3–10.0.0.99


Lab Setup Procedure

Step 1. Install 7-Zip

7-Zip was installed to extract the Kali Linux virtual-machine package, which may be distributed as a .7z archive.

Tool: 7-Zip

Step 2. Install VirtualBox

VirtualBox was installed as the hypervisor.

Step 3. Create the NAT Network

A dedicated NAT Network was created in VirtualBox.

Configuration: Network Name: NatNetwork IPv4 Prefix: 10.0.0.0/24 DHCP: Enabled IPv6: Disabled

Step 4. Import Kali Linux

The Kali Linux virtual machine was downloaded from the official Kali Linux website and imported into VirtualBox.

Step 5. Configure the Kali Linux Network

The Kali Linux network configuration was checked and configured with a consistent IPv4 address.

Tools & Resources

7-Zip: https://7-zip.org/download.html
VirtualBox: https://virtualbox.org/wiki/Downloads
Kali Linux: https://kali.org/get-kali

Author

Aryan Deshmukh
Cybersecurity Student B083C

LinkedIn: https://www.linkedin.com/in/aryan-deshmukh-a963b9318?utm_source=share_via&utm_content=profile&utm_medium=member_ios 



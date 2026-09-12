# 🛡️ Cybersecurity Lab Setup

> Building the environment before testing the security.

## 🔎 About This Project

This project documents the setup of a controlled cybersecurity testing lab using **Kali Linux** and **Oracle VirtualBox**.

The purpose of this lab is to create a safe and reliable environment for practicing cybersecurity concepts, network security, reconnaissance, and security testing in an authorized lab environment.

## 🧰 Lab Environment

- **Host OS:** Windows
- **Virtualization:** Oracle VirtualBox
- **Attacking Machine:** Kali Linux
- **Network Type:** NAT Network
- **Network Name:** `NatNetwork`
- **Subnet:** `10.0.0.0/24`
- **Kali Linux IP:** `10.0.0.2`
- **Gateway:** `10.0.0.1`

## ⚙️ Configuration Completed

- ✅ Kali Linux imported into VirtualBox
- ✅ NAT Network configured
- ✅ Network subnet configured as `10.0.0.0/24`
- ✅ Static IP configured for Kali Linux
- ✅ Internet connectivity verified
- ✅ Shared Clipboard enabled
- ✅ Drag & Drop enabled
- ✅ Shared folder configured
- ✅ Virtual machine snapshot created

## 🌐 Network Configuration

The Kali Linux virtual machine was configured with a static IP address within the lab network.

```text
IP Address  : 10.0.0.2
Subnet      : 255.255.255.0
Gateway     : 10.0.0.1
Network     : 10.0.0.0/24

🧪 Connectivity Test

Internet connectivity was verified from Kali Linux using:

ping google.com

Successful replies confirmed that the lab machine had internet connectivity.

📁 Shared Folder

A VirtualBox shared folder named downloads was configured to allow file sharing between the host system and the Kali Linux virtual machine.

🎯 Objective

The main objective of this project is to build a controlled cybersecurity testing environment where security tools and techniques can be practiced safely and only on authorized systems.

📚 Learning Outcomes

Through this setup, I gained practical experience in:

Virtual machine configuration

Kali Linux setup

NAT networking

Static IP configuration

Linux network configuration

Internet connectivity testing

VirtualBox features

Basic network troubleshooting

Preparing a cybersecurity testing environment


🔐 Safety & Authorization

This lab is intended only for authorized cybersecurity learning and testing.

All security testing should be performed only on systems that I own or have explicit permission to test.


---

📌 Project Information

Project: Cybersecurity Testing Lab Environment
Week: 1
Platform: Kali Linux + Oracle VirtualBox
Network: 10.0.0.0/24

> A secure testing environment is the first step toward responsible security testing.



**Repository name:** `cybersecurity-lab-setup`  
**Description:** `A practical cybersecurity lab setup using Kali Linux and Oracle VirtualBox for security testing and learning.`
 
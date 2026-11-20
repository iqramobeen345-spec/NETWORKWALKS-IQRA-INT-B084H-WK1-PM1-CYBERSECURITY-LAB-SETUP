# NETWORKWALKS-IQRA-INT-B084H-WK1-PM1-CYBERSECURITY-LAB-SETUP
Cybersecurity Lab Setup using VirtualBox and Kali Linux
# 🔐 Cybersecurity Lab Environment Setup

## Week 1 | Project Module 1

**Internship:** Cybersecurity Internship – Networkwalks  
**Project:** Practical Lab Environment Setup  
**Tools:** Oracle VirtualBox, Kali Linux  
**Module:** WK1-PM1

---

## 📌 Project Overview

This project focuses on building a virtual cybersecurity testing environment using Oracle VirtualBox and Kali Linux.

The purpose of this lab is to create a dedicated virtual environment for learning cybersecurity concepts, ethical hacking, penetration testing, and practical security exercises.

Kali Linux is configured as a virtual machine, while VirtualBox provides the virtualization platform and virtual networking environment.

## 🎯 Project Objectives

- Install and configure Oracle VirtualBox.
- Download and import Kali Linux as a virtual machine.
- Create a custom NAT Network.
- Configure static IP addressing.
- Enable clipboard sharing and drag-and-drop.
- Configure shared folders between the host and virtual machine.
- Verify internet connectivity.
- Create a virtual machine snapshot for backup and recovery.

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Oracle VirtualBox | Virtualization platform |
| Kali Linux | Cybersecurity testing operating system |
| 7-Zip | File extraction |
| NAT Network | Virtual network configuration |

## ⚙️ Lab Configuration

| Component | Configuration |
|---|---|
| Virtualization Platform | Oracle VirtualBox |
| Guest Operating System | Kali Linux |
| Network Mode | NAT Network |
| Network Subnet | 10.0.0.0/24 |
| Kali Linux IP | 10.0.0.2/24 |
| Gateway | 10.0.0.1 |
| Shared Folder | /downloads |
| Internet Access | Required |

## 🚀 Implementation Steps

### Step 1: Install 7-Zip

Download and install 7-Zip to extract the downloaded virtual machine files.

### Step 2: Install Oracle VirtualBox

Download and install Oracle VirtualBox on the host computer.

### Step 3: Create a NAT Network

Open VirtualBox Network settings and create a custom NAT Network.

Configure the IPv4 network as:

- Network: 10.0.0.0/24
- Enable DHCP according to the lab configuration.

### Step 4: Download and Import Kali Linux

Download the Kali Linux VirtualBox image from the official Kali Linux website.

Import the virtual machine into Oracle VirtualBox.

### Step 5: Configure Virtual Machine Settings

Configure the Kali Linux VM with the following settings:

- Attach the network adapter to the created NAT Network.
- Enable the virtual network adapter.
- Enable shared clipboard.
- Enable drag-and-drop.
- Configure the shared folder from the host machine.

### Step 6: Configure Kali Linux Network

Configure the Kali Linux network interface with the required static IP address:

- IP Address: 10.0.0.2
- Netmask: 255.255.255.0
- Gateway: 10.0.0.1
- DNS: 8.8.8.8

### Step 7: Verify Network Connectivity

Check the network configuration and test internet connectivity from Kali Linux.

### Step 8: Create a Virtual Machine Snapshot

Create a snapshot of the configured Kali Linux virtual machine.

This snapshot provides a recovery point if any configuration changes cause problems during future practical exercises.

## 📸 Screenshots

Screenshots of the completed lab configuration are included in the `screenshots/` directory.

1. VirtualBox NAT Network configuration.
2. Kali Linux desktop running inside VirtualBox.
3. Kali Linux network configuration.
4. Shared folder configuration.
5. Virtual machine snapshot.

## 📚 Key Learning Outcomes

Through this project, I learned:

- Fundamentals of virtualization.
- Installing and managing virtual machines.
- Basic virtual networking concepts.
- Configuring static IP addresses.
- Understanding NAT Network architecture.
- Sharing files between host and guest systems.
- Creating VM snapshots for backup and recovery.
- Preparing a controlled environment for cybersecurity practice.



---

**Learning through practice | Building cybersecurity skills step by step.**

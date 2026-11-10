# network-monitoring-setup-
network-monitoring-cisco-packet

# APEX CORP – Network Monitoring Setup

## 📌 Project Overview

The APEX CORP Network Monitoring Setup is an enterprise network simulation developed using Cisco Packet Tracer. It demonstrates how an organization can design, configure, manage, and monitor its network infrastructure.

The project focuses on VLAN segmentation, inter-VLAN routing, DHCP, DNS, NTP, and centralized Syslog monitoring.

## 🎯 Project Objectives

* Design an enterprise network infrastructure.
* Implement department-wise VLAN segmentation.
* Configure inter-VLAN routing.
* Automate IP address assignment using DHCP.
* Configure centralized DNS services.
* Implement NTP for time synchronization.
* Configure Syslog for centralized network monitoring.
* Test connectivity between departments and servers.

## 🖥️ Network Devices Used

| Device                 | Purpose                                 |
| ---------------------- | --------------------------------------- |
| Cisco 2911 Core Router | Inter-VLAN routing                      |
| Distribution Switches  | VLAN aggregation and traffic forwarding |
| Access Switches        | Connect departmental PCs                |
| Management Server      | Centralized Syslog monitoring           |
| Application Server     | Application hosting                     |
| DNS-DHCP Server        | IP assignment and name resolution       |
| PCs                    | Departmental users                      |

## 🌐 VLAN Configuration

| VLAN ID | Department | Gateway      |
| ------- | ---------- | ------------ |
| 10      | Admin      | 192.168.10.1 |
| 20      | Staff      | 192.168.20.1 |
| 30      | HR         | 192.168.30.1 |
| 40      | IT         | 192.168.40.1 |
| 50      | Servers    | 192.168.50.1 |
| 60      | Finance    | 192.168.60.1 |
| 70      | Management | 192.168.70.1 |
| 80      | Executive  | 192.168.80.1 |

## ⚙️ Technologies Implemented

### 1. VLAN Configuration

Separate VLANs are created for different departments to organize network traffic and improve network management.

### 2. Inter-VLAN Routing

The Core Router uses subinterfaces and 802.1Q encapsulation to enable communication between different VLANs.

### 3. DHCP

DHCP automatically assigns IP addresses, subnet masks, and default gateways to client PCs.

### 4. DNS

DNS provides name resolution by translating domain names into IP addresses.

### 5. NTP

NTP synchronizes time across network devices to maintain accurate timestamps.

### 6. Syslog Monitoring

Syslog collects log messages from the Core Router, distribution switches, and access switches on a centralized Management Server.

* Syslog Server: 192.168.50.10
* Protocol: UDP
* Port: 514
* Logging Level: Informational

## 🧪 Testing and Verification

* Verified VLAN configurations.
* Verified trunk links between switches.
* Tested gateway connectivity from departmental PCs.
* Tested inter-VLAN communication.
* Verified connectivity to the Management Server.
* Verified Syslog messages from network devices.

## 📊 Project Benefits

* Centralized network monitoring.
* Better network organization.
* Easier troubleshooting.
* Department-wise network segmentation.
* Automated IP configuration.
* Improved network administration.

## 🛠️ Software Used

* Cisco Packet Tracer

## 🚀 Conclusion

The APEX CORP Network Monitoring Setup demonstrates an enterprise network environment with VLAN segmentation, inter-VLAN routing, centralized server services, and Syslog-based monitoring.

This project provides practical experience in network configuration, connectivity testing, monitoring, and troubleshooting using Cisco Packet Tracer.

**Project Name:** APEX CORP – Network Monitoring Setup
**Category:** Computer Networking
**Platform:** Cisco Packet Tracer


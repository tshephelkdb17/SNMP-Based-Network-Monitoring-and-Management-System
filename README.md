# SNMP-Based Network Monitoring and Management System using Cisco Packet Tracer

## Project Overview

This project demonstrates the design, configuration, and management of a simulated enterprise network using **Cisco Packet Tracer** and the **Simple Network Management Protocol (SNMP)**. The network consists of multiple routers, switches, and end devices connected through OSPF dynamic routing, where a dedicated Network Manager PC monitors and manages SNMP-enabled devices.

The project showcases practical network administration tasks including device monitoring, remote management, interface status analysis, and configuration changes using SNMP Management Information Base (MIB) objects and Object Identifiers (OIDs).

---

## Network Architecture

The network follows an SNMP Manager-Agent model:

* **SNMP Manager:** Network Manager PC responsible for monitoring and sending management requests.
* **SNMP Agents:** Cisco routers and switches configured to provide management information.
* **Routing Protocol:** OSPF was implemented to establish connectivity between different network segments.
* **Network Segmentation:** VLANs were configured on switches for management purposes.

---

## Key Features

* Configured a multi-site enterprise network topology using Cisco Packet Tracer.
* Implemented OSPF dynamic routing to enable communication between multiple networks.
* Configured SNMP Read-Only (RO) and Read-Write (RW) communities for secure monitoring and management.
* Used MIB Browser to retrieve device information such as system names, interface descriptions, and operational status.
* Identified network interfaces using OIDs including `sysName`, `ifDescr`, `ifAdminStatus`, and `ifOperStatus`.
* Performed SNMP GET and SET operations to monitor devices and modify interface administrative states.
* Verified network connectivity and device communication through testing and troubleshooting.

---

## Technologies and Tools

* Cisco Packet Tracer
* Cisco IOS Command Line Interface (CLI)
* Simple Network Management Protocol (SNMP)
* Management Information Base (MIB)
* Object Identifiers (OIDs)
* Open Shortest Path First (OSPF)
* VLAN Configuration
* IPv4 Addressing and Subnetting

---

## Learning Outcomes

Through this project, I gained hands-on experience in enterprise network configuration and management. The project strengthened my understanding of SNMP architecture, network monitoring, remote device administration, OSPF routing, and troubleshooting using Cisco networking tools.

---


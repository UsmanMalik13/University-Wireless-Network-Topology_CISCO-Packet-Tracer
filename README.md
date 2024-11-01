# Implementation of a Hybrid Computer Network Topology with VLAN Support

This project involves designing and implementing a hybrid computer network topology that incorporates VLANs to manage traffic between departments efficiently in a medium-sized company. The network supports both wired and wireless connections, ensuring secure data handling, optimal traffic management, and scalability for future needs.

---

## Table of Contents

- [Problem Statement](#problem-statement)
- [Solution Overview](#solution-overview)
- [Network Design](#network-design)
- [VLAN Configuration](#vlan-configuration)
- [Hardware and Software Requirements](#hardware-and-software-requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Future Enhancements](#future-enhancements)
- [License](#license)
- [Contact](#contact)

---

## Problem Statement

A medium-sized company requires a robust and efficient network topology with VLAN support to separate and manage traffic between various departments. The network should support wired connections for regular workstations and provide wireless access for mobile devices and guests, ensuring efficient traffic management and data security.

---

## Solution Overview

### Project Title
**Implementation of a Hybrid Computer Network Topology with VLAN Support**

### Introduction
This project focuses on creating a computer network topology designed for a medium-sized company with diverse departmental needs. By integrating VLANs, the network efficiently handles traffic, enhances data security, and is scalable for future expansions. The design combines switches, routers, access points, and PCs in a hybrid topology, optimizing both wired and wireless connections.

---

## Network Design

The network topology is structured to separate data traffic based on departmental requirements using three VLANs:

1. **VLAN 1 - General Users (Wireless)**:  
   - Contains two PCs connected wirelessly through a **WRT300N Wireless Router**.
   
2. **VLAN 2 - Administration (Wired)**:  
   - Contains one PC connected via Ethernet for high-speed, secure data transfer, designated for tasks requiring higher bandwidth. This segment represents the **Admin Side**.

3. **VLAN 3 - Guests and Mobile Users (Wireless)**:  
   - Designed for guest or mobile users with wireless connectivity through an **Access Point**.

A **3560 Multilayer Switch** centrally manages traffic between VLANs, ensuring efficient data flow, security, and segregation as required by each department.

---

## VLAN Configuration

The VLAN configuration enables isolated and secure communication within each department while allowing for controlled inter-VLAN communication through routing policies. Each VLAN is assigned as follows:

- **VLAN 1**: For general wireless access, segregating general users.
- **VLAN 2**: Dedicated to administrative tasks, ensuring high security and wired connection.
- **VLAN 3**: Set up for guest users, isolating external traffic from internal users.

The **3560 Multilayer Switch** enables effective routing and switching across VLANs, optimizing data handling and improving network efficiency.

---

## Hardware and Software Requirements

### Hardware
- **3560 Multilayer Switch**: Central management of VLANs and traffic.
- **WRT300N Wireless Router**: Provides wireless access for VLAN 1.
- **Access Point**: Supports wireless access for guests in VLAN 3.
- **Ethernet cables** for wired connections in VLAN 2.
- **PCs**: For testing wired and wireless connectivity within VLANs.

### Software
- **Cisco Packet Tracer** (or similar network simulation software): To design, implement, and simulate the network topology.
  
---

## Installation

1. **Set Up VLANs**: Use the Cisco Packet Tracer to create and configure the VLANs for different departments.
2. **Configure the 3560 Multilayer Switch**: Set up inter-VLAN routing to manage traffic efficiently.
3. **Connect the Devices**: Ensure correct connections between PCs, routers, switches, and access points.
4. **Assign IPs and Test Connectivity**: Assign static IPs to devices within each VLAN, then use ping tests to verify network connectivity.

---

## Usage

- **Connect to the Network**: Devices automatically connect to their assigned VLAN based on the configuration.
- **Data Flow and Security**: Traffic between VLANs is managed through the multilayer switch, allowing controlled access.
- **Add New Devices**: Future devices can be added to the network by assigning them to the relevant VLANs to ensure continued segmentation and security.

---

## Future Enhancements

- **Scalability**: Extend the network with additional VLANs as the company grows.
- **Advanced Security Features**: Implement firewall settings for further security between VLANs.
- **Performance Monitoring**: Use network monitoring tools to ensure optimal traffic management.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact

For any questions or further information, feel free to reach out:

**Usman Malik**  
- Email: [usman.malik051301@gmail.com](mailto:usman.malik051301@gmail.com)
- GitHub: [UsmanMalik13](https://github.com/UsmanMalik13)

---


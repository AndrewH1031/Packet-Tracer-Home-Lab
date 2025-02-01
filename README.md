# Packet Tracer Home Lab

## Overview

This is a large virtual network developed in CISCO Packet Tracer version 8.2.2. I created this project to apply what I've learned from the Cisco Networking Academy course and to get a better understanding of networking protocols.

## Key Components

PCs - Each assigned an IPv4 address through DHCP and a unique VLAN. Not pingable by other devices except for those connected via trunk port.

Telephones - Configured for VoIP and able to simulate phone calls between themselves.

Printers - Four set up on each of the main routers. These are only pingable by their respective PCs on the VLAN associated with them.

Switches - Connected via Ethernet cable with trunking enabled. Supports communication between VLANs on connected devices.

Servers - DHCP enabled.

Routers - OSPF routing enabled, allowing for efficient travel of information bnetween devices.

ISP - A special router connecting the Cluster network to the main branch. PAT has been enabled to translate all addresses in the Cluster to a single private IP.

Additional documentation of IP addresses and VLANS for each machine can be found in the project document.

## Installation

Before getting started, clone or download this repository to your local machine.

1. Download and configure CISCO Packet Tracer v8.2.2 via the official site --> https://www.netacad.com/resources/lab-downloads. Note that this will require a NetAcademy account.

2. Open the project file in Packet Tracer.

That's it! Enjoy playing around with the network.

# Hands-On Labs Using Cisco Packet Tracer and GNS3

This document provides a comprehensive collection of 15 hands-on labs designed to reinforce the concepts learned in CCNA training. Each lab includes step-by-step instructions, expected outcomes, troubleshooting tips, and real-world scenario applications. The instructions are available in both English and Hinglish for better understanding.

## Lab 1: Basic Router Configuration
### Objective
Learn how to configure basic settings on a Cisco router.

### Instructions
1. Open Cisco Packet Tracer.
2. Add a router to the workspace.
3. Access the CLI of the router.
4. Enter global configuration mode by typing `configure terminal`.
5. Set the hostname using `hostname Router1`.
6. Configure the enable secret password using `enable secret cisco123`.
7. Exit to the user mode.

### Expected Outcome
The router should have a hostname of Router1 and will require the enable password to access privileged commands.

### Troubleshooting Tips
- If you cannot access privileged mode, double-check the enable secret password entered.

### Real-World Scenario
This lab simulates the initial configuration of routers in enterprise networks.

---

## Lab 2: VLAN Configuration
### Objective
Understand VLAN creation and configuration.

### Instructions
1. Open Cisco Packet Tracer.
2. Add switches to the workspace and connect routers.
3. Access the switch CLI.
4. Create VLAN 10 using `vlan 10` command.
5. Assign ports to VLAN 10.

### Expected Outcome
Devices connected to the assigned ports will be in VLAN 10 and isolated from other VLANs.

### Troubleshooting Tips
- Ensure ports are assigned to the VLAN correctly using `show vlan` command.

### Real-World Scenario
VLANs are used to segment network traffic in large organizations.

---

## Lab 3: Inter-VLAN Routing
### Objective
Set up inter-VLAN routing using a router.

### Instructions
1. Configure VLANs on the switch as per Lab 2.
2. Set up sub-interfaces on the router for each VLAN.
3. Enable routing on the router.

### Expected Outcome
Devices in different VLANs can communicate with each other.

### Troubleshooting Tips
- Verify sub-interface configurations and check VLAN assignments.

### Real-World Scenario
Inter-VLAN routing enables communication between different departments in a company.

---

## Lab 4: Static Routing
### Objective
Learn about static routing and its configuration.

### Instructions
1. Add two routers and connect them.
2. Configure static routes on both routers.

### Expected Outcome
Routers should be able to direct traffic without dynamic routing protocols.

### Troubleshooting Tips
- Check routing tables using `show ip route` command.

### Real-World Scenario
Static routing is often used in small networks with predictable traffic patterns.

---

## Lab 5: Access Control Lists (ACLs)
### Objective
Implement standard and extended ACLs.

### Instructions
1. Create a standard ACL to block traffic from a specific subnet.
2. Create an extended ACL to permit specific types of traffic.

### Expected Outcome
Traffic to and from specified subnets should be controlled per the ACL rules.

### Troubleshooting Tips
- Ensure the correct ACL is applied to the correct interface.

### Real-World Scenario
ACLs are crucial for network security and traffic regulation.

---

## Lab 6: DHCP Configuration
### Objective
Configure DHCP for an internal network.

### Instructions
1. Set up a router to provide DHCP services.
2. Configure the DHCP pool settings.

### Expected Outcome
Devices should receive IP addresses automatically via DHCP.

### Troubleshooting Tips
- Verify DHCP configuration and check if the server is reachable.

### Real-World Scenario
DHCP simplifies IP address management in large networks.

---

## Lab 7: NAT Configuration
### Objective
Set up NAT to allow private IPs to access the internet.

### Instructions
1. Configure NAT on the router using the `ip nat inside source list` command.
2. Test the configuration with a PC accessing the internet.

### Expected Outcome
Private IPs should be able to communicate with public networks.

### Troubleshooting Tips
- Check NAT configuration and ensure access lists are properly configured.

### Real-World Scenario
NAT is widely used in home networks and organizations to manage IP addresses efficiently.

---

## Lab 8: Spanning Tree Protocol (STP)
### Objective
Understand STP and how to prevent loops in switched networks.

### Instructions
1. Add multiple switches and connect them in a loop.
2. Configure STP using `spanning-tree mode` command.

### Expected Outcome
STP will block redundant paths to prevent loops in the network.

### Troubleshooting Tips
- Check STP states using `show spanning-tree` command.

### Real-World Scenario
STP is essential for maintaining network stability in complex environments.

---

## Lab 9: Wireless Network Configuration
### Objective
Set up a basic wireless network.

### Instructions
1. Add a wireless router to the workspace.
2. Configure SSID and security settings.
3. Connect wireless devices.

### Expected Outcome
Devices should connect to the wireless network successfully.

### Troubleshooting Tips
- Verify wireless settings and ensure correct encryption methods are used.

### Real-World Scenario
Wireless networking is crucial for providing mobility in organizational environments.

---

## Lab 10: VPN Configuration
### Objective
Implement a basic VPN connection.

### Instructions
1. Set up a VPN server on the router.
2. Configure clients to connect to the VPN.

### Expected Outcome
Clients should be able to connect securely to the internal network.

### Troubleshooting Tips
- Ensure the correct VPN configurations are in place on both server and clients.

### Real-World Scenario
VPNs are essential for secure remote access to organizational resources.

---

## Lab 11: QoS Configuration
### Objective
Understand Quality of Service (QoS) principles and configuration.

### Instructions
1. Configure QoS policies on the router.
2. Test with different types of traffic.

### Expected Outcome
Traffic should be prioritized based on the QoS settings.

### Troubleshooting Tips
- Monitor traffic to ensure correct QoS policy application.

### Real-World Scenario
QoS is critical for businesses relying on real-time applications like VoIP.

---

## Lab 12: IPv6 Configuration
### Objective
Learn how to configure IPv6 on routers and devices.

### Instructions
1. Enable IPv6 on the router.
2. Assign IPv6 addresses to interfaces.

### Expected Outcome
Devices should be reachable using IPv6 addresses.

### Troubleshooting Tips
- Verify IPv6 configurations with `show ipv6 interface` commands.

### Real-World Scenario
IPv6 adoption is crucial due to the exhaustion of IPv4 addresses.

---

## Lab 13: Syslog Configuration
### Objective
Set up Syslog for network logging.

### Instructions
1. Configure the router to send logs to a Syslog server.
2. Test log message generation.

### Expected Outcome
Logs should be received and stored on the Syslog server.

### Troubleshooting Tips
- Ensure network connectivity between router and Syslog server.

### Real-World Scenario
Syslog is essential for monitoring network performance and troubleshooting.

---

## Lab 14: Network Monitoring with SNMP
### Objective
Configure SNMP for network monitoring.

### Instructions
1. Enable SNMP on the router.
2. Configure SNMP community strings and access levels.

### Expected Outcome
Network devices should be monitored using SNMP tools.

### Troubleshooting Tips
- Check SNMP configurations and ensure monitoring tools are correctly set up.

### Real-World Scenario
SNMP is widely used for network management and performance monitoring.

---

## Lab 15: Dynamic Routing Protocols
### Objective
Implement OSPF and EIGRP in a lab environment.

### Instructions
1. Set up multiple routers.
2. Configure OSPF and EIGRP on the routers.

### Expected Outcome
Dynamic routing should enable efficient path selection for data transmission.

### Troubleshooting Tips
- Monitor routing tables and use ping tests to validate configurations.

### Real-World Scenario
Dynamic routing protocols are essential for modern networks, ensuring effective communication between large numbers of devices.
# Lab 01 - Network Diagnostics

## Objective

Identify and analyze the network configuration of a Windows system using built-in networking tools.

## Command Used

```bash
ipconfig /all
```

## Information Found

* IPv4 Address: 10.101.212.207
* Subnet Mask: 255.255.128.0
* Default Gateway: 10.101.128.1
* DNS Server: 19.198.0.70
* DHCP Enabled: Yes

## Analysis

The system is using a private IPv4 address within the 10.0.0.0/8 address range.

The subnet mask of 255.255.128.0 indicates a /17 network, which is commonly used in enterprise environments to support a large number of devices.

The default gateway (10.101.128.1) is responsible for forwarding traffic outside the local network.

The DNS server translates domain names into IP addresses, allowing users to access websites using human-readable names.

DHCP is enabled, meaning the system automatically receives network settings from a DHCP server.

## Questions

### What is an IPv4 address?

Answer:
An IPv4 address is a logical address used to identify devices on a network.

### What is the purpose of a subnet mask?

Answer:
A subnet mask divides an IP address into network and host portions.

### What is a default gateway?

Answer:
A default gateway forwards traffic from the local network to other networks.

### What does DNS do?

Answer:
DNS translates domain names into IP addresses.

### What does DHCP do?

Answer:
DHCP automatically assigns network settings to devices.

## What I Learned

* How to identify network configuration information using ipconfig /all.
* The difference between IP addresses, subnet masks, and default gateways.
* How DNS and DHCP support network communication.
* How enterprise networks use private IP addressing.

## Cybersecurity Connection

Security analysts frequently collect and analyze network configuration information when troubleshooting systems, investigating incidents, and understanding how devices communicate across a network.
## Safety Considerations

* Only collect and analyze network information from systems and networks you are authorized to use.
* Avoid sharing sensitive information such as public IP addresses, MAC addresses, or organization-specific network details publicly.
* Review lab outputs before uploading screenshots or command results to GitHub to ensure sensitive information is removed or redacted.

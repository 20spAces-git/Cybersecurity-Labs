# Lab 02 - ARP Analysis

## Objective

Analyze the ARP table on a Windows system and understand how IP addresses are mapped to MAC addresses.

## Command Used

```bash
arp -a
```

## Interface Information

Interface IP Address:

10.101.212.207

Interface Identifier:

0xe

## Results

Dynamic Entries: 2

Static Entries: 6

## Analysis

The ARP table displayed mappings between IP addresses and MAC addresses for devices on the local network.

The system contained two dynamic entries, which were automatically learned through network communication.

The ARP table also contained six static entries. Static entries are predefined and are commonly associated with multicast or broadcast traffic.

ARP improves network efficiency by storing MAC address information so devices do not need to repeatedly broadcast ARP requests.

## Questions

### What does ARP stand for?

Answer:

Address Resolution Protocol

### What information is stored in the ARP table?

Answer:

The ARP table stores IP addresses and their corresponding MAC addresses.

### Why is ARP important?

Answer:

ARP allows devices on a local network to determine the MAC address associated with an IP address.

### What type of address does ARP resolve?

Answer:

ARP resolves IP addresses to MAC addresses.

## What I Learned

* ARP maps IP addresses to MAC addresses.
* Dynamic entries are learned automatically.
* Static entries are predefined and often support network services.
* ARP tables improve communication efficiency on local networks.

## Cybersecurity Connection

Security analysts frequently examine ARP tables when troubleshooting connectivity problems and investigating suspicious activity.

Understanding normal ARP behavior is important when identifying attacks such as ARP spoofing.

## Safety Considerations

* Only analyze ARP information on systems and networks you own or are authorized to use.
* Remove or redact sensitive network information before uploading lab results to GitHub.
* Do not attempt ARP spoofing or offensive techniques on production networks.
* Follow organizational policies and ethical guidelines when performing network analysis.

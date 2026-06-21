# Lab Observations and Notes

## Observation 1 - Enterprise Network Addressing

During Lab 01, the system was assigned the IP address:

10.101.212.207

with a subnet mask of:

255.255.128.0

This indicated that the device was operating on a large enterprise-style network rather than a typical home network.

---

## Observation 2 - Gateway Differences

The default gateway identified during Network Diagnostics was:

10.101.128.1

During Traceroute, the first hop observed was:

10.101.128.2

This demonstrates that different network devices may participate in routing traffic within an enterprise environment.

---

## Observation 3 - ARP Entries

The ARP table contained:

* 2 Dynamic Entries
* 6 Static Entries

This demonstrated how systems store previously learned MAC address mappings to improve communication efficiency.

---

## Observation 4 - IPv6 Discovery

The DNS lookup for google.com returned:

2607:f8b0:4023:1002::66

This was an IPv6 address, demonstrating that modern internet services support IPv6 communication.

---

## Observation 5 - Active Network Connections

The netstat analysis identified:

* 25 Listening Connections
* 47 Established Connections

This demonstrated that modern operating systems maintain many active network connections simultaneously through both TCP and UDP protocols.

---

## Future Research Topics

* IPv6 Addressing
* Wireshark Packet Analysis
* Nmap Network Scanning
* Common TCP Ports
* Common UDP Ports
* Windows Networking Internals
* DNS Security
* ARP Spoofing
* Packet Capture Analysis
# Lab Observations and Notes

## Key Observations

Document interesting findings from labs.

Example:

* Enterprise network used a /17 subnet mask.
* DNS returned an IPv6 address.
* Traceroute passed through multiple service providers.
* Windows maintained dozens of active connections.

---

## Common Mistakes to Avoid

* Forgetting to document command output.
* Publishing sensitive network information.
* Assuming "Request Timed Out" always means a failure.
* Confusing MAC addresses with IP addresses.
* Ignoring IPv6 addresses.

---

## Best Practices

* Document findings immediately after completing a lab.
* Verify results before publishing.
* Use screenshots when appropriate.
* Keep lab notes organized and consistent.
* Focus on understanding the results, not just collecting them.

---

## Cybersecurity Ethics

* Only perform activities on systems and networks you own or are authorized to use.
* Respect privacy and organizational policies.
* Do not use learning activities for unauthorized access.
* Follow responsible disclosure practices.

---

## Terms I Want to Research Further

* IPv6
* VLANs
* Firewalls
* Packet Analysis
* Wireshark
* Nmap
* Active Directory
* SIEM Platforms

---

## Lessons Learned

Record major takeaways from completed labs.

Example:

* DNS is more important than I originally realized.
* Enterprise networks are structured differently than home networks.
* Netstat provides visibility into active communication.
* Traceroute helps visualize network paths.

---

## Questions for Future Study

* How does Wireshark capture packets?
* How does Nmap discover devices?
* How does Active Directory manage users?
* How do SOC analysts monitor network traffic?

```
```

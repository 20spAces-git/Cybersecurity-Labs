# Lab 03 - Ping Analysis

## Objective

Test network connectivity to an external host using the ping command and analyze the results.

## Command Used

```bash
ping google.com
```

## Results

Destination Host:

142.250.26.100

Packets Sent:

4

Packets Received:

4

Packets Lost:

0

Minimum Response Time:

13 ms

Maximum Response Time:

14 ms

Average Response Time:

13 ms

## Analysis

The ping test successfully reached Google's servers.

All four packets were transmitted and received successfully, resulting in 0% packet loss.

The successful replies indicate that the system has internet connectivity and can communicate with external hosts.

The response times ranged from 13 ms to 14 ms, indicating a fast and stable network connection.

No connectivity issues were observed during testing.

## Questions

### What protocol does ping use?

Answer:

ICMP (Internet Control Message Protocol)

### What does a successful ping indicate?

Answer:

A successful ping indicates that network connectivity exists between devices.

### What does packet loss mean?

Answer:

Packet loss occurs when packets fail to reach their destination.

### Why is ping useful?

Answer:

Ping is used to test connectivity and troubleshoot network problems.

## What I Learned

* Ping uses ICMP to test network connectivity.
* Successful ping responses indicate that systems can communicate across a network.
* Packet loss can indicate network issues or connectivity problems.
* Response times help measure network performance.

## Cybersecurity Connection

Security analysts and network administrators use ping to verify connectivity, troubleshoot network issues, and determine whether systems are reachable across a network.

Ping can also help identify network outages and connectivity problems during incident investigations.

## Safety Considerations

* Only perform connectivity tests on systems and networks you own or are authorized to access.
* Avoid excessive or automated pinging of external systems.
* Review command output before publishing results to GitHub to remove sensitive information.
* Follow organizational policies and ethical guidelines when performing network diagnostics.

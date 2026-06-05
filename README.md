# Task 5: Capture and Analyze Network Traffic Using Wireshark

## Objective
The objective of this task was to capture live network traffic using Wireshark and analyze different network protocols to understand how devices communicate over a network.

## Tools Used
- Wireshark 4.6.6
- Windows 11
- Wi-Fi Network Interface

## Procedure

1. Installed and launched Wireshark.
2. Selected the active Wi-Fi network interface.
3. Started packet capture.
4. Generated network traffic by browsing websites.
5. Applied protocol filters to isolate specific traffic.
6. Analyzed captured packets and protocol details.
7. Saved the packet capture for future analysis.

## Protocols Analyzed

### DNS (Domain Name System)
DNS packets were captured to observe how domain names are resolved into IP addresses. DNS queries and responses were successfully identified.

### TCP (Transmission Control Protocol)
TCP packets were analyzed to understand reliable communication between devices. Acknowledgments, retransmissions, and connection management were observed.

### TLS (Transport Layer Security)
TLS traffic was captured to examine encrypted communication. TLS packets demonstrated how secure HTTPS connections protect transmitted data.

### QUIC (Quick UDP Internet Connections)
QUIC packets were observed during web browsing activities. QUIC provides faster and secure communication over UDP and is commonly used by modern web applications.

## Observations

- DNS requests and responses were successfully captured.
- TCP packets showed reliable communication mechanisms.
- TLS traffic confirmed encrypted network communication.
- QUIC packets demonstrated modern secure web traffic.
- Packet details such as source address, destination address, protocol type, and packet length were visible through Wireshark.

## Results

The network traffic capture was successful. Multiple protocols were identified and analyzed using protocol-specific filters. The packet inspection process provided practical knowledge of network communication and protocol behavior.

## Conclusion

This task provided hands-on experience with Wireshark and network traffic analysis. It improved understanding of packet structures, protocol functionality, and secure network communications. The activity demonstrated how network monitoring tools can be used to troubleshoot, analyze, and understand network behavior.

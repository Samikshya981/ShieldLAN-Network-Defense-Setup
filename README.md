# ShieldLAN – Basic Network Defense Setup

## Description
ShieldLAN is a basic network defense project created using Cisco Packet Tracer.
It demonstrates secure communication between two LANs using an IPsec VPN tunnel
over an untrusted network.

## Tools Used
- Cisco Packet Tracer
- IPsec VPN
- ACL
- ISAKMP
- Static Routing

## Network Topology
Two LANs are securely connected using a site-to-site IPsec VPN.

## How to Run
1. Open the `.pkt` file in Cisco Packet Tracer
2. Switch to Realtime mode
3. Ping from PC0 to PC1 to activate the VPN
4. Verify using:
   - show crypto isakmp sa
   - show crypto ipsec sa


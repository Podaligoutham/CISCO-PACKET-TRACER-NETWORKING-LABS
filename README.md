# Lab 01 – Basic LAN & Ping

## Objective

Build a basic LAN using a Cisco 2960 switch and two PCs.

## Topology

PC0 → Switch → PC1

## IP Addressing

| Device | IP Address   | Subnet Mask   |
| ------ | ------------ | ------------- |
| PC0    | 192.168.1.10 | 255.255.255.0 |
| PC1    | 192.168.1.20 | 255.255.255.0 |

## Verification

* `ping 192.168.1.20`
* `show mac address-table`
* `show interfaces status`

## Expected Result

PC0 should successfully ping PC1.

## Troubleshooting

Disconnected the PC0-to-switch cable and verified that connectivity failed. Reconnected the cable and restored connectivity.

## What I Learned

* IPv4 addressing
* Subnet masks
* Switch connectivity
* MAC address learning
* Basic troubleshooting

## Tools

Cisco Packet Tracer

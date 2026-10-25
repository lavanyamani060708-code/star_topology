# Star Topology Using Cisco Packet Tracer

## Aim
To design and simulate a Star Topology network using Cisco Packet Tracer and test communication between connected computers.

## Software Required
- Cisco Packet Tracer

## Devices Used
- 4 PCs
- 1 Cisco 2960 Switch
- Copper Straight-Through cables

## Network Topology
In Star Topology, all computers are connected to a central switch. The switch helps devices communicate within the local area network (LAN).

## IP Address Configuration

| Device | IP Address | Subnet Mask |
|---|---|---|
| PC0 | 192.168.1.1 | 255.255.255.0 |
| PC1 | 192.168.1.2 | 255.255.255.0 |
| PC2 | 192.168.1.3 | 255.255.255.0 |
| PC3 | 192.168.1.4 | 255.255.255.0 |

## Procedure
1. Open Cisco Packet Tracer.
2. Place four PCs and one Cisco 2960 switch in the workspace.
3. Connect each PC to a separate switch port using Copper Straight-Through cables.
4. Configure the IP address and subnet mask for each PC.
5. Open the Command Prompt on a PC.
6. Use the `ping` command to test communication with the other PCs.

## Testing
Example command from PC0:

`ping 192.168.1.2`

Repeat the ping test for PC2 and PC3 using their IP addresses.

## Advantages
- Easy to install and manage.
- Failure of one PC cable generally does not affect other PCs.
- Faults are easier to identify.

## Result
A Star Topology network was configured using Cisco Packet Tracer. Communication between PCs was tested using the ping command.

## Project File
`star_topology.pkt`

## Author
GitHub: [lavanyamani060708-code](https://github.com/lavanyamani060708-code)

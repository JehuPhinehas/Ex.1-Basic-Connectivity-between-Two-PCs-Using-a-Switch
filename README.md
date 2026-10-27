## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 		25.10.2026

# Objective

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required
•	Cisco Packet Tracer Software
•	Devices: PCs, Switch, Router, Cables
•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram

<img width="1917" height="1198" alt="image" src="https://github.com/user-attachments/assets/da6705da-e9f0-4f47-8a66-3788c68bf787" />


________________________________________
# IP Addressing Table (if applicable)
Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure
Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results)
-PC0 configuration image:

<img width="1917" height="1198" alt="image" src="https://github.com/user-attachments/assets/1e694c4d-ed8e-448f-8106-be898308736c" />


-Switch configuration image:

<img width="1917" height="1198" alt="image" src="https://github.com/user-attachments/assets/868cf069-9e90-4ce9-976f-f82bd3042078" />

-ping successfull image:

<img width="1917" height="1198" alt="image" src="https://github.com/user-attachments/assets/2c9fe270-6b5b-4839-924f-19960ab00e66" />


Insert screenshots showing ping success, configuration, or simulation results.
________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	

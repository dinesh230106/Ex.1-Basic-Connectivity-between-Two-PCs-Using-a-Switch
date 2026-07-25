## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 23/07/2026 		

# Objective

To configure and test basic LAN connectivity between two PCs using a switch.

# Apparatus/Tools Required
•	Cisco Packet Tracer Software

•	Devices: PCs, Switch, Router, Cables

•	Optional: Wireless Router, Server, Cloud

# Network Topology Diagram

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6998a12c-8b7c-4095-9ee5-30e349ffa8ca" />


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
<img width="1920" height="1080" alt="Screenshot (70)" src="https://github.com/user-attachments/assets/28919a75-3425-4c6f-86f5-fe3c34b97e98" />


<img width="1920" height="1080" alt="Screenshot (71)" src="https://github.com/user-attachments/assets/6854ad14-81f2-4def-ae0e-e17285db2878" />


<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/61c7246a-9512-4eca-889d-fc462497c417" />

________________________________________
# Result
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	

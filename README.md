# Networking-Engineering project using Cisco Packet Tracer
#### This project is creating network for Student Central Department: 4 areas (Student Service Area, Information Counter Area, Wireless Zone Area, Staff Area).
##### Network Structure
###### Four areas with specific roles:
Student Service: 1 router, 2 switches, 4 PCs, 2 printers.
Information Counter: 1 router, 2 switches, 4 PCs, 2 printers.
Wireless Zone: Separate SSIDs for staff and students, 1 router, 1 switch, 2 access points.
Staff Area: 1 router, 1 switch, 4 PCs, 1 printer, DNS server.
##### Key Features
Redundancies: Router links for fault tolerance and load balancing.
Routing: Static IPv4 and IPv6 routes; DHCP in Wireless Zone.
Security: Console and enable passwords.
##### IP Addressing:
IPv4: 110.130.72.0/24 – 110.130.79.255
IPv6: 2001:ABCD:5:51::/64
##### Connectivity: 
Staff Area has external WWW access; DNS server in Staff Area supports IPv4/IPv6 resolution.

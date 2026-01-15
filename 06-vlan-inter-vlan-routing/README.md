VLAN and Inter-VLAN Routing Lab

1. Configured correct IP address and subnet mask on each PC
   - Gateway set as the LAST usable IP address of each subnet

2. Created three connections between R1 and SW1
   - Configured one router interface (sub-interface) per VLAN
   - Router IPs match the gateway addresses configured on PCs

3. Configured VLANs on SW1
   - VLANs created and named:
     - Engineering
     - HR
     - Sales
   - Switch ports assigned to correct VLANs
   - Interfaces connected to R1 configured properly

4. Verified connectivity
   - Successful ping between PCs in different VLANs
   - Broadcast ping tested using Packet Tracer Simulation Mode
   - Observed which devices received the broadcast

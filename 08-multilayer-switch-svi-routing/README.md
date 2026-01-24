Multilayer Switch (SVI) and Layer 3 Routing Lab

Initial State:
- Hosts already assigned to correct VLANs
- SW1 and SW2 connected via trunk
- R1 and SW2 previously connected using Router-on-a-Stick
- SW2 replaced with a multilayer switch

1. Replaced Router-on-a-Stick with a point-to-point Layer 3 connection
   - Removed ROAS configuration between R1 and SW2
   - Configured a Layer 3 routed interface between R1 and SW2
   - Assigned IP addresses according to the network diagram
   - Configured a default route on SW2 pointing to R1 G0/0

2. Configured Switch Virtual Interfaces (SVIs) on SW2
   - One SVI created per VLAN
   - Assigned the LAST usable IP address of each subnet to the corresponding SVI
   - Enabled IP routing on the multilayer switch

3. Verified inter-VLAN connectivity
   - Successful ping between hosts in different VLANs

4. Verified Internet connectivity
   - Successfully pinged 1.1.1.1
   - Confirmed routing through R1 to the Internet router

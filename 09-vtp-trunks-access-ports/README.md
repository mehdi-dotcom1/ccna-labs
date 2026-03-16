VTP, Trunks, and VLAN Access Ports Lab

1. Configured trunk ports between switches
   - Disabled DTP on trunk interfaces
   - Verified administrative and operational modes

2. Configured SW1 in VTP domain "CCNA"
   - Created VLANs 10, 20, 30
   - Verified VLAN propagation to SW2 and SW3

3. Configured SW2 in VTP transparent mode
   - Added VLAN40 on SW2
   - Verified VLAN40 does NOT propagate to SW1 or SW3

4. Configured SW3 in VTP client mode
   - Attempted to create VLAN50 on SW3
   - Verified VLAN50 was NOT added (VTP client cannot create VLANs)

5. Configured switchports connecting to hosts as access ports
   - Manually assigned correct VLANs
   - Verified DTP is disabled on host-facing ports

6. Verified connectivity between VLAN hosts where applicable

VLAN, Trunking, and Router-on-a-Stick Lab

1. Configured switch interfaces connected to PCs as access ports
   - Each port assigned to the correct VLAN

2. Configured trunk link between SW1 and SW2
   - Allowed only required VLANs on the trunk
   - Configured an unused VLAN as the native VLAN
   - Verified that all required VLANs exist on both switches

3. Configured Router-on-a-Stick between SW2 and R1
   - Created sub-interfaces on R1 for each VLAN
   - Assigned the LAST usable IP address of each subnet to R1 sub-interfaces
   - Enabled 802.1Q encapsulation

4. Verified connectivity
   - Successful ping between all PCs across different VLANs

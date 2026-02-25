# Lab 08: DHCP on Router for Multiple VLANs

## Objective
Configure a router to provide DHCP services for multiple VLANs.

## Topology
![Topology](topology.png)

## VLANs
- VLAN 10 (SALES)
- VLAN 20 (IT)

## DHCP Design
- VLAN 10: 192.168.10.0/24
- VLAN 20: 192.168.20.0/24

## Configuration Summary

### Router
- DHCP pools created for VLAN 10 and VLAN 20
- Excluded gateway IPs
- DNS server configured

### Switch
- VLANs and trunking are configured

## Verification
- PCs successfully obtain IP addresses via DHCP
- Inter-VLAN communication successful

## Lessons Learned
- DHCP can be centralized on a router
- VLANs require separate DHCP scopes

## Full Documentation
👉 [Google Drive – Lab 08 Documentation](https://drive.google.com/file/d/1JeHrm6y3O3rTS8SxUF--7YYIhSn0M8CU/view?usp=sharing)

# Law Office Network — Cisco Routing, VLAN & Security Lab

A realistic small-office network lab built in Cisco Packet Tracer to practice
VLAN segmentation, Layer 3 routing, DHCP, IP telephony, static routing,
and ACL-based network security.

##  Objectives

- Segment departments using VLANs
- Configure Inter-VLAN Routing using a Layer 3 Switch
- Provide DHCP services for each VLAN
- Configure Voice VLAN for IP Phones
- Configure Cisco CME for IP telephony
- Configure static routing between network devices
- Restrict Guest VLAN access using Extended ACLs
- Troubleshoot connectivity issues layer-by-layer

---

##  VLAN Design

| VLAN | Name | Network | Gateway |
|------|------|---------|---------|
| 10 | ATTORNEYS | 192.168.10.0/24 | 192.168.10.1 |
| 20 | PARALEGAL | 192.168.20.0/24 | 192.168.20.1 |
| 30 | RECEPTION | 192.168.30.0/24 | 192.168.30.1 |
| 40 | PRINTER | 192.168.40.0/24 | 192.168.40.1 |
| 50 | GUEST-WIFI | 192.168.50.0/24 | 192.168.50.1 |
| 60 | VOICE | 192.168.60.0/24 | 192.168.60.1 |
| 99 | MANAGEMENT | 192.168.99.0/24 | 192.168.99.1 |

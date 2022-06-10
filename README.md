# NETPLAN
Command-line network configuration utility

########## MODIFICAR NETPLAN ##############

```
#nano /etc/netplan/01-network-manager-all.yaml 
```
-------------- Archivo 01-network-manager-all.yaml ---------------------

```
#network:
#version: 2
#renderer: NetworkManager

network:
 version: 2
 renderer: networkd
 ethernets:
   lo:
     dhcp4: false
     optional: false
     addresses:
        - 127.0.0.1/8
        - x.x.x.21/24
   enp2s0:
     dhcp4: true
     dhcp6: false
     optional: false
 #addresses:
 #- x.x.x.7/24

   xdxdxdxdxdxdxd:
     dhcp4: true

```

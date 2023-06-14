# VLANs, Trunks, and QinQ

## Virtual Local Area Network (VLAN)

VLANs are a type of network technology that allow us to create multiple virtual networks within a single physical network.

This can allow us to separate traffic based on logical groupings such as department, purpose, or security level without the need for physical separation.

VLANs are commonly used to improve network performance, security, and manageability.

## Trunks

Trunks are connections between network switches that allow multiple VLANs to be carried over a single physical link.

In other words, instead of requiring a separate physical cable for each VLAN, the traffic for all of the VLANs can be sent across one cable.

## QinQ

QinQ is a VLAN stacking technique that allows multiple VLAN tags to be added to a single Ethernet frame. QinQ is useful for when we need to extend VLANs across multiple networks or service providers.

As far as AWS is concerned, QinQ is a VLAN stacking/tagging technique that can be used with AWS Direct Connect to extends VLANs across on-premises data centers and AWS environments, making it easier to reduce costs and manage network traffic.

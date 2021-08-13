#### MAC Address Device Identification for Network and Application Services (MADINAS) Charter
##### The Medium Access Control (MAC) address is the Link Layer address used in IEEE 802 technologies. It was originally assigned statically for each physical network card by the Network Interface Card manufacturer, out of the space reserved by the IEEE Registration Authority Committee (RAC) for globally unique MAC addresses. The MAC address is used as source or destination target when sending and receiving frames. The default static assignment of the MAC address raises privacy concerns for personal devices, which have recently started to be mitigated by end-device vendors implementing and SDOs specifying the use of Randomized and Changing MAC addresses (RCM).

##### Device identity is important in scenarios where the network needs to know the device or user identity in order to offer, operate and maintain certain services. Currently, many use cases and applications make an implicit assumption about the unique association between the device identity and its MAC address. This assumption is being used in both control plane and data plane functions and protocols. RCM breaks this assumption. This requires updating applications to function across MAC address changes.

##### The MADINAS Working Group will document the current RCM state of the affairs and examine network and application use cases that would be impacted by RCM. The group will also evaluate existing solutions that may provide identifiers (i.e., beyond the MAC address) in various scenarios where application and network can use them instead of MAC address. 

##### The Working Group will work together with other IETF WGs (e.g., DHC, IntArea), and will liaise with other relevant SDOs such as IEEE 802 and the Wireless Broadband Alliance (WBA). The Working Group will coordinate on the different recommendations, as well as potential follow-up activities within or outside the IETF.

- Document Current State of Affairs:
##### An Informational Use Cases and Requirements document (e.g. draft-henry-madinas-framework)

##### Expected deliverables/milestones:
##### 1. An Informational Problem Statement document, including use cases analysis and requirements. 
     - An Informational Use Cases and Requirements document (e.g. draft-henry-madinas-framework)
     - An Informational MAC Address Randomization current state-of-affairs document (e.g. draft-zuniga-mac-address-randomization)

##### 2. Document Best Practices handling RCM
    - A Best Common Practices document




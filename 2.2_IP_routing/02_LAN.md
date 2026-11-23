
# 2. Part B — Configuring the LAN

## 2.1 Static IP Configuration
### Pi A (192.168.50.1)
<img width="1600" height="900" alt="pi A" src="https://github.com/user-attachments/assets/de3d4e6c-38e0-4653-92e7-72d24c28be4d" />


### Pi B (192.168.50.2)

<img width="1600" height="900" alt="pi B" src="https://github.com/user-attachments/assets/4ec45a28-f549-4fcb-ba3b-fb076e6dd963" />


## 2.2 Explanation
Explain:
- What is a static IP address?  
- Why both devices cannot use the same address  
- Why we use /24

A static IP address is an IP address that is manually assigned to a device and does not change automatically.

Both devices cannot use the same IP address because it would create an IP address conflict. This can cause communication problems between devices on the network.

We use /24 because it represents the subnet mask 255.255.255.0. It means the first 24 bits identify the network, while the remaining 8 bits are used for device addresses. This allows devices in the same network to communicate with each other.

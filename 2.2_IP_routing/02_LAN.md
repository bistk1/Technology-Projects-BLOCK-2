
# 2. Part B — Configuring the LAN

## 2.1 Static IP Configuration
### Pi A (192.168.50.1)

<img width="4000" height="2252" alt="rapsberry pi-A" src="https://github.com/user-attachments/assets/451a3874-2ad6-499e-af85-4d0db84e2ea6" />


### Pi B (192.168.50.2)

<img width="4000" height="2252" alt="IMG-20261108-WA0019" src="https://github.com/user-attachments/assets/630a37e2-e1fc-4342-bc05-b3115f235c68" />


## 2.2 Explanation
Explain:
- What is a static IP address?

- A static IP address is an IP address that is manually assigned to a device. It does not normally change automatically, so the device can keep using the same address on the network.

- 
- Why both devices cannot use the same address

- Both devices cannot use the same IP address because it would create an IP address conflict. The network would not be able to identify the correct device properly, which could cause connection problems.

- 
- Why we use /24

We use /24 because it represents the subnet mask 255.255.255.0. It means the first 24 bits are used for the network part, while the remaining 8 bits are used for device addresses. This allows both Raspberry Pis to communicate on the same local network.

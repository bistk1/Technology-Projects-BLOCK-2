

## 🔍 5. Testing & Verification

### 5.1 Ping Tests  
Did the PC successfully ping a DNS name (e.g., `library_pc1`)?  
Explain the result.
The PC successfully pinged the DNS name library_pc1. The ping test confirmed that the PC could communicate with the destination using its hostname. The successful replies showed that the network connection was working.

📸 **Screenshot of successful ping**

<img width="389" height="135" alt="connectivity" src="https://github.com/user-attachments/assets/af17871a-d6c9-4c78-bb62-9d6ed631b10d" />
<img width="1919" height="1032" alt="network2-102-100" src="https://github.com/user-attachments/assets/75c2d5fd-bf29-4c5b-908b-449686dd187b" />
<img width="650" height="304" alt="network2" src="https://github.com/user-attachments/assets/0dc2b34a-33e8-43d9-a053-995578219c04" />


### 5.2 DNS Resolution  
Describe whether DNS resolved the hostname correctly.

The DNS server successfully resolved the hostname into its corresponding IP address. This confirmed that the DNS service and name records were configured correctly.

### 5.3 DHCP Lease Verification  
Describe the IPs assigned to each PC.  
Do they match the DHCP pool?
All PCs received their IP addresses automatically from the DHCP server. Each PC received an IP address from the configured DHCP pool, along with the correct subnet mask, default gateway and DNS server. The assigned addresses matched the DHCP pool range.

📸 **Screenshot: `ipconfig /all`**

<img width="960" height="540" alt="ipconfig pc5" src="https://github.com/user-attachments/assets/9a31f2ba-8107-40c6-9e0e-16ae7ce68512" />
<img width="960" height="540" alt="ipconfig pc7" src="https://github.com/user-attachments/assets/3c14457f-817d-486c-91d5-e2b8594337cb" />
<img width="960" height="540" alt="ipconfigpc6" src="https://github.com/user-attachments/assets/d640f67e-6cb9-4275-9045-81aecec6b265" />

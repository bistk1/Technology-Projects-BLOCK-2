

## 🔍 5. Testing & Verification

### 5.1 Ping Tests  
Did the PC successfully ping a DNS name (e.g., `library_pc1`)?  
Explain the result.

I used the ping command to test the connection between the PCs and the DNS name pc6. The ping was successful, which means the network connection was working properly and the PC could communicate with the destination.

📸 **Screenshot of successful ping**

<img width="650" height="304" alt="network2" src="https://github.com/user-attachments/assets/c7a7aa1c-dcd7-4eb2-97a7-22b468150085" />
<img width="1919" height="1032" alt="network2-102-100" src="https://github.com/user-attachments/assets/d2953eec-64a7-41fe-b2dc-bcd6c424834b" />


### 5.2 DNS Resolution  
Describe whether DNS resolved the hostname correctly.

The DNS service successfully resolved the hostname pc6 into its correct IP address. This showed that the DNS configuration was working correctly and I could use the hostname instead of typing the IP address.

### 5.3 DHCP Lease Verification  
Describe the IPs assigned to each PC.  
Do they match the DHCP pool?

I used the ipconfig /all command to check the IP addresses assigned to each PC. The PCs received their network settings automatically from the DHCP server. The assigned IP addresses were within the configured DHCP pool range, which confirmed that DHCP was working correctly.

📸 **Screenshot: `ipconfig /all`**
<img width="960" height="540" alt="ipconfig pc5" src="https://github.com/user-attachments/assets/30ea1459-437c-4a96-bbb1-d3315a6006e9" />
<img width="960" height="540" alt="ipconfigpc6" src="https://github.com/user-attachments/assets/f1cd93e1-723a-42eb-93c7-81dfca134f56" />
<img width="960" height="540" alt="ipconfig pc7" src="https://github.com/user-attachments/assets/4ae8dd73-508b-4eed-a730-b5e72f9a73da" />


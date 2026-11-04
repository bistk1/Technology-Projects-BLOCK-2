
## 🛠️ 3. Server Configuration (DHCP + DNS)

### 3.1 Static IP Settings  
Describe how you configured the server's static IP.

I set a static IP address in Packet Tracer's IP Configuration option. I manually set the address, subnet mask, and default gateway. I set the IP to be static because I want the server to have an IP that doesn't change, so the clients can find the server to communicate with it easily.

📸 **Screenshot: Server IP configuration**

<img width="960" height="540" alt="server ip configuration" src="https://github.com/user-attachments/assets/b01d6c5b-b54c-4168-b954-c767f58de29a" />


### 3.2 DHCP Configuration  
Describe the DHCP pool you created (gateway, DNS, start IP, etc).

I turned on the DHCP service on the server and made a DHCP pool for the client devices. I entered the default gateway, DNS server address and starting IP address in the pool settings. I did not have to manually assign IP addresses to the client PCs since the DHCP service does that automatically.


📸 **Screenshot: DHCP settings**


<img width="960" height="540" alt="DHCP configuration" src="https://github.com/user-attachments/assets/d58ddba9-82b3-4dcc-828b-a99f849118d3" />


### 3.3 DNS Configuration  
Explain how you enabled DNS and created name records.

I added a Name Record with a domain name and its IP address. I have enabled the DNS service on my server. This record allows client computers to reference names rather than remembering IP addresses. This record helped me to understand how the DNS translates a name to an IP address.
  
📸 **Screenshot: DNS service + name entries**


<img width="960" height="540" alt="DNS name" src="https://github.com/user-attachments/assets/f8b91b56-b116-4225-ab8e-608a0db2c75e" />


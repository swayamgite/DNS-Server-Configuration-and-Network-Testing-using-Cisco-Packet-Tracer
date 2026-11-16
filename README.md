DNS Configuration Using Cisco Packet Tracer

Objective

- To configure DNS (Domain Name System) in Cisco Packet Tracer.
- To translate domain names into IP addresses within a local network.
- To allow client PCs to access network services using domain names instead of IP addresses.
- To configure IP addresses on the DNS server and client computers.
- To verify that DNS name resolution works correctly from all client devices.

Requirements

- Cisco Packet Tracer software
- 1 Switch
- 1 Server (configured as DNS Server)
- 2 PCs (PC0 and PC1)
- Copper Straight-Through Ethernet cables
- Configured IP network (network address and subnet mask)
- DNS service enabled on the server
- DNS records configured on the DNS server
- DNS server IP address configured on all client PCs

Step 1: Connect the Devices

Open Cisco Packet Tracer.

Drag and place the following devices into the workspace:

- 1 Switch
- 1 Server (DNS Server)
- 2 PCs (PC0 and PC1)

Connect all devices using Copper Straight-Through cables:

- Server0 to Switch
- PC0 to Switch
- PC1 to Switch

Wait until all device connections turn green, indicating that the network links are active.

This creates the basic network topology required for DNS configuration and communication between the server and client computers.

Screenshot:

"Network Topology" (./01-Network-Topology.png)

Step 2: Configure DNS Service

After connecting all devices, the next step is to configure the DNS service on the server.

- Click on Server0 to open the server configuration window.
- Select the Services tab.
- From the list of available services on the left panel, click DNS.
- Make sure that the DNS Service is set to ON.

Enabling the DNS service allows the server to translate domain names into their corresponding IP addresses.

Screenshot:

"DNS Service" (./02-DNS-Service.jpg)

Step 3: Configure DNS Records

After enabling the DNS service, configure the DNS records on the server.

- Open the Server configuration window.
- Select the Services tab.
- Click DNS from the left panel.
- Enter the required domain name in the Name field.
- Enter the corresponding server IP address in the Address field.
- Click Add to save the DNS record.

A DNS record maps a domain name to its corresponding IP address. This allows client computers to access network resources using domain names instead of IP addresses.

Screenshot:

"DNS Service Configuration" (./03-DNS-Service-Configuration.jpg)

Step 4: Configure IP Address on PC0

After configuring the DNS service, assign an IP address to PC0.

- Click on PC0.
- Open the Desktop tab.
- Select IP Configuration.
- Select Static configuration.
- Enter the following IP settings:

Setting| Value
IP Address| 192.168.1.11
Subnet Mask| 255.255.255.0
Default Gateway| 0.0.0.0
DNS Server| 192.168.1.10

This configuration assigns a static IP address to PC0 and sets the DNS server address to 192.168.1.10.

It allows PC0 to communicate with the DNS server and perform domain name resolution.

Screenshot:

"PC0 IP Configuration" (./04-PC0-IP.jpg)

Step 5: Configure IP Address on PC1

After configuring PC0, the next step is to assign an IP address to PC1.

- Click on PC1.
- Open the Desktop tab.
- Select IP Configuration.
- Select Static configuration.
- Enter the following IP settings:

Setting| Value
IP Address| 192.168.1.12
Subnet Mask| 255.255.255.0
Default Gateway| 0.0.0.0
DNS Server| 192.168.1.10

This configuration assigns a static IP address to PC1 and sets 192.168.1.10 as the DNS server.

It allows PC1 to communicate with the DNS server and resolve domain names.

Screenshot:

"PC1 IP Configuration" (./05-PC1-IP.jpg)

Step 6: Configure IP Address on the Server

After configuring the client PCs, assign a static IP address to the DNS server.

- Click on Server0.
- Open the Desktop tab.
- Select IP Configuration.
- Select Static configuration.
- Enter the following IP settings:

Setting| Value
IP Address| 192.168.1.10
Subnet Mask| 255.255.255.0
Default Gateway| 0.0.0.0
DNS Server| 192.168.1.10

This configuration assigns the IP address 192.168.1.10 to the DNS server.

The server uses its own IP address as the DNS server address to provide DNS services to client computers.

Screenshot:

"Server IP Configuration" (./06-Server-IP.jpg)

Step 7: Verify DNS Configuration on PC0

After configuring the IP addresses and DNS settings, verify that DNS name resolution is working correctly on PC0.

- Click on PC0.
- Open the Desktop tab.
- Select the DNS testing option used in the configuration.
- Perform DNS testing using the configured domain name.
- Check the result to verify DNS name resolution.

This step verifies whether PC0 can successfully communicate with the DNS server and resolve the configured domain name.

Screenshot:

"PC0 DNS Testing" (./07-PC0-DNS-Test.jpg)

Step 8: Verify DNS Configuration on PC1

After successfully testing DNS on PC0, perform DNS testing on PC1.

- Click on PC1.
- Open the Desktop tab.
- Select the DNS testing option used in the configuration.
- Perform DNS testing using the configured domain name.
- Check the result to verify DNS name resolution.

This confirms that PC1 can also communicate with the DNS server and resolve the configured domain name.

Screenshot:

"PC1 DNS Testing" (./08-PC1-DNS-Test.jpg)

Result

The DNS configuration was implemented using Cisco Packet Tracer.

The network topology was created, DNS service was enabled, and IP addresses were assigned to the server and client computers.

The DNS server was configured with IP address 192.168.1.10.

Both client computers were configured with the following IP settings:

- PC0: 192.168.1.11
- PC1: 192.168.1.12
- DNS Server: 192.168.1.10
- Subnet Mask: 255.255.255.0

DNS testing was performed from both PC0 and PC1 to verify the DNS configuration.

Conclusion

The DNS Configuration project was completed using Cisco Packet Tracer.

This project demonstrated how DNS translates domain names into IP addresses and helps client computers communicate with servers using domain names.

Through this practical implementation, I gained knowledge of DNS service configuration, IP addressing, DNS records, network topology creation, and client-server communication.

Author

Swayam Gite

Cyber Security Student

DNS Server Configuration and Network Testing using Cisco Packet Tracer

📌 Project Overview

This project demonstrates the configuration and testing of a DNS (Domain Name System) Server using Cisco Packet Tracer.

The main purpose of this project is to understand how DNS translates domain names into IP addresses and allows client computers to communicate with servers using domain names.

🎯 Objectives

- To create a network topology using Cisco Packet Tracer.
- To configure a DNS Server.
- To enable and configure DNS services.
- To assign IP addresses to server and client PCs.
- To configure DNS settings on client computers.
- To test DNS name resolution from multiple client devices.

🛠️ Requirements

- Cisco Packet Tracer
- 1 Switch
- 1 Server (DNS Server)
- 2 PCs (Clients)
- Copper Straight-Through Cables
- IP Address Configuration
- DNS Service

Step 1: Create Network Topology

Open Cisco Packet Tracer and create a network topology using one switch, one server, and two client PCs.

Connect all devices using Copper Straight-Through cables.

This topology provides the network infrastructure required for DNS communication between the server and client computers.

Network Topology Screenshot:

"Network Topology" (./01-Network-Topology.png)

Step 2: Configure DNS Service

Click on the Server and open the Services tab.

Select DNS from the left panel and enable the DNS Service.

DNS service allows client computers to resolve domain names into their corresponding IP addresses.

DNS Service Screenshot:

"DNS Service" (./02-DNS-Service.jpg)

Step 3: Configure DNS Records

Configure the DNS records on the server by entering the required domain name and corresponding IP address.

Click Add to save the DNS record.

DNS records help client computers identify the IP address associated with a domain name.

DNS Configuration Screenshot:

"DNS Configuration" (./03-DNS-Service-Configuration.jpg)

Step 4: Configure IP Address on PC0

Click on PC0 and open the Desktop tab.

Select IP Configuration and assign the required IP address, subnet mask, and DNS server address.

This configuration allows PC0 to communicate with the DNS server and perform domain name resolution.

PC0 IP Configuration Screenshot:

"PC0 IP Configuration" (./04-PC0-IP.jpg)

Step 5: Configure IP Address on PC1

Click on PC1 and open the Desktop tab.

Select IP Configuration and configure the required IP address, subnet mask, and DNS server address.

This allows PC1 to communicate with the DNS server and access network resources using domain names.

PC1 IP Configuration Screenshot:

"PC1 IP Configuration" (./05-PC1-IP.jpg)

Step 6: Configure IP Address on DNS Server

Click on the Server and open the Desktop tab.

Select IP Configuration and assign the required IP address and subnet mask.

Configure the DNS server settings to enable proper communication between the server and client devices.

Server IP Configuration Screenshot:

"Server IP Configuration" (./06-Server-IP.jpg)

Step 7: Verify DNS Configuration on PC0

Open PC0 and perform DNS testing using the configured domain name.

Check whether PC0 can successfully communicate with the DNS server and resolve the domain name.

This step verifies the DNS configuration on the first client computer.

PC0 DNS Testing Screenshot:

"PC0 DNS Testing" (./07-PC0-DNS-Test.jpg)

Step 8: Verify DNS Configuration on PC1

Open PC1 and perform DNS testing using the configured domain name.

Check whether PC1 can successfully resolve the domain name through the DNS server.

This confirms DNS communication from the second client computer.

PC1 DNS Testing Screenshot:

"PC1 DNS Testing" (./08-PC1-DNS-Test.jpg)

✅ Result

The DNS Server was configured successfully using Cisco Packet Tracer.

IP configurations were assigned to the server and client computers. DNS service was enabled and DNS testing was performed from both PC0 and PC1.

📚 Conclusion

This project helped me understand DNS server configuration, IP addressing, DNS records, and domain name resolution.

It also provided practical knowledge of network topology creation and client-server communication using Cisco Packet Tracer.

👨‍💻 Author

Swayam Gite

Cyber Security Student

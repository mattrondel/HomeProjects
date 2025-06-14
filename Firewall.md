**What Firewalls Do**

Firewalls are network security devices that monitor and control incoming and outgoing network traffic based on predetermined security rules. They act as a barrier between trusted internal networks and untrusted external networks like the internet.

**Types of Firewalls**

Packet Filtering Firewalls: Examine individual packets and make decisions based on IP addresses, ports, and protocols. Fast but limited in scope.

Stateful Inspection Firewalls: Track the state of active connections and make decisions based on connection context, not just individual packets. More secure than packet filtering.

Application Layer Firewalls (Proxy Firewalls): Operate at the application layer, inspecting the actual content of communications. Can understand specific protocols like HTTP, FTP, or SMTP.

Next-Generation Firewalls (NGFW): Combine traditional firewall capabilities with additional features like intrusion prevention, application awareness, and deep packet inspection.

**Deployment Models**

**Network Firewalls**: Deployed at network perimeters to control traffic between networks.

**Host-Based Firewalls**: Software running on individual devices to control traffic to/from that specific host.

**Cloud Firewalls**: Virtual firewalls deployed in cloud environments, often called Web Application Firewalls (WAF) when protecting web applications.

**Key Concepts**

**Default Deny**: Best practice where everything is blocked by default, and only explicitly allowed traffic passes through.

**DMZ (Demilitarized Zone)**: Network segment that sits between internal and external networks, typically hosting public-facing servers.

**Rule Processing**: Firewalls process rules in order, so rule placement matters. Most specific rules should come first.

**Common Configurations**

- Inbound rules typically block most traffic except specific services

- Outbound rules may be more permissive but should still be controlled

- Port-based filtering (blocking unused ports)

- Protocol restrictions (allowing only necessary protocols)


**Limitations**

Firewalls can't protect against insider threats, malware that uses allowed protocols, or attacks that bypass the network perimeter. 

They're one component of defense-in-depth strategy, not a complete security solution.

Understanding that modern security requires multiple layers beyond just perimeter firewalls shows you grasp current cybersecurity thinking.

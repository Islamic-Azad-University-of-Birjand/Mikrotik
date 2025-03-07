## What is **MikroTik**?

**MikroTik** is the name of a company that produces products related to computer networking.

**MikroTik** is based on Linux and, when installed on dedicated hardware like RouterBOARD or **x86-based** computers, turns the hardware into a network router with the same features. The company initially focused on writing software for 32-bit computer hardware but gradually shifted towards producing networking products.

---
## Applications and **Advantages** of MikroTik Routers:

You might be wondering where **MikroTik** is used! Let me explain:

- **Routing**

Routing with **MikroTik** is easier and faster.

- **Firewall**

MikroTik also includes a firewall feature, allowing you to restrict incoming and outgoing network ports, which enhances network security.

- **[DHCP Server](./DHCP.md)**

With **DHCP servers**, you can assign a unique IP address to each system. **MikroTik routers** support this capability.

- **Wireless**

Various wireless technologies are supported by MikroTik, and I recommend exploring this feature.

- **Load Balancing**

A **load balancer** helps maintain network stability, allowing you to use two internet service networks simultaneously. By connecting a second internet service to the network, it prevents internet outages and interruptions.

- **VPN (Virtual Private Network)**

The **MikroTik operating system** uses various VPN methods to create secure connections.

- **MikroTik Hot Spot Gateway**

This feature allows for public network connections without the need for software installation or network configuration. With hot spot gateways, you can set up a login and authentication page for each separate network, providing better management of users at the network level.

- **[MPLS](./MPLS.md) (Multi Protocol Label Switching)**

MPLS is a technique that replaces traditional IP addressing methods for fast routing and shaping traffic flows in the network.

## What are the **Disadvantages** of MikroTik?

In general, MikroTik routers do not have significant issues, but it is important to note that:

- MikroTik devices are not **up-gradable**.

---
## **VPN** Protocols

Over the years, VPN leaders have developed and used a variety of protocols, each of which has unique benefits and disadvantages. The five most widely used protocols right now are:

- **OpenVPN** is an open-source VPN released in 20011 that has continually improved since. Now the gold standard of VPN protocols, it’s compatible with cutting-edge encryption standards and provides fast and reliable speeds.  
  
- **WireGuard** is much newer, released in 2015. It’s comparable to OpenVPN in terms of security and encryption, but many consider it faster and more reliable. VPN providers that build their own proprietary protocols tend to use WireGuard as the basis.
  
- **IKEv2** is often paired with IPSec (Internet Protocol Security) to create a secure VPN tunnel. IKEv2/IPSec is lightweight and adequately secure. It’s also agile, since it’s one of the few protocols that can re-establish a VPN connection when you switch networks (e.g. from mobile data to Wi-Fi).
  
- **L2TP**, much like IKEv2, is often paired with IPSec. It was developed in the 1990s by Cisco and Microsoft, and it was considered secure at the time. It still has zero known vulnerabilities, but many people believe it’s no longer safe from government spying, especially by the NSA.2
  
- **PPTP** is the oldest VPN protocol to become widely available, and many people see it as obsolete in terms of security. It’s fast and can still provide adequate privacy, however, albeit with a lower encryption standard.

--- 

- [ ] 0: Intro of the MikroTik (**T**)

- [ ] 1 : what is VPN && VPN for ? && protocols 
- Protocols models 
	- types 
	- examples
	- **pros** and **cons** (Advantages & Disadvantages)

- [ ] 3: In the end 
	- Real Examples
	- Web server && DNS server 
	
  
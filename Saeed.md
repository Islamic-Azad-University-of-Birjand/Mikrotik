## What is Vpn ?

	VPN stands for "Virtual Private Network"
	VPNs encrypt your internet traffic and disguise your online identity 
	The encryption takes place in *real time*

##  How does a VPN work?
	A VPN hides your IP address by letting the network redirect it through a specially configured remote server run by a VPN host
	This means your Internet Service Provider (ISP) and other third parties cannot see which websites you visit or what data you send and receive online.

**Secure encryption:** To read the data, you need an _encryption key_ . Without one, it would take millions of years for a computer to decipher the code in the event of a [brute force attack](https://www.kaspersky.com/resource-center/definitions/brute-force-attack) . With the help of a VPN, your online activities are hidden even on public networks.

**Disguising your whereabouts** : VPN servers essentially act as your proxies on the internet. Because the demographic location data comes from a server in another country, your actual location cannot be determined. In addition, most VPN services do not store logs of your activities. Some providers, on the other hand, record your behavior, but do not pass this information on to third parties. This means that any potential record of your user behavior remains permanently hidden.

**Access to regional content:** Regional web content is not always accessible from everywhere. Services and websites often contain content that can only be accessed from certain parts of the world. Standard connections use local servers in the country to determine your location. This means that you cannot access content at home while traveling, and you cannot access international content from home. With 
**VPN location spoofing** , you can switch to a server to another country and effectively “change” your location.

**Secure data transfer:** If you work remotely, you may need to access important files on your company’s network. For security reasons, this kind of information requires a secure connection. To gain access to the network, a VPN connection is often required. VPN services connect to private servers and use encryption methods to reduce the risk of data leakage.

# Why should you use a VPN connection?

Your ISP usually sets up your connection when you connect to the internet. It tracks you via an IP address. Your network traffic is routed through your ISP's servers, which can log and display everything you do online.

Your ISP may seem trustworthy, but it may share your browsing history with advertisers, the police or government, and/or other third parties. ISPs can also fall victim to attacks by cyber criminals: If they are hacked, your personal and private data can be compromised.

This is especially important if you regularly connect to public Wi-Fi networks. You never know who might be monitoring your internet traffic and what they might steal from you, including passwords, personal data, payment information, or even your entire identity.

## What kind of VPNs are there?

### SSL VPN

Often not all employees of a company have access to a company laptop they can use to work from home. During the corona crisis in Spring 2020, many companies faced the problem of not having enough equipment for their employees. In such cases, use of a private device (PC, laptop, tablet, mobile phone) is often resorted to. In this case, companies fall back on an **SSL-VPN** solution, which is usually implemented via a corresponding hardware box.

The prerequisite is usually an HTML-5-capable browser, which is used to call up the company's login page. HTML-5 capable browsers are available for virtually any operating system. Access is guarded with a username and password.

### Site-to-site VPN

A **site-to-site VPN** is essentially a private network designed to hide private intranets and allow users of these secure networks to access each other's resources.

A site-to-site VPN is useful if you have multiple locations in your company, each with its own local area network (LAN) connected to the WAN (Wide Area Network). Site-to-site VPNs are also useful if you have two separate intranets between which you want to send files without users from one intranet explicitly accessing the other.

Site-to-site VPNs are mainly used in large companies. They are complex to implement and do not offer the same flexibility as SSL VPNs. However, they are the most effective way to ensure communication within and between large departments.

### Client-to-Server VPN

Connecting via a **VPN client** can be imagined as if you were connecting your home PC to the company with an extension cable. Employees can dial into the company network from their home office via the secure connection and act as if they were sitting in the office. However, a VPN client must first be installed and configured on the computer.

This involves the user not being connected to the internet via his own ISP, but establishing a direct connection through his/her VPN provider. This essentially shortens the tunnel phase of the VPN journey. Instead of using the VPN to create an encryption tunnel to disguise the existing internet connection, the VPN can automatically encrypt the data before it is made available to the user.

This is an increasingly common form of VPN, which is particularly useful for providers of insecure public WLAN. It prevents third parties from accessing and compromising the network connection and encrypts data all the way to the provider. It also prevents ISPs from accessing data that, for whatever reason, remains unencrypted and bypasses any restrictions on the user's internet access (for instance, if the government of that country restricts internet access).

The advantage of this type of VPN access is greater efficiency and universal access to company resources. Provided an appropriate telephone system is available, the employee can, for example, connect to the system with a headset and act as if he/she were at their company workplace. For example, customers of the company cannot even tell whether the employee is at work in the company or in their home office.

## Is a Free VPN Safe?

- **Security Risks:** One of the primary concerns with free VPNs online is that they may not have robust security features. Many free VPN providers lack the resources to develop and maintain strong security protocols, leaving their users vulnerable to cyber threats such as malware, hacking, and phishing.
- **Data Logging:** Free VPNs need to generate revenue, and they often do this by logging and selling users’ data to third-party advertisers. These VPN providers may log your browsing history, online activity, and personal information and then sell it to advertisers, compromising your online privacy.
- **Slow Internet Speeds:** Free VPNs have limited bandwidth and often throttle internet speed to reduce costs. This can make online browsing and stream painfully slow. Additionally, the best free VPN providers may place restrictions on the share of data you can utilize each month, forcing you to either upgrade to a paid version or seek another free VPN provider.
- **Limited Server Locations:** Free VPNs typically have fewer server locations than their paid counterparts. This can limit your access to geo-restricted content and make bypassing internet censorship in some countries harder. With limited server options, you may also experience slower speeds due to server congestion.
- **No Customer Support:** Finally, free VPNs typically offer no customer support or technical assistance. This can be significant if you run into problems with the VPN connection or need help troubleshooting an issue. You’re on your own, and this can make it difficult to get the help you need.


# Types of VPN protocols include:

- Internet Protocol Security (IPsec)
- Secure Socket Tunneling Protocol (SSTP)
- WireGuard
- OpenVPN
- SoftEther
- Point-to-Point Tunneling Protocol (PPTP)
- Layer 2 Tunneling Protocol (L2TP)


### Secure Socket Tunneling Protocol (SSTP)
	Secure Socket Tunneling Protocol (SSTP) is a VPN communication protocol developed to provide secure, encrypted connections over a network. SSTP uses SSL/TLS encryption, which is the same technology that underpins secure internet connections. SSL/TLS encryption ensures the privacy and security of data as it travels across the internet.

![[Pasted image 20250306085634.png]]




###  WireGuard

	WireGuard is a cutting-edge VPN protocol known for its simplicity and high-speed performance. WireGuard is designed to be much simpler and faster than legacy protocols, using state-of-the-art cryptographic techniques. As an open-source project, WireGuard's streamlined approach results in better efficiency and ease of use.

![[Pasted image 20250306085715.png]]


## OpenVPN

	OpenVPN is a robust, secure VPN protocol favored in the enterprise environment for its strong encryption and configurability. This protocol works by creating secure point-to-point or site-to-site connections in routed or bridged configurations. OpenVPN uses custom security protocols that utilize SSL/TLS for key exchange.

![[Pasted image 20250306085845.png]]



### Point-to-Point Tunneling Protocol (PPTP)

	Developed by Microsoft, Point-to-Point Tunneling Protocol (PPTP) is one of the oldest VPN protocols. PPTP facilitates secure data transmission by creating a tunnel for point-to-point communication. The protocol encapsulates data packets within an IP envelope, allowing them to be sent across a network

![[Pasted image 20250306090259.png]]

### Layer 2 Tunneling Protocol (L2TP)

	Layer 2 Tunneling Protocol (L2TP) is a tunneling protocol. It does not provide encryption or confidentiality by itself. L2TP relies on an encryption protocol that it passes within the tunnel to provide privacy. L2TP is often paired with IPsec, which is responsible for encryption and secure transport of data between endpoints.

![[Pasted image 20250306090511.png]]


### V2ray

 V2Ray Protocols

- **VMess**: The primary protocol in V2Ray, designed to hide proxy traffic and prevent detection.
- **VLESS**: A newer, lightweight alternative to VMess, designed for better performance and obfuscation.
- **Shadowsocks**: A widely used protocol for circumventing censorship, often paired with V2Ray.
- **Trojan**: Another protocol V2Ray supports, which mimics normal HTTPS traffic for better concealment.



2: Setup vpns on Mikrotik
	-Protocols
		openVpn,PPTP,L2TP
	-Firewall
	-ServerSide

3: In the end 
	-Real Examples
	-Web server && dns server 



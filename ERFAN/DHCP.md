[**Dynamic Host Configuration Protocol (DHCP)**](https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol)
## What is a DHCP Server?

A DHCP server is a network management tool that automatically assigns valid IP addresses to devices and computers connecting to the network without requiring constant intervention from an administrator. The DHCP server stores the IP information of clients, preventing the allocation of duplicate IP addresses, and ensures that valid and unique IP addresses are assigned.

## How Does a DHCP Server Work?

In a DHCP server, there is a pool of unique IP addresses available, and each device needs to obtain an IP address to connect to the network. Typically, clients send a "broadcast" request to the server immediately after booting up (a broadcast packet is a request sent to all active hosts on the network).

Next, the device that sent the IP request receives a "response" packet from the DHCP server. This packet includes the assigned IP address and the Default Gateway. It is important to note that this response is sent based on the configuration information previously defined by the network administrator.

Finally, a specific IP address is temporarily leased to the requester. Once the lease time expires, the IP address is considered available again. If the user requires more time, they can send another request, and the DHCP server may either renew the existing IP address or assign a new one, depending on the rules set by the network administrator.
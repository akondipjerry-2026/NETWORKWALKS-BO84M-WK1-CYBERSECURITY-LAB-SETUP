My Network Configuration

During this project, I created a NAT Network in VirtualBox and connected my Kali Linux virtual machine to it.

I chose NAT Network because I wanted my virtual machine to have internet access while also allowing communication with other virtual machines connected to the same network.

What I Did

- Created a NAT Network in VirtualBox.
- Connected my Kali Linux VM to the network.
- Started Kali Linux and checked its network connection.
- Tested internet connectivity to make sure it was working.

Network Details

These are the network settings I got from my Kali Linux machine:

Item| Configuration
Network Type| NAT Network
Kali Linux IP Address| 10.0.0.2
Default Gateway| 10.0.0.1
DNS Server| 10.0.0.1
Subnet Mask| 255.255.255.0 (/24)

Connectivity Test

After configuring the network, I tested the internet connection from Kali Linux.

Result: Internet connectivity was successful.

What I Learned

This exercise helped me understand how to connect a virtual machine to a NAT Network and check whether it can access the internet.

It also helped me become more familiar with network settings in VirtualBox.

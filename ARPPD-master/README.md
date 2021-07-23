For the initial few decades of network existence, computer networks were utilized
by corporate workers for sending email and by organisations for sharing printers.
With the advancement of society, network technology is likewise continually
growing, and network applications are gradually popularized.Increasingly more
computer users can get to a ton of data resources of global network system at
home.Internet has become an essential part of the present world. However, network
security also comes to our sight. There are huge loads of protocols which were
utilized to establish these networks.But there are a few precautions that were not
considered. In this project, we do some examination and simulation about the
Address Resolution Protocol (ARP) and ARP spoofing to exhibit a few precautions
in ARP. 

INTRODUCTION

ARP Poisoning (also called ARP Spoofing) is a type of cyber attack over a Local
Area Network (LAN) that includes sending malicious ARP bundles and packets to
a default gateway on a LAN in order to change the pairings in its IP to MAC
address table also called ARP Table. ARP Protocol translates IP Addresses into
MAC addresses. Since the ARP protocol was planned purely for effectiveness and
not for security, ARP Poisoning attacks are easy to execute as long as the attacker
has access of a machine inside the target LAN or is directly associated with it. The
attack itself comprises of an attacker sending a false ARP response to the default
network gateway, informing it that his or her MAC address ought to be related with
their target's IP address (and the other way around, so their target's MAC is now
connected with the attacker's IP address). When the default gateway has received
this message and broadcasts its changes to all different devices on the network, the
all of the of the target's traffic to other devices on the network goes through the
attacker's computer, permitting the attacker to access or alter it before sending it to
its real destination. Since ARP Poisoning attacks happen on such a low level, users
targeted by ARP Poisoning rarely realize that their traffic is being accessed or
altered. Other than Man-In-The-Middle-Attack, ARP Poisoning can be utilized to
cause a denial-of-service over a LAN by basically intercepting or dropping and not
forwarding the target's packets.

Here is how ARP works –
• When one machine needs to communicate with another, it looks into its ARP
table.
• If the MAC address isn't found in the table, the ARP request is broadcasted
over the network.
• All machines on the organization will compare this IP address with MAC
address.
• If one of the devices in the network identifies this MAC address, then it will
respond to the ARP request with its IP and MAC address.
• The requesting PC will store the address pair in its ARP table and
communication will occur. 

## What is a network ? 

When two and more computers connect with each other it is called **Network**.
But when two and more computers connect and share data/ resources then we call it **Networking**.

#### What is LAN & WAN ?

Local Area Networking and Wide Area Networking

Suppose, In Mumbai we have one switch with a different port in which we can connect 2-3 computers to it  and that switch is connected to the router.So, that particular area is called LAN.

When 2 different area LANs are connected to each other then we call it WAN.
WANs are of two types 
* Public
* Private
#### What is Router?

When we connect two or more different networks then we call it Router.
 
#### What is the Internet ?

The Internet is basically called the Network of networks. It is a combo of a small network and a big network then we call it Internet.

#### What is Switch in Networking ?

A network switch connects devices within a network (often a local area network, or LAN*) and forwards data packets to and from those devices.

![image](https://user-images.githubusercontent.com/96170504/216305824-6d08f751-63a0-4e92-ae81-4306b3f2c759.png)

#### What is the difference between a MAC address and an IP address?

Network switches refer to MAC addresses in order to send Internet traffic to the right devices, not IP addresses and Every device that connects to the Internet has an IP address. An IP address is a series of alphanumeric characters, like 192.0.2.255 or 2001:0db8:85a3:0000:0000:8a2e:0370:7334.

#### what is Router ?

It is a network device which works as a traffic controller. it's main purpose is to choose a congestion free path to send the data packets .
otherway, Router is a network device which is used to connect different network with each other. 

#### what is ISP Network ?

The term “internet service provider (ISP)” refers to a company that provides access to the internet to both personal and business customers. ISPs make it possible for their customers to surf the web, shop online, conduct business, and connect with family and friends—all for a fee.

#### What is IP Address in Network ?

An IP address is a long string of numbers assigned to every device connected to a network that uses Internet Protocol as the medium for communication.

There are 2 types of IP Address:-
* IPv4 : IPv4 is the fourth version of IP,The IPv4 uses a 32-bit address scheme allowing to store 2^32 addresses.Eg :- 192.149.252.76 
* IPv6 : IPv6 (Internet Protocol Version 6) , IPv6 is a 128-bit IP address which supports 2^128 Internet addresses in total.The use of IPv6 not only solves the problem of limited network addresses resources but also resolves the barriers for multiple access devices to connect to the Internet. Eg:- 3ffe:1900:fe21:4545:0000:0000:0000:0000

2^7  2^6 2^5 2^4 2^3 2^2 2^1 2^0 
128  64  32   16   8  4   2   1

![image](https://user-images.githubusercontent.com/96170504/216386673-5d851e51-faf2-40e2-8ce0-7655b3e8b9b6.png)

Class A : 0 to 127  
Class B : 128 to 191 
Class C : 192 to 223 
Class D : 224 to 239
Class E : 240 to 255

#### what is Network Model ?

There are two type of Network :
* OSI Networking Model
* TCP/IP Network

![image](https://user-images.githubusercontent.com/96170504/216316561-899f4ab6-2852-4d1f-94ce-c273cf884a10.png)

* Application Layer : Data > The Softwares which interact one huuman to another workes in Application Layer. webbrowser [http, https, SMTP]
* Presentation Layer : Data > Is the Formate eg : Png, jpeg Audio: Mp3, Video : mp4
* Session Layer : Data > Create and Maintain the sessions
* Transport Layer : Segment > End to end delivery of data. Segments will add the Port number 
* Network Layer : Packets | IP address | ICMP | IPv4 | IPv6 (Routers) . There the packets will add the source IP and destination IP
* Datalink Layer : Frame| It adds the Source Mac address and destination Mac address.
* Physical Layer : Bits | cables| connection , In this basically the NIC card will encode and MAC address into 0's and 1's 0011.

#### Subnet Mask

A subnet mask is a 32-bit number created by setting host bits to all 0s and setting network bits to all 1s. In this way, the subnet mask separates the IP address into the network and host addresses.

Note: 1 - 128 , 2 - 192, 3 - 224, 4 - 240, 5 - 248, 6 - 252, 7 - 254
Eg to find subnet
10.0.1.1/24 :- 24= (8+8+8) "8bit = 225"
225.225.225.0 Subnet
216.202.192.66/22 :- (8+8+6)
Subnet 225.225.252.0

#### By seeling IP how can u say which class does it belong.

Class A : 0 to 127  
Class B : 128 to 191 
Class C : 192 to 223 
Class D : 224 to 239
Class E : 240 to 255

* Just by checking above class range u can say your IP range
150.1.1.1 : Class B , 200.1.1.1 : Class C, 125.1.1.1 : Class A , 128.1.1.1 : Class B, 194.1.1.1 : Class C.

#### How to find the Network and Host in IP ?

Class A : N H H H , Class B : N N H H, Class C : N N N H
Example:-  177.100.18.4   
 As 177 comes under Class B so, there will be two N and two H.
 * 199.8.45.0 : As 199 comes under Class c so, there will be three N and one H.
 * 119.8.35.9 : As 199 comes uner class A so, there will be one N and three H.
 * 192.53.87.9 : As 192 comes under class C so, there will be three N and one H.
 * 95.96.76.2: As 95 comes uner class A so, there will be one N and three H.


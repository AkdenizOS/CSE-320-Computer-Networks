1. The Internet is often described as a network of networks that interconnects millions of
hosts.
2. Devices such as routers and switches that forward packets are called packet switches.
3. In networking, a protocol defines the format, order, and actions taken for exchanging
messages.
4. The computers running network applications at the edge of the Internet are called end
systems.
5. Communication links in networks may use physical media such as fiber, copper, radio, or
sattelite.
6. The network edge consists mainly of hosts such as clients and servers.
7. The part of the network composed of interconnected routers responsible for forwarding
packets is called the network core.
8. In a client–server architecture, the server is typically an always-on host with a
permanent IP address.
9. In peer-to-peer architecture, peers both request services and provide services to other
peers.
10. A process communicating over the network is identified using an IP address together
with a port number.
11. In socket communication, the socket acts as the door between the application and the
transport layer.
12. HTTP is an example of an application layer protocol used by the Web.
13. Email transfer across mail servers typically uses the protocol called SMTP.
14. The transport layer provides logical communication between application processes
running on different hosts.
15. The Internet transport protocol that provides reliable, ordered delivery of data is TCP.
16. The Internet transport protocol that provides a lightweight, connectionless service is
UDP.
17. When sending data, the transport layer divides application messages into smaller units
called segments.
18. The process of gathering data from multiple sockets at the sender is called
multiplexing.
19. The process of delivering received segments to the correct socket at the receiver is
called demultiplexing.
20. The two main functions of the network layer are routing and forwarding.
21. 
**Network Layer (Ağ Katmanı - Yönlendirme ve IP)**
21. The process of moving packets from a router's input to the appropriate router output is called ________.

22. The algorithm that determines the end-to-end path taken by packets from source to destination is called ________.

23. The length of an IPv4 address is ________ bits, whereas an IPv6 address is 128 bits.

24. A network protocol that dynamically assigns temporary IP addresses to hosts when they join a local network is called ________.

25. The ________ protocol translates private IP addresses in a local network to a single public IP address for Internet access.

26. The algorithm that calculates the shortest path from a single source node to all other nodes using global topology information is known as ________ algorithm.


**Link Layer & LANs (Bağlantı Katmanı ve Yerel Ağlar)**
27. While the network layer uses IP addresses to route packets, the link layer uses ________ addresses to deliver frames to physically connected interfaces.

28. The ________ protocol is used to translate an IP address into its corresponding physical (MAC) address.

29. Error detection at the link layer is commonly implemented using CRC, which stands for Cyclic ________ Check.

30. Ethernet uses the ________ multiple access protocol to listen to the channel and handle collisions on a shared medium.

31. A link-layer ________ is a plug-and-play device that transparently forwards frames based on MAC destination addresses and builds its own forwarding table dynamically.

32. In network switches, a technique used to create multiple logical broadcast domains within a single physical infrastructure is called ________.


**Wireless & Mobile Networks (Kablosuz ve Mobil Ağlar)**

33. 802.11 wireless LANs (Wi-Fi) use the ________ protocol to avoid collisions, rather than detecting them like Ethernet does.

34. In wireless networks, the situation where two nodes can both communicate with a central access point but cannot hear each other's transmissions is called the ________ terminal problem.

35. As a radio signal propagates through space or matter, its strength decreases; this phenomenon is known as ________ loss (or signal attenuation).


**TCP/UDP & Congestion Control (Taşıma Katmanı - Sınav Dokümanlarından)**

36. In the TCP congestion control mechanism, the initial phase where the congestion window size grows exponentially is known as TCP ________.

37. A TCP segment loss can be detected either by a timeout or by the receipt of three ________ ACKs.


**Packet Tracer / CLI Commands (Final Sınavı Dokümanından)**
38. In a Cisco router, the command `enable` is used to enter into ________ EXEC mode.

39. To configure the router globally, you must enter into global ________ mode.


**Chapter 1: Network Core, Delay & Architecture (Ağ Temelleri ve Gecikme)**

40. The time required to push all of a packet's bits into the link is called ________ delay.

41. The time required for a bit to travel from the beginning of the physical link to the next router is called ________ delay.

42. A ________ attack makes network resources unavailable to legitimate users by overwhelming the resource with a flood of bogus traffic.

43. In the OSI reference model, the ________ layer is responsible for allowing applications to interpret the meaning of data, such as encryption and compression.

44. The rate (in bits/sec) at which bits are currently being transferred between sender and receiver is called the ________.


**Chapter 4: Network Layer & Routing (Ağ Katmanı ve Yönlendirme)**

45. In a router's architecture, the ________ fabric physically moves a packet from an input port to the appropriate output port.

46. The maximum amount of data that a link-layer frame can carry, which dictates if an IP datagram needs fragmentation, is called the ________ (Maximum Transmission Unit).

47. IPv4 addresses are 32 bits long and are typically written in ________-dotted notation.

48. The network-layer protocol used by routers and hosts to communicate error information, such as "destination network unreachable", is called ________.

49. Distance Vector (DV) routing algorithms are based on the ________ equation (dynamic programming).

50. A well-known issue with Distance Vector algorithms, where nodes repeatedly exchange increasing cost updates when a link fails, is called the "count-to-________" problem.

51. ________ is a routing protocol that uses a Link-State (LS) algorithm and floods routing information to all routers in the Autonomous System (AS).

52. The inter-domain routing protocol that acts as the "glue" holding the entire Internet together is called ________.


**Chapter 5: Link Layer & LANs (Bağlantı Katmanı ve Yerel Ağlar)**

53. The link layer encapsulates a network-layer datagram into a ________ before transmitting it over the link.

54. A MAC address is ________ bits long and is permanently burned into the ROM of the Network Interface Card (NIC).

55. Ethernet MAC addresses are usually written in base-16, which is known as ________ notation.

56. In a shared multiple access channel, when two or more nodes transmit frames at the exact same time, a ________ occurs.

57. Slotted ALOHA and CSMA/CD are examples of ________ access MAC protocols, where nodes don't take turns but try to transmit whenever they have data.

58. A link-layer switch builds its MAC address table automatically and dynamically using a process called ________ learning.

59. In an Ethernet frame, the 8-byte ________ field is used to wake up the receiving adapters and synchronize their clocks.


**Chapter 6: Wireless & Mobile Networks (Kablosuz Ağlar)**:

60. In 802.11 (Wi-Fi) infrastructure networks, the base station is also known as an Access ________.

61. To reduce collisions caused by the hidden terminal problem, 802.11 networks can use small reservation packets called RTS (Request to Send) and ________ (Clear to Send).

62. In cellular networks, the process of routing a call to a new base station without interrupting the ongoing connection is called ________.


**Transport Layer & TCP Congestion (Taşıma Katmanı ve Tıkanıklık Kontrolü)**

63. The maximum amount of unacknowledged data a TCP sender can have in flight is limited by the ________ window (cwnd).

64. In TCP congestion control, the sender transitions from the "slow start" phase to the "congestion avoidance" phase when the window size reaches a variable called ________.

65. The TCP fast ________ mechanism allows a sender to retransmit a missing segment before the timer expires if it receives 3 duplicate ACKs.


**General Protocols (Genel Protokoller ve Kavramlar)**
66. The Domain Name System (DNS) is primarily used to translate human-readable hostnames into ________ addresses.

67. While HTTP and FTP use TCP for reliable data transfer, DNS typically uses ________ as its underlying transport layer protocol for faster, connectionless queries.

68. When a host wants to dynamically obtain an IP address upon joining a network, it broadcasts a ________ Discover message.

69. A ________ router allows multiple devices on a local network to share a single public IP address.

70. In an IP address, a subnet mask is used to separate the network part from the ________ part.


---

### Cevap Anahtarı (Answer Key)

21. forwarding
22. routing
23. 32
24. DHCP *(Dynamic Host Configuration Protocol)*
25. NAT *(Network Address Translation)*
26. Dijkstra's *(veya Link-State)*
27. MAC *(veya physical, LAN)*
28. ARP *(Address Resolution Protocol)*
29. Redundancy
30. CSMA/CD *(Carrier Sense Multiple Access with Collision Detection)*
31. switch
32. VLAN *(Virtual Local Area Network)*
33. CSMA/CA *(Carrier Sense Multiple Access with Collision Avoidance)*
34. hidden
35. path
36. slow start
37. duplicate
38. privileged
39. configuration
40. transmission
41. propagation
42. DoS *(veya Denial of Service)*
43. presentation
44. throughput
45. switching
46. MTU
47. decimal
48. ICMP *(Internet Control Message Protocol)*
49. Bellman-Ford
50. infinity
51. OSPF *(Open Shortest Path First)*
52. BGP *(Border Gateway Protocol)*
53. frame
54. 48
55. hexadecimal
56. collision
57. random
58. self *(veya switch)*
59. preamble
60. Point *(AP = Access Point)*
61. CTS
62. handoff *(veya handover)*
63. congestion
64. ssthresh *(slow start threshold)*
65. retransmit
66. IP
67. UDP *(User Datagram Protocol)*
68. DHCP
69. NAT *(Network Address Translation)*
70. host

---

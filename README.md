# Computer Networks & the Internet

<a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" alt="Creative Commons License" /></a>This tutorial was written by Katherine Walden and is licensed under a <a href="http://creativecommons.org/licenses/by-nc/4.0/" rel="license">Creative Commons Attribution-NonCommercial 4.0 International License</a>.

## Lab Overview & Goals

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?pid=34072a5a-f600-4db0-ad8a-aef501001d65">Lecture/Live Coding Playlist</a></td>
  </tr>
  </table>

## Acknowledgements

This lab's lecture segments were adapted from the following PBS *[Crash Course Computer Science](https://www.pbs.org/show/crash-course-computer-science/)* episodes:
- "[Computer Networks](https://www.pbs.org/video/computer-networks-crash-course-computer-science-28-dqjdkc/)"
- "[The Internet](https://www.pbs.org/video/the-internet-crash-course-computer-science-29-oj4vv6/)"

# Table of Contents
- [Lecture & Live Coding](#lecture--live-coding)
- [Key Concepts](#key-concepts)
- [Templates](#templates)
- [Computer Networks](#computer-networks)
- [The Internet](#the-internet)
- [Additional Resources](#additional-resources)
- [Lab Notebook Questions](#lab-notebook-questions)

## Lecture & Live Coding

Throughout this lab, you will see a Panopto icon at the start of select sections.

This icon indicates there is lecture/live coding asynchronous content that accompanies this section of the lab. 

You can click the link in the figure caption to access these materials (ND users only).

Example:

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?pid=34072a5a-f600-4db0-ad8a-aef501001d65">Lecture/Live Coding Playlist</a></td>
  </tr>
  </table>

## Key Concepts

[Click here](https://github.com/kwaldenphd/internet/blob/main/key-concepts.md) for a full list of key concepts and definitions for this lab.

## Templates

[Link to lab notebook template](https://docs.google.com/document/d/1qYZRLlZzbZHCGIJEn4Urvpk9uBHouE_psQCsU61lEvE/copy) (ND users, Google Doc)

# Computer Networks

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=18ec9cd0-b880-4987-814b-aef5000b3f73">Computer Networks</a></td>
  </tr>
  </table>

## Key Concepts

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/LAN_WAN.svg?raw=true" width="500"></p>

**Local Area Network (LAN)**
- "A local area network (LAN) is a computer network that interconnects computers within a limited area such as a residence, school, laboratory, university campus or office building. By contrast, a wide area network (WAN) not only covers a larger geographic distance, but also generally involves leased telecommunication circuits. Ethernet and Wi-Fi are the two most common technologies in use for local area networks" ([Wikipedia](https://en.wikipedia.org/wiki/Local_area_network))

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/1973_Ether.png?raw=true" width="500"></p>

**Ethernet**
- "Ethernet is a family of wired computer networking technologies commonly used in local area networks (LAN), metropolitan area networks (MAN) and wide area networks (WAN). It was commercially introduced in 1980 and first standardized in 1983" ([Wikipedia](https://en.wikipedia.org/wiki/Ethernet))

**Media Access Control (MAC) Address**
- "A media access control address (MAC address) is a unique identifier assigned to a network interface controller (NIC) for use as a network address in communications within a network segment. This use is common in...networking technologies, including Ethernet, Wi-Fi, and Bluetooth...As typically represented, MAC addresses are recognizable as six groups of two hexadecimal digits, separated by hyphens, colons, or without a separator" ([Wikipedia](https://en.wikipedia.org/wiki/MAC_address))

**Routing/Routers**
- "A router is a networking device that forwards data packets between computer networks. Routers perform the traffic directing functions on the Internet. Data sent through the internet, such as a web page or email, is in the form of data packets. A packet is typically forwarded from one router to another router through the networks that constitute an internetwork (e.g. the Internet) until it reaches its destination node" ([Wikipedia](https://en.wikipedia.org/wiki/Router_(computing)))

**Hops**
- "In wired computer networking, including the Internet, a hop occurs when a packet is passed from one network segment to the next. Data packets pass through routers as they travel between source and destination. The hop count refers to the number of network devices through which data passes from source to destination" ([Wikipedia](https://en.wikipedia.org/wiki/Hop_(networking)))

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/Packet_Switching_Diagram.png?raw=true" width="500"></p>

**Packet Switching**
- "Packet switching is a method of grouping data that is transmitted over a digital network into packets. Packets are made of a header and a payload. Data in the header are used by networking hardware to direct the packet to its destination where the payload is extracted and used by application software. Packet switching is the primary basis for data communications in computer networks worldwide" ([Wikipedia](https://en.wikipedia.org/wiki/Packet_switching))

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/Packet_Diagram.png?raw=true" width="500"></p>

**Network Packet**
- "A network packet is a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data, which is also known as the payload. Control information provides data for delivering the payload, for example: source and destination network addresses, error detection codes, and sequencing information. Typically, control information is found in packet headers and trailers" ([Wikipedia](https://en.wikipedia.org/wiki/Network_packet))

**Internet Protocol (IP)**
- "The Internet protocol suite is the conceptual model and set of communications protocols used in the Internet and similar computer networks. It is commonly known as TCP/IP because the foundational protocols in the suite are the Transmission Control Protocol (TCP) and the Internet Protocol (IP). The Internet protocol suite provides end-to-end data communication specifying how data should be packetized, addressed, transmitted, routed, and received. This functionality is organized into four abstraction layers, which classify all related protocols according to the scope of networking involved. From lowest to highest, the layers are the link layer, containing communication methods for data that remains within a single network segment (link); the internet layer, providing internetworking between independent networks; the transport layer, handling host-to-host communication; and the application layer, providing process-to-process data exchange for applications" ([Wikipedia](https://en.wikipedia.org/wiki/Internet_protocol_suite))

**Internet Protocol (IP) Address**
- "An Internet Protocol address (IP address) is a numerical label such as 192.0.2.1 that is connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: network interface identification and location addressing" ([Wikipedia](https://en.wikipedia.org/wiki/IP_address))

**ARPANET**
- "The Advanced Research Projects Agency Network (ARPANET) was the first wide-area packet-switched network with distributed control and one of the first networks to implement the TCP/IP protocol suite. Both technologies became the technical foundation of the Internet. The ARPANET was established by the Advanced Research Projects Agency (ARPA) of the United States Department of Defense" ([Wikipedia](https://en.wikipedia.org/wiki/ARPANET))

**Internet of Things**
- "The Internet of things (IoT) describes physical objects (or groups of such objects) with sensors, processing ability, software, and other technologies that connect and exchange data with other devices and systems over the Internet or other communications networks" ([Wikipedia](https://en.wikipedia.org/wiki/Internet_of_things))

[Click here](https://github.com/kwaldenphd/internet/blob/main/key-concepts.md) for a full list of key concepts and definitions for this lab.

## Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSexiph4YBLk_cvOK6dt0C_4qfiFZ0RfvxUYJFWFdL83msZo_g/viewform?usp=sf_link">Computer Networks Comprehension Check</a></td>
  </tr>
  </table>

## Application

Q1a: Let's use the `ping` command for a network test. Open a terminal shell (`Terminal` or `Git BASH`). Type `ping` followed by an IP address. A few you could choose from:
- OpenDNS: `208.67.222.222` and `208.67.220.220`
- Cloudflare: `1.1.1.1` and `1.0.0.1`
- Google: `8.8.8.8` and `8.8.4.4`

Sample command for Google:
```
ping 8.8.8.8
```

Press `Enter`/`Return`.

Q1b: Describe what you're seeing in the `ping` command output. What do these results indicate about the network status? A couple resources that can help with understanding these results:
- IBM, "[`ping` Command](https://www.ibm.com/docs/en/aix/7.1?topic=p-ping-command)"
- PageDuty, "[How to Ping a Network for Testing Connectivity](https://www.pagerduty.com/resources/learn/ping-network-testing-connectivity/)"

Q2a: Let's run a similar test using the `traceroute` or `tracert` command. Still in the  terminal, type `tracert` followed by a domain name or IP address.

Domain name example:
```
tracert google.com
```

IP address example:
```
tracert 8.8.8.8
```

Press `Enter`/`Return`.

<blockquote>Alternate <code>traceroute</code> workflow for MacOS users: Shaw Support, "<a href="https://support.shaw.ca/t5/internet-articles/how-to-run-a-traceroute-mac-os/ta-p/5053">How to run a Traceroute (Mac OS)</a>."</blockquote>

Q2b: Describe what you're seeing in the `traceroute`/`tracert` program output. What do these results indicate about the network status? How are they similar or different from the `ping` output? 

A couple resources that can help with understanding these results:
- RedHat, "[Traceroute: Finding meaning among the stars](https://www.redhat.com/sysadmin/traceroute-finding-meaning)"
- InMotion Hosting, "[How to Read a Traceroute](https://www.inmotionhosting.com/support/server/ssh/read-traceroute/)"

# The Internet

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=cbd745c0-1db8-40f8-a234-aef401865bf1">Computer Networks</a></td>
  </tr>
  </table>

## Key Concepts

**Internet**
- "The Internet is the global system of interconnected computer networks that uses the Internet protocol suite (TCP/IP) to communicate between networks and devices. It is a network of networks that consists of private, public, academic, business, and government networks of local to global scope, linked by a broad array of electronic, wireless, and optical networking technologies" ([Wikipedia](https://en.wikipedia.org/wiki/Internet))

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/LAN_WAN.svg?raw=true" width="500"></p>

**Wide Area Network (WAN)**
- "A wide area network (WAN) is a telecommunications network that extends over a large geographic area" ([Wikipedia](https://en.wikipedia.org/wiki/Wide_area_network))

**Internet Service Provider (ISP)**
- "An Internet service provider (ISP) is an organization that provides services for accessing, using, or participating in the Internet. ISPs can be organized in various forms, such as commercial, community-owned, non-profit, or otherwise privately owned" ([Wikipedia](https://en.wikipedia.org/wiki/Internet_service_provider))
- Common commercial ISPs in the U.S. include: AT&T, Verizon, Xfinity, Comcast, Windstream

**Packet Switching**
- "Packet switching is a method of grouping data that is transmitted over a digital network into packets. Packets are made of a header and a payload. Data in the header are used by networking hardware to direct the packet to its destination where the payload is extracted and used by application software. Packet switching is the primary basis for data communications in computer networks worldwide" ([Wikipedia](https://en.wikipedia.org/wiki/Packet_switching))

**User Datagram Protocol (UDP)**
- "In computer networking, the User Datagram Protocol (UDP) is one of the core members of the Internet protocol suite. With UDP, computer applications can send messages, in this case referred to as datagrams, to other hosts on an Internet Protocol (IP) network" ([Wikipedia](https://en.wikipedia.org/wiki/User_Datagram_Protocol))

**Transmission Control Protocol (TCP, or TCP/IP)**
- "The Transmission Control Protocol (TCP) is one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol (IP). Therefore, the entire suite is commonly referred to as TCP/IP" ([Wikipedia](https://en.wikipedia.org/wiki/Transmission_Control_Protocol))

**Internet Protocol (IP) Address**
- "An Internet Protocol address (IP address) is a numerical label such as 192.0.2.1 that is connected to a computer network that uses the Internet Protocol for communication. An IP address serves two main functions: network interface identification and location addressing" ([Wikipedia](https://en.wikipedia.org/wiki/IP_address))

**Port**
- "In computer networking, a port is a number assigned to uniquely identify a connection endpoint and to direct data to a specific service. At the software level, within an operating system, a port is a logical construct that identifies a specific process or a type of network service. A port is identified for each transport protocol and address combination by a 16-bit unsigned number, known as the port number. The most common transport protocols that use port numbers are the Transmission Control Protocol (TCP) and the User Datagram Protocol (UDP)" ([Wikipedia](https://en.wikipedia.org/wiki/Port_(computer_networking)))

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/DNS_Tree.png?raw=true" width="500"></p>

**Domain Name System (DNS)**
- "The Domain Name System (DNS) is the hierarchical and decentralized naming system used to identify computers reachable through the Internet or other Internet Protocol (IP) networks" ([Wikipedia](https://en.wikipedia.org/wiki/Domain_Name_System))

**Top-Level Domains (TLDs)**
- "A top-level domain (TLD) is one of the domains at the highest level in the hierarchical Domain Name System of the Internet after the root domain" ([Wikipedia]())
- Examples include: `.com`, `.org`, `.edu`

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/OSI_Model.png?raw=true" width="500"></p>

**Open System Interconnection (OSI) Model**
<ul><li>"The Open Systems Interconnection model (OSI model) is a conceptual model that describes the universal standard of communication functions of a telecommunication system or computing system, without any regard to the system's underlying internal technology and specific protocol suites" (<a href="https://en.wikipedia.org/wiki/OSI_model">Wikipedia</a>)</li>
 <li>Layers in the OSI Model:</li>
<ol type="1">
 <li value="7">Application</li>
 <li value="6">Presentation</li>
 <li value="5">Session</li>
 <li value="4">Transport</li>
 <li value="3">Network</li>
 <li value="2">Data link</li>
 <li value="1">Physical</li>
 </ol>
 </ul>

[Click here](https://github.com/kwaldenphd/internet/blob/main/key-concepts.md) for a full list of key concepts and definitions for this lab.

## Comprehension Check

<table>
 <tr><td>
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSdcKWzqImWVevjXXv766giq0E3xwbdsEHV1OvkZmt4YIVhbag/viewform?usp=sf_link">The Internet Comprehension Check</a></td>
  </tr>
  </table>

## Application

Q3a: Let's use the `ipconfig` (Windows) or `ifconfig` (Mac) commands to learn more about your computer's network configuration. Open a terminal shell (`Terminal` or `Git BASH`). Type `ipconfig` (Windows) or `ifconfig` (Mac) followed by `Enter`/`Return`.

Q3b: Describe what you're seeing in the output. What information are these results providing about your network? How do they connect to concepts covered in this lab?

A couple resources that can help with understanding these results:
- `ipconfig`
  * LazyAdmin, "[How to use the ipconfig command and options explained](https://lazyadmin.nl/it/ipconfig-command/)"
  * Meridian Outpost, "[How to use ipconfig command with examples](https://www.meridianoutpost.com/resources/articles/command-line/ipconfig.php)"
- `ifconfig`
  * StackExchange, "[MacOS ifconfig output](https://superuser.com/questions/267660/can-someone-please-explain-ifconfig-output-in-mac-os-x)"
  * Oracle, "[Monitoring the interface with the `ifconfig` command](https://docs.oracle.com/cd/E19253-01/816-4554/ipconfig-141/index.html)"

## Additional Resources

Interested in learning more about computer networks and the Internet? The "[Additional Resources](https://github.com/kwaldenphd/internet/blob/main/additional-resources.md)" page in this repository includes links to a variety of content on...
- Conceptual and technical foundations
- Markup languages and HTML
- Cultural histories of the internet
- Identity and power in online spaces

# Lab Notebook Questions

[Link to lab notebook template](https://docs.google.com/document/d/1qYZRLlZzbZHCGIJEn4Urvpk9uBHouE_psQCsU61lEvE/copy) (ND users, Google Doc)

Q1a: Let's use the `ping` command for a network test. Open a terminal shell (`Terminal` or `Git BASH`). Type `ping` followed by an IP address. A few you could choose from:
- OpenDNS: `208.67.222.222` and `208.67.220.220`
- Cloudflare: `1.1.1.1` and `1.0.0.1`
- Google: `8.8.8.8` and `8.8.4.4`

Sample command for Google:
```
ping 8.8.8.8
```

Press `Enter`/`Return`.

Q1b: Describe what you're seeing in the `ping` command output. What do these results indicate about the network status? A couple resources that can help with understanding these results:
- IBM, "[`ping` Command](https://www.ibm.com/docs/en/aix/7.1?topic=p-ping-command)"
- PageDuty, "[How to Ping a Network for Testing Connectivity](https://www.pagerduty.com/resources/learn/ping-network-testing-connectivity/)"

Q2a: Let's run a similar test using the `traceroute` or `tracert` command. Still in the  terminal, type `tracert` followed by a domain name or IP address.

Domain name example:
```
tracert google.com
```

IP address example:
```
tracert 8.8.8.8
```

Press `Enter`/`Return`.

<blockquote>Alternate <code>traceroute</code> workflow for MacOS users: Shaw Support, "<a href="https://support.shaw.ca/t5/internet-articles/how-to-run-a-traceroute-mac-os/ta-p/5053">How to run a Traceroute (Mac OS)</a>."</blockquote>

Q2b: Describe what you're seeing in the `traceroute`/`tracert` program output. What do these results indicate about the network status? How are they similar or different from the `ping` output? 

A couple resources that can help with understanding these results:
- RedHat, "[Traceroute: Finding meaning among the stars](https://www.redhat.com/sysadmin/traceroute-finding-meaning)"
- InMotion Hosting, "[How to Read a Traceroute](https://www.inmotionhosting.com/support/server/ssh/read-traceroute/)"

Q3a: Let's use the `ipconfig` (Windows) or `ifconfig` (Mac) commands to learn more about your computer's network configuration. Open a terminal shell (`Terminal` or `Git BASH`). Type `ipconfig` (Windows) or `ifconfig` (Mac) followed by `Enter`/`Return`.

Q3b: Describe what you're seeing in the output. What information are these results providing about your network? How do they connect to concepts covered in this lab?

A couple resources that can help with understanding these results:
- `ipconfig`
  * LazyAdmin, "[How to use the ipconfig command and options explained](https://lazyadmin.nl/it/ipconfig-command/)"
  * Meridian Outpost, "[How to use ipconfig command with examples](https://www.meridianoutpost.com/resources/articles/command-line/ipconfig.php)"
- `ifconfig`
  * StackExchange, "[MacOS ifconfig output](https://superuser.com/questions/267660/can-someone-please-explain-ifconfig-output-in-mac-os-x)"
  * Oracle, "[Monitoring the interface with the `ifconfig` command](https://docs.oracle.com/cd/E19253-01/816-4554/ipconfig-141/index.html)"

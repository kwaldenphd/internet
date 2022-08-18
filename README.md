# Computer Networks and the Internet

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
- "[The World Wide Web](https://www.pbs.org/video/the-world-wide-web-crash-course-computer-science-30-r9235i/)"

# Table of Contents
- [Lecture & Live Coding](#lecture--live-coding)
- [Key Terms](#key-terms)
- [Lab Notebook Template](#lab-notebook-template)
- [Computer Networks](#computer-networks)
- [The Internet](#the-internet)
- [The World Wide Web](#the-world-wide-web)
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

## Key Terms

[Click here](https://github.com/kwaldenphd/internet/blob/main/key-terms.md) for a full list of key terms and definitions for this lab.

## Lab Notebook Template

# Computer Networks

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=18ec9cd0-b880-4987-814b-aef5000b3f73">Computer Networks</a></td>
  </tr>
  </table>

## Key Terms

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

[Click here](https://github.com/kwaldenphd/internet/blob/main/key-terms.md) for a full list of key terms and definitions for this lab.

## Comprehension Check

<table>
 <tr><td>
<img src="https://www.freeiconspng.com/thumbs/survey-icon/survey-icon-12.png" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLScQoRbyDYB2Cisg_AmfMhUqj8qXn0ZbeuembRhQpOnbb64I2g/viewform?usp=sf_link">Computer Networks Comprehension Check</a></td>
  </tr>
  </table>

What do protocols do

Packet switching in your own words

## Application

COMPUTER NETWORK HARDWARE SPECS, SOMETHING WITH THE ND NETWORK

# The Internet

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=cbd745c0-1db8-40f8-a234-aef401865bf1">Computer Networks</a></td>
  </tr>
  </table>

## Key Terms

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

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/OS_Model.png?raw=true" width="500"></p>

**Open System Interconnection (OSI) Model**
- "The Open Systems Interconnection model (OSI model) is a conceptual model that describes the universal standard of communication functions of a telecommunication system or computing system, without any regard to the system's underlying internal technology and specific protocol suites" ([Wikipedia]())
- Layers in the OSI Model:
  7. Application
  6. Presentation
  5. Session
  4. Transport
  3. Network
  2. Data link
  1. Physical

[Click here](https://github.com/kwaldenphd/internet/blob/main/key-terms.md) for a full list of key terms and definitions for this lab.

## Comprehension Check

<table>
 <tr><td>
<img src="https://www.freeiconspng.com/thumbs/survey-icon/survey-icon-12.png" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLScQoRbyDYB2Cisg_AmfMhUqj8qXn0ZbeuembRhQpOnbb64I2g/viewform?usp=sf_link">The Internet Comprehension Check</a></td>
  </tr>
  </table>

Describe layers of OSI Model

IP address description

Something more technical about packet switching

## Application

TRACEROUTE, GET YOUR IP

# The World Wide Web 

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=7bacf9bb-6940-44f2-8e90-aef401865c19">Computer Networks</a></td>
  </tr>
  </table>

## Key Terms

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/WWW_Berns_Lee.png?raw=true" width="500"></p>

**World Wide Web (WWW)**
- "The World Wide Web (WWW), commonly known as the Web, is an information system where documents and other web resources are identified by Uniform Resource Locators (URLs, such as https://www.example.com/), which may be interlinked by hypertext, and are accessible over the Internet. The resources of the WWW are transferred via the Hypertext Transfer Protocol (HTTP) and may be accessed by users by a software application called a web browser and are published by a software application called a web server" ([Wikipedia](https://en.wikipedia.org/wiki/World_Wide_Web))

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/Hypertext.png?raw=true" width="500"></p>

**Hyerlinks & Hypertext**
- "In computing, a hyperlink, or simply a link, is a reference to data that the user can follow by clicking or tapping. A hyperlink points to a whole document or to a specific element within a document. Hypertext is text with hyperlinks" ([Wikipedia](https://en.wikipedia.org/wiki/Hyperlink))

**Web Browsers**
- "A web browser (also referred to as an Internet browser or simply a browser) is application software for accessing the World Wide Web or a local website. When a user requests a web page from a particular website, the web browser retrieves the necessary content from a web server and then displays the page on the user's device" ([Wikipedia](https://en.wikipedia.org/wiki/Web_browser))
- Sample web browsers: Internet Exporer, Microsoft Edge, Mozilla Firefox, Safari, Google Chrome

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/URL.png?raw=true" width="500"></p>

**Uniform Resource Locator (URL)**
- "A Uniform Resource Locator (URL), colloquially termed a web address, is a reference to a web resource that specifies its location on a computer network and a mechanism for retrieving it. A URL is a specific type of Uniform Resource Identifier (URI), although many people use the two terms interchangeably" ([Wikipedia](https://en.wikipedia.org/wiki/URL))

**Web Server**
- "A web server is computer software and underlying hardware that accepts requests via HTTP (the network protocol created to distribute web content) or its secure variant HTTPS" ([Wikipedia](https://en.wikipedia.org/wiki/Web_server))

**Hypertext Transfer Protocol (HTTP)**
- "The Hypertext Transfer Protocol (HTTP) is an application protocol for distributed, collaborative, hypermedia information systems. HTTP is the foundation of data communication for the World Wide Web, where hypertext documents include hyperlinks to other resources that the user can easily access, for example by a mouse click or by tapping the screen in a web browser" ([Wikipedia](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol))

**Markup Language**
- "In computer text processing, a markup language is a system for annotating a document in a way that is syntactically distinguishable from the text, meaning when the document is processed for display, the markup language is not shown, and is only used to format the text" ([Wikipedia](https://en.wikipedia.org/wiki/Markup_language))
- [Click here](https://youtu.be/C0ivP3KYO3A) to learn more about markup languages.

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/HTML_Tag.png?raw=true" width="500"></p>

**Hypertext Markup Language (HTML)**
- “HyperText Markup Language, invented by Tim Berners-Lee as the basis for the World Wide Web….based on the international standard SGML (Standardized Generalized Markup Language), which was originally developed for the representation of print documents in electronic form. HTML created a notation for hypertext that has become the global standard, and provided the basis for the standardized linking and display of documents independent of the platform, operating system, and application in which they were created.” (Janet Murray, *[Inventing the Medium: Principles of Interaction Design as a Cultural Practice](https://mitpress.mit.edu/9780262016148/inventing-the-medium/)*, pp. 424)

**Tag**
- “A heading in a web page as indexing, structural, or formatting terms. Formatting tags identify structural parts of a document, such as <heading> or display <italics>.” (Janet Murray, *[Inventing the Medium: Principles of Interaction Design as a Cultural Practice](https://mitpress.mit.edu/9780262016148/inventing-the-medium/)*, pp. 440)

**Cascading Style Sheets (CSS)**
- "Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language such as HTML or XML" ([Wikipedia](https://en.wikipedia.org/wiki/CSS))

[Click here](https://github.com/kwaldenphd/internet/blob/main/key-terms.md) for a full list of key terms and definitions for this lab.

## Comprehension Check

<table>
 <tr><td>
<img src="https://www.freeiconspng.com/thumbs/survey-icon/survey-icon-12.png" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLScQoRbyDYB2Cisg_AmfMhUqj8qXn0ZbeuembRhQpOnbb64I2g/viewform?usp=sf_link">The WWW Comprehension Check</a></td>
  </tr>
  </table>

WWW/Internet distinction

Describe hypertext concept in your own words

Describe markup language in your own words

## Application

BUILDING A WEBSITE

# Additional Resources

Conceptual and technical foundations:
- Article 19 and Catnip, *[How the Internet Really Works: An Illustrated Guide to Protocols, Privacy, Censorship, and Governance](https://catnip.article19.org/)* (No Starch Press, 2021. ISBN: 9781718500297). [Link to access through ND Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph006167953).
- Tim Berners-Lee, "[Information Management: A Proposal](https://www.w3.org/History/1989/proposal.html)", 1990.
- J.C.R. Licklider and Robert W. Taylor, "[The Computer as a Communication Device](http://memex.org/licklider.pdf)," Science and Technology, April 1968.
- V. Cerf and R. Kahn, "[A Protocol for Packet Network Intercommunication](https://doi-org.proxy.library.nd.edu/10.1109/TCOM.1974.1092259)," in IEEE Transactions on Communications, vol. 22, no. 5, pp. 637-648, May 1974.

Markup languages and HTML:
- James H. Coombs, Allen H. Renear, Steven J. DeRose. (November 1987). "[Markup systems and the future of scholarly text processing](http://xml.coverpages.org/coombs.html)". *Communications of the ACM* 30 (11): 933–947.
- Tim Bray. (April 2003). "On Semantics and Markup, Taxonomy of Markup". [www.tbray.org/ongoing](http://www.tbray.org/ongoing).
- W3C, “[Extensible Markup Language (XML)](https://www.w3.org/TR/xml11/)” (16 August 2006)
- Web Hypertext Application Technology Working Group, “[HTML Living Standard](https://html.spec.whatwg.org/)” (September 2020)
- Angela M. Haas, “[Wampum as Hypertext: An American Indian Tradition of Multimedia Theory and Practice](https://muse-jhu-edu.proxy.library.nd.edu/article/235980),” *Studies in American Indian Literatures* 19: 4 (2007).

Cultural histories of the internet:
- Janet Abbate, *[Inventing the Internet](https://mitpress.mit.edu/9780262011723/inventing-the-internet/)* (MIT Press, 1999. ISBN: 0262511150). [Link to access through ND Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_cdi_askewsholts_vlebooks_9780262266703).
- Paolo Bory, *The Internet Myth: From the Internet Imaginary to Network Ideologies* (University of Westminster Press, 2020). [Link to access through ND Libraries](https://onesearch.library.nd.edu/permalink/f/7uudnk/TN_doab46271).
- Timelines
  *  Barry Leiner, et al, "[Brief History of the Internet](https://www.internetsociety.org/internet/history-internet/brief-history-internet/)" *Internet Society* (1997)
  *  Gil Press, "[A Very Short History of the Internet and the Web](https://www.forbes.com/sites/gilpress/2015/01/02/a-very-short-history-of-the-internet-and-the-web-2/#2ea43af67a4e)" *Forbes* (2 January 2015)

Identity and power in online spaces:
- Safiya Umoja Noble, *[Algorithms of Oppression: How Search Engines Reinforce Racism](https://nyupress.org/9781479837243/algorithms-of-oppression/)* (NYU Press, 2019). [Link to access through ND Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005505291).
- Safiya Umoja Noble and Brendesha M. Tynes, eds., *[The Intersectional Internet: Race, Sex, Class, and Culture Online](https://www.peterlang.com/document/1109657)* (Peter Lang, 2016). [Link to access through ND Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph006132751).
- Lisa Nakamura and Peter Chow-White, eds, *Race After the Internet* (Routledge, 2013). [Link to access through ND Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005788357).
- Marisa Elena Duarte, *Network Sovereignty: Building the Internet Across Indian Country* (University of Washington Press, 2017). [Link to access through ND Libraries](https://onesearch.library.nd.edu/permalink/f/1phik6l/ndu_aleph005407182).

# Lab Notebook Questions

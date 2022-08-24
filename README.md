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
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSexiph4YBLk_cvOK6dt0C_4qfiFZ0RfvxUYJFWFdL83msZo_g/viewform?usp=sf_link">Computer Networks Comprehension Check</a></td>
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

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/OSI_Model.png?raw=true" width="500"></p>

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
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSdcKWzqImWVevjXXv766giq0E3xwbdsEHV1OvkZmt4YIVhbag/viewform?usp=sf_link">The Internet Comprehension Check</a></td>
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

<p align="center"><img src="https://github.com/kwaldenphd/internet/blob/main/images/WWW_Berners_Lee.png?raw=true" width="500"></p>

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
<img src="https://github.com/kwaldenphd/internet/blob/main/images/clipboard.png?raw=true" alt="Clipboard icon" width="50"/></td>
  <td><a href="https://docs.google.com/forms/d/e/1FAIpQLSec8RlhNcj9YKG6Fliv3LBm35y4fhO_-mcENs1Vvfe5aHJ6Mw/viewform?usp=sf_link">The WWW Comprehension Check</a></td>
  </tr>
  </table>

WWW/Internet distinction

Describe hypertext concept in your own words

Describe markup language in your own words

## Application

### Well-Formed HTML

Create a `.txt` file on your computer and add the text listed below. Save the file as `hello-world.html` and open it in a web browser.

```HTML
<html>
<body>Hello World</body>
</html>
```

This is a very basic HTML document. The HTML tags `<HTML>` identify this document as a html document. The body tags `<body>` enclose the content that will be visible on the page. You should see just the text “Hello World!” The browser has translated the HTML tags and returned only the text.

`hello-world.html` contains the minimum requirements for an HTML document. However, it is best practice to create a HTML document that is “well formed,” that is, that it follows all of the grammar, vocabulary, and syntax rules of html. We can check the well-formed-ness of this document in a validator like the [W3C Markup Validation Service](https://validator.w3.org). 

Head to the W3C validator and click on “Validate by Direct Input” and copy and paste the code above into the validator and click `check`. You should receive a few errors. 
- [W3Schools, "HTML head tag"](https://www.w3schools.com/tags/tag_head.asp)
- [W3Schools, "HTML !DOCTYPE Declaration"](https://www.w3schools.com/tags/tag_doctype.asp)
- [W3Schools, "HTML ISO Language Codes"](https://www.w3schools.com/tags/ref_language_codes.asp)
  
HTML is pretty forgiving, but other languages are not, so it’s best to practice following all of the rules from the start. Navigate to your Replit workspace for this lab and open the `index.html` document.

<table>
 <tr><td>
<img src="https://elearn.southampton.ac.uk/wp-content/blogs.dir/sites/64/2021/04/PanPan.png" alt="Panopto logo" width="50"/></td>
<td><a href="https://notredame.hosted.panopto.com/Panopto/Pages/Viewer.aspx?id=03112275-fe69-4b36-85e5-aef50171900c">IDE Overview & Getting Started With Replit</a></td>
  </tr>
  </table>

FIG A

Comments are indicated by `<!-- and -->` and are written for the user (not the computer). These special start and end tags tell the computer to ignore what follows. Comments are used to include instructions and explanations about the code in a human-readable form. You can use comments throughout your code to leave notes for yourself or describe what the code is doing (or what you want it to do).

A few other pieces of information Replit has added to this page so we have valid, well-formed HTML:
- The `<!DOCTYPE` declaration tells the computer this is an HTML document
- The opening `<html>` tag marks the start of the page/document
- We also have additional information like XHTML specification, namespace, and document language (`en`)

### Building Web Pages

PAGE DIAGRAM

Now that we have a template for a valid, well-formed HTML page, we can start adding content to the page. Between the `<head>` tags you will see a set of `<title>` tags. The `<head>` of the document is reserved for metadata, but also includes the `<title>` of the page which is represented in the tabs in some web browsers. 

```html
  <head>
    <title>YOUR PAGE TITLES GOES HERE</title>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
  </head>
```

Replace `YOUR PAGE TITLE GOES HERE` between the `<title>` tags to give your document a new title. Click `Run` to see the updated page.

Now, let’s modify the body. This is where the content that we will see in the web browser is entered. HTML uses a number of different formatting tags. You can use the W3Schools's ["HTML Reference"](https://www.w3schools.com/tags/default.asp) to browse through some of the different options. 

For now, we’ll use `<h1>` (heading 1) and `<p>` (paragraph). After the first `<body>` tag, place a `<h1>` tag on a new line. 

A couple things to notice:
- The line is indented. This isn’t a requirement of HTML, but it is a convention that is used by coders to write cleaner code. The indentation allows you to easily determine what tags are nested within each other. For example, the `<title>` and `<meta>` tags are nested within the `<head>` tags. Now, our `<h1>` is nested within the `<body>`. The use of the tabs simply makes the code easier for us to read, but the computer doesn’t care (with Python the indentation is important and will cause errors if the indents do not appear in the right place).
- Repl.it has completed your `<h1>` with a closing `</h1>` tag. The closing tag is not required for all HTML tags, but it is good practice to close all of your tags. This is a good example. Without a closing tag, everything that follows will be formatted as a `<h1>`. Some IDEs include an auto-complete function to help you prevent errors in your code and create valid documents.

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_5.jpg?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_5.jpg?raw=true" /></a></p>

Go ahead and enter some content between the `<h1>` tags. `<h1>` is preformatted as first level heading text. We’ll see how it looks in a minute. 

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_6.jpg?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_6.jpg?raw=true" /></a></p>

Next add a `<p>` tag and type some text. `<p>` tags are preformatted as paragraphs with padding between paragraphs.

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_J.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_J.png?raw=true" /></a></p>

Repl.it has another function that will be helpful as we develop our websites. Click the `Run` button and your `.html` document will display in Replit's web browser.

<blockquote>Repl.it will auto-save your work (like Google Docs). For other IDEs, you can press <code>Control + S</code> to save file updates.</blockquote>

<blockquote><h1>Why <code>index.html</code>?</h1><br><code>index.html</code> is the name of the default landing page for websites. The web server (the computer hosing the site) will automatically recognize <code>index.html</code> as the first page or the home page of a website. Some servers use other variations like <code>home.html</code>, but we’ll use <code>index.html</code>.</blockquote>

We have just created is a single web page. To build a web site, we likely want multiple pages of linked content. 

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_L.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_L.png?raw=true" /></a></p>

Let’s create a second `.html` file by clicking on the `+` "Add File" icon in the upper left-hand corner. Save this file as `page2.html`. 

We can copy the HTML from `index.html` to make sure we're starting with an HTML document that is well-formed and valid.

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_K.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_K.png?raw=true" /></a></p>

Add some content to your second page, starting with a title, `<h1>` and `<p>` tags. 

### Linking Web Pages

Now, let’s add a link to the second page on our `index.html` page. We add links with the `<a>` tag and the `href` attribute. The `a` tag defines a hyperlink, and the `href` attribute shows the link destination.`<a href>` tag. This tag allows us to link pages in the same website and link out to pages that exist on external websites.

The tag syntax is as follows: `<a href="URL to page">Text that will appear as the link</a>`. 
  
Below your paragraph tag on the `index.html` page add the line `<a href=”page2.html”>Link to page 2</a>.`
- Learn more about the `<a href>` tag via W3Schools: http://www.w3schools.com/TAGS/att_a_href.asp

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_10.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_10.png?raw=true" /></a></p>

Run `index.html` to see the updated file with a link. When you click on “Link to page 2” your `page2.html` file should open. In this case, our URL to the page in our `<a href>` tags is just the name of new page we created. We do not need a full URL (http://www.somewhere.com) because we are calling a file that is stored in the same directory on our server (the repl).
- NOTE: If your link is not working, try re-typing the quotation marks around the destination link.

If we had saved this file to another folder or directory, we would need to include the full file path, including any directory information. For example if we had put `page2.html` in a folder titled "pages," the `a href` tag would look like `<a href="pages/page2.html">`.

### Adding Images

Let’s add an image to the `index.html` page. 

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_I.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_I.png?raw=true" /></a></p>

Find an image that you like on the web, save it to your local computer, and upload the file to your repl. 

The `<img>` tag is very similar to the `<a href>` tag that we just used. It has two required attributes:
- `src` or the source
-  `alt` or the alternative text for the image

`src` can be a local file or a URL to an image on the web, just like the href attribute in the `<a href>` tag. `alt` is for the alternative text or the text that is displayed for screen readers or browsers that don’t support images. 

<blockquote>Learn more about the <code>img</code> tag via <a href="http://www.w3schools.com/tags/tag_img.asp">W3Schools</a>.</blockquote>

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_M.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Fig_M.png?raw=true" /></a></p>

On your `index.html` page, add the line `<img src="imagefilename" alt=Description of image>` in the `<body>`. Be sure to use your image file name in place of the italicized text above. 

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_12.jpg?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_12.jpg?raw=true" /></a></p>

View the page in the Replit browser (using `Run`) to see if the image has loaded correctly.

At this point, our website project only has one image. If we end up using multiple images, we might want to put all the images files in an `images` folder.

Create an `images` folder and move your single image file into the folder. What happens when you hit `Run`? What would you need to modify in the HTML to correctly display this image?
- HINT: Think about absolute versus relative file paths.

### Building Tables

HTML uses a few core tags for web pages that include tables.
- `table` (marks the start and end of a table
- `tbody` (marks the start and end of the table body)
- `tr` (marks the start and end of each table row)
- `th` (marks the start and end of each column in the first row of the table)
- `td` (marks the start and end of each column after the first row of the table)

How we might see those tags combined in a table structure:

```HTML
<table>
 <tr>
  <th>First Column Header</th>
  <th>Second Column Header</th>
  <th>Third Column Header</th>
 </tr>
 <tr>
  <td>Data in first column/first row</td>
  <td>Data in second column/first row</td>
  <td>Data in third column/first row</td>
 </tr>
 <tr>
  <td>Data in first column/second row</td>
  <td>Data in second column/second row</td>
  <td>Data in third column/second row</td>
 </tr>
</table>
```

The output of that HTML would look like:

<table>
 <tr>
  <th>First Column Header</th>
  <th>Second Column Header</th>
  <th>Third Column Header</th>
 </tr>
 <tr>
  <td>Data in first column/first row</td>
  <td>Data in second column/first row</td>
  <td>Data in third column/first row</td>
 </tr>
 <tr>
  <td>Data in first column/second row</td>
  <td>Data in second column/second row</td>
  <td>Data in third column/second row</td>
 </tr>
</table>

Additional attributes like `align`, `style`, etc. can be used with many of these tags. For more on building tables in HTML:
- [W3Schools, "HTML Tables"](https://www.w3schools.com/html/html_tables.asp)
- [W3Schools, "HTML table tag"](https://www.w3schools.com/tags/tag_table.asp)

Add a table to one of your HTML pages (index.html or page2.html). You could create fictional data or add meaningful data from another source.

### Style & Formatting

HTML allows us to add style to our pages internally, or inline, using HTML tags. We’ve already styled our pages a bit using the `<h1>` tag. `<h1>` designates preformatted text that is larger than the `<p>` or paragraph text. But, what if we want to add color or change the font on our page? 

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_13.jpg?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_13.jpg?raw=true" /></a></p>

We can add style to individual HTML element tags using `style` attributes. The syntax for style attributes is `style="STYLE_PROPERTY:PROPERTY_VALUE;"`

For example, if we wanted text characters in the `H1` tag to be blue and center aligned:
```HTML
 <h1 style="color:blue; text-align:center;">Hello World!</h1>
```

And if we wanted text in the `p` tag to have a light blue background and a different font:
```HTML
 <p style="background-color:powderblue; font-family:courier;">This is my first HTML page.</p>
```

All style elements are enclosed in quotation marks and include a semicolon after each element. To put that all together:

```HTML
<body>
 <h1 style="color:blue; text-align:center;">Hello World!</h1>
 <p style="background-color:powderblue; font-family:courier;">This is my first HTML page.</p>
</body>
```

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_14.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_14.png?raw=true" /></a></p>

We can see how the style attributes are changing how the web page content displays:
- The `<h1>` heading has has a blue text color and is center-aligned
- The `<p>` content has a powder blue background color and Courier font

For more on HTML styles:
- HTML Styles: https://www.w3schools.com/html/html_styles.asp
- HTML Colors: https://www.w3schools.com/html/html_colors.asp

Take a look at the W3Schools [HTML Colors](https://www.w3schools.com/html/html_colors.asp) page. See anything familiar? HTML supports multiple formats for representing color.

If you haven't already, experiment with modifying your existing HTML pages to include some of these (or other) style elements.

#### Cascading Style Sheets (CSS)

You can customize HTML using style attributes, but imagine you want all instances of the `<h1>` or `<p>` tag in your website to have the same formatting. Doing this with `style` would require adding code every time you use these elements.

Cascading Style Sheets (CSS) provides a more elegant way to add these style attributes across the pages in our site. For those familiar with website-building tools like WordPress, Weebly, or Wix, CSS is a main part of how different site "themes" are managed. 
- For more on CSS: https://www.w3schools.com/css/css_intro.asp

Let’s create a simple external CSS for our site. The CSS is cascading because there is a hierarchy to the way that styles are applied. 

If styles are defined within the document (as in the previous example), then they are applied before those in the stylesheet. This lets us override the stylsheet if there is particular content that we would like to style differently.

Open the `style.css` file already in your repl. The CSS file doesn’t contain any content, it only defines the styles for the various elements in HTML files. 

<p align="center"><a href="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_15.png?raw=true"><img class="aligncenter" src="https://github.com/kwaldenphd/HTML-CSS/blob/master/images/Image_15.png?raw=true" /></a></p>

Let's get started by adding a few styles for the background, `<h1>`, and `<p>`. Each tag is defined first- these are referred to as the selectors. 

Our style instructions for each tag are enclosed in `{ }`. These are called declarations. We can add as many style declarations as we would like in between the brackets, separating each with a semicolon. Each declaration has a property followed by a colon and then a value. 

It is common practice to place each declaration on a new line and to indent the declarations, but this is only to make the file easier for us to read and edit. The spacing has no impact on how the computer reads and interprets the code.

Putting that all together:

```CSS
body {
 background-color: lightblue;
 }
 
h1 {
 color: white;
 text-align: center;
}

p {
 font-family: courier;
 font-size: 20px;
}
```

This CSS sample has three declarations (`body`, `h1`, `p`), and each declaration has at least one property (`background-color`, `color`, `text-align`, etc).

Now we need to link the CSS to any HTML file where we want the style sheet to apply. This connection is called a reference. Each HTML page must reference the CSS to apply it to the page. 

We create this reference in the `<head>` of the HTML document with the other metadata. In the `<head>` of `index.html` add the reference `<link rel="stylesheet" type="text/css" href="mystyle.css">`.

```HTML
<head>
 <title>Page Title</title>
 <link rel="stylesheet" type="text/css" href="style.css">
```

This line can appear anywhere between the `<head>` and `</head>`. 
- The `<link>` tag is another way to create links to other documents. 
- In this case the `rel` attribute defines the relationship between the HTML file and the linking document. 
- The `type` defines the type and `href` contains the URL or location reference for the file.
  * To learn more about the `<link rel>` tag: http://www.w3schools.com/tags/att_link_rel.asp

THIS FIG STAYS

IMAGE 17

Run the `index.html` file in the Replit browser to see the updated CSS. However, if you click on the link to `page2.html`, it will look the same as it did before. This is because we need to link the stylesheet to each of the pages. Add the same `<link rel="stylesheet" type="text/css" href="mystyle.css">` to `page2.html`. Now both pages should share the same style.

If you haven't already, experiment with creating a CSS and linking it to your HTML pages.

## Putting It All Together

Now, it’s time to build your own website. The lab procedure has covered the tools you can use to get started, but you can also expand on what you've learned using the W3Schools HTML and CSS resources and documentation (be sure to cite resources you consult or reference- a list of URLs is fine). You're welcome to use or reuse the HTML/CSS content you created in the last section of the lab.

For now, your site needs to fit a few minimum requirements. First, the theme. Choose at least three media items—these can be books, articles, podcasts, films, songs, etc. Ideally, these three (or more) items will have something in common, but that connection is up to you.

Next, you are going to build a website about these items. You need to meet the following requirements:
- You need a landing page (`index.html`) that describes the items and provides a brief introduction to your site. For example, if you are presenting books from your favorite author you could provide a brief into to the author here. It doesn’t need to be extensive, but you want to include some content. Your landing page should also include some logo or image.
- The landing page (`index.html`) must also link to three different pages, one for each of the items you have chosen. 
- Each of the item pages must include:
  * A short description of the item. You may pull this description from another source (publisher, archives, Wikipedia), just be sure to cite the source and if possible provide a link.
  * A link to some related source on the web (Wikipedia, YouTube video, etc) If you’ve pulled your description from another source, then the link to this source can serve as the link.
  * A representative image (with a caption/credit and `alt` text)

- The site also needs to include at least one table built in HTML (could be on any page)
- You will also need a CSS for your site. The CSS will be used across all pages of content to standardize the look and feel of your site.

That’s it. You are free to be as creative as you’d like as long as you meet these requirements. As you design your site, the W3Schools [HTML](http://www.w3schools.com/html/) and [CSS](http://www.w3schools.com/css/default.asp) includes tutorials or sample code tutorials for menus, tables, and other elements you could add to your site. Feel free to borrow code and CSS you find on the web (be sure to provide a link back to sources). Have fun and experiment!

All the materials for your website (`.html`, `.css`, and image files) can be submitted on Canvas as a single `.zip` folder on Canvas, along with your answers to lab notebook questions.

You can download the entire Replit project by clicking on the "Download as Zip" option under the three dots next to "Files" on the left-hand side of the page.

Also include a link to your Replit project workspace. This link is the URL that is active in your browser when you are working on this project in Replit.
- Link template: `https://replit.com/@USERNAME/PROJECTNAME`
- The link you copy in from Replit should include your username, followed by the project name

BULDING A WEBSITE- COLLABORATIVELY/AS GROUP

## Additional Resources

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

QX: Something with network specs

QX: Something with traceroute

QX: Website

QX: Have you ever created a website before? Have you used a program like WordPress, Weebly, SquareSpace, or Wix? How is this process different? Reflect on the process of creating a website by working directly with the HTML.

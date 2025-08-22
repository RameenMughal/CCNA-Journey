# Module 1: Networking Today

## 1.0. Introduction

### 1.0.2 What will I learn to do in this module?

**Module Objective**: Explain the advances in modern network technologies.

<img width="587" height="357" alt="image" src="https://github.com/user-attachments/assets/b42b0f50-e2bb-4025-86d4-7139d82b88cb" />

### 1.0.4 Video - Getting Started in Cisco Packet Tracer

Packet Tracer is a tool that allows you to simulate real networks. It provides three main menus:
- You can add devices and connect them via cables or wireless.
- You can select, delete, inspect, label, and group components within your network.
- You can manage your network by opening an existing/sample network, saving your current network, and modifying your user profile or preferences.

The Open, Save, Save As, and Exit commands work as they would for any program, but there are two commands that are special to Packet Tracer.

The Open Samples command will display a directory of prebuilt examples of features and configurations of various network and Internet of Things devices included within Packet Tracer.

The Exit and Logout command will remove the registration information for this copy of Packet Tracer and require the next user of this copy of Packet Tracer to do the login procedure again.

Basically, Open Samples is for exploring ready-made network examples, while Exit and Logout is for ending your session and clearing your login information.

## 1.1. Networks Affect our Lives

### 1.1.1 Networks Connect Us

In today’s world, through the use of networks, we are connected like never before. 

People with ideas can communicate instantly with others to make those ideas a reality. News events and discoveries are known worldwide in seconds. Individuals can even connect and play games with friends separated by oceans and continents.

### 1.1.3 No Boundaries

The internet has changed the manner in which our social, commercial, political, and personal interactions occur. The immediate nature of communications over the internet encourages the creation of global communities. Global communities allow for social interaction that is independent of location or time zone.

The creation of the cloud lets us store documents and pictures and access them anywhere, anytime. So whether we are on a train, in a park, or standing on top of a mountain, we can seamlessly access our data and applications on any device.

## 1.2. Network Components

### 1.2.1 Host Roles

If you want to be a part of a global online community, your computer, tablet, or smart phone must first be connected to a network. That network must be connected to the internet. This topic discusses the parts of a network.

All computers that are connected to a network and participate directly in network communication are classified as hosts. Hosts can be called end devices. Some hosts are also called clients. 

However, the term hosts specifically refers to devices on the network that are assigned a number for communication purposes. This number identifies the host within a particular network. This number is called the Internet Protocol (IP) address. An IP address identifies the host and the network to which the host is attached.

Servers are computers with software that allow them to provide information, like email or web pages, to other end devices on the network. Each service requires separate server software. 

For example, a server requires web server software in order to provide web services to the network. A computer with server software can provide services simultaneously to many different clients.

As mentioned before, clients are a type of host. Clients have software for requesting and displaying the information obtained from the server, as shown in the figure.

<img width="505" height="149" alt="image" src="https://github.com/user-attachments/assets/bbb7fe91-29d1-4d6d-9fb5-596d3a71c6e9" />

An example of client software is a web browser, like Chrome or FireFox. A single computer can also run multiple types of client software. 

For example, a user can check email and view a web page while instant messaging and listening to an audio stream. 

The table lists three common types of server software.

<img width="617" height="238" alt="image" src="https://github.com/user-attachments/assets/183240cd-2c46-4fd7-bbb2-4ff07c4375b5" />

### 1.2.2 Peer-to-Peer

Client and server software usually run on separate computers, but it is also possible for one computer to be used for both roles at the same time. In small businesses and homes, many computers function as the servers and clients on the network. This type of network is called a peer-to-peer network.

In the figure, the print sharing PC has a Universal Serial Bus (USB) connection to the printer and a network connection, using a network interface card (NIC), to the file sharing PC.

<img width="582" height="148" alt="image" src="https://github.com/user-attachments/assets/ee5a6831-7567-4f2c-b31b-05d82f84c2ed" />

The advantages of peer-to-peer networking:
- Easy to set up
- Less complex
- Lower cost because network devices and dedicated servers may not be required
- Can be used for simple tasks such as transferring files and sharing printers

The disadvantages of peer-to-peer networking:
- No centralized administration
- Not as secure
- Not scalable
- All devices may act as both clients and servers which can slow their performance

### 1.2.3 End Devices

The network devices that people are most familiar with are end devices. To distinguish one end device from another, each end device on a network has an address.

When an end device initiates communication, it uses the address of the destination end device to specify where to deliver the message.

An end device is either the source or destination of a message transmitted over the network.

### 1.2.4 Intermediary Devices

Intermediary devices connect the individual end devices to the network. They can connect multiple individual networks to form an internetwork (interconnected networks). These intermediary devices provide connectivity and ensure that data flows across the network.

Intermediary devices use the destination end device address, in conjunction (together) with information about the network interconnections (how devices are connected with eachother), to determine the path that messages should take through the network. 

Examples of the more common intermediary devices and a list of functions are shown in the figure.

<img width="533" height="149" alt="image" src="https://github.com/user-attachments/assets/dd51ba1f-9b84-4a7c-9d5f-f677ec8d6af3" />

Intermediary network devices perform some or all of these functions:
- Regenerate and retransmit communication signals
- Maintain information about what pathways exist through the network and internetwork
- Notify other devices of errors and communication failures
- Direct data along alternate pathways when there is a link failure
- Classify and direct messages according to priorities
- Permit or deny the flow of data, based on security settings

**Note**: Not shown is a legacy Ethernet hub. An Ethernet hub is also known as a multiport repeater. Repeaters regenerate and retransmit communication signals. Notice that all intermediary devices perform the function of a repeater.

### 1.2.5 Network Media

Communication transmits across a network on media. The media provides the channel over which the message travels from source to destination.

In networking (and communication in general), a channel is the pathway or medium that carries the message from the sender (source) to the receiver (destination).

Modern networks primarily use three types of media to interconnect devices, as shown in the figure:
- **Metal wires within cables** - Data is encoded into electrical impulses.
- **Glass or plastic fibers within cables (fiber-optic cable)** - Data is encoded into pulses of light.
- **Wireless transmission** - Data is encoded via modulation of specific frequencies of electromagnetic waves.

<img width="496" height="345" alt="image" src="https://github.com/user-attachments/assets/b79ba2ff-000b-460d-8b53-ce4cd21c53c4" />

The four main criteria for choosing network media are these:
- What is the maximum distance that the media can successfully carry a signal?
- What is the environment in which the media will be installed?
- What is the amount of data and at what speed must it be transmitted?
- What is the cost of the media and installation?

## 1.3. Network Representations and Topologies

### 1.3.1 Network Representations 

Network architects and administrators must be able to show what their networks will look like. They need to be able to easily see which components connect to other components, where they will be located, and how they will be connected. 

Diagrams of networks often use symbols, like those shown in the figure, to represent the different devices and connections that make up a network.

<img width="497" height="351" alt="image" src="https://github.com/user-attachments/assets/4e8ceaaa-58f4-454b-964e-11ca5c4cb850" />

A diagram provides an easy way to understand how devices connect in a large network. This type of “picture” of a network is known as a topology diagram. The ability to recognize the logical representations of the physical networking components is critical to being able to visualize the organization and operation of a network.

In addition to these representations, specialized terminology is used to describe how each of these devices and media connect to each other:
- **Network Interface Card (NIC)** - A NIC physically connects the end device to the network. It has a unique address (MAC address) that identifies your device.
- **Physical Port** - A connector or outlet on a networking device where the media connects to an end device or another networking device. A physical port is a socket/connector on a device where you plug in a cable.
- **Interface** - Specialized ports on a networking device that connect to individual networks. Because routers connect networks, the ports on a router are referred to as network interfaces. Think of an interface like a bridge — each interface connects one network to another.

**Note**: The terms port and interface are often used interchangeably.

### 1.3.2 Topology Diagrams

Topology diagrams are mandatory documentation for anyone working with a network. They provide a visual map of how the network is connected. 

There are two types of topology diagrams: physical and logical.

#### Physical Topology Diagrams

Physical topology diagrams illustrate the physical location of intermediary devices and cable installation, as shown in the figure. You can see that the rooms in which these devices are located are labeled in this physical topology.

<img width="524" height="338" alt="image" src="https://github.com/user-attachments/assets/d90f2f6d-c6e5-42ec-bc3e-451cc0ea07be" />

#### Logical Topology Diagrams

Logical topology diagrams illustrate devices, ports, and the addressing scheme of the network, as shown in the figure. You can see which end devices are connected to which intermediary devices and what media is being used.

<img width="518" height="358" alt="image" src="https://github.com/user-attachments/assets/8bd55ec3-dfe1-4c02-bf48-4f83884f354a" />

## 1.4. Common Types of Networks

### 1.4.1 Networks of Many Sizes

Networks come in all sizes. They range from simple networks consisting of two computers, to networks connecting millions of devices.

Simple home networks let you share resources, such as printers, documents, pictures, and music, among a few local end devices.

Small office and home office (SOHO) networks allow people to work from home, or a remote office. Many self-employed workers use these types of networks to advertise and sell products, order supplies, and communicate with customers.

Businesses and large organizations use networks to provide consolidation, storage, and access to information on network servers. Networks provide email, instant messaging, and collaboration among employees. Many organizations use their network’s connection to the internet to provide products and services to customers.

The word consolidation generally means: Bringing resources, systems, or services together into a unified structure to improve efficiency, reduce costs, and simplify management.

The internet is the largest network in existence. In fact, the term internet means a “network of networks”. It is a collection of interconnected private and public networks.

In small businesses and homes, many computers function as both the servers and clients on the network. This type of network is called a peer-to-peer network.

### 1.4.2 LANs and WANs

Network infrastructures vary greatly in terms of:
- Size of the area covered
- Number of users connected
- Number and types of services available
- Area of responsibility

The two most common types of network infrastructures are Local Area Networks (LANs), and Wide Area Networks (WANs). 

A LAN is a network infrastructure that provides access to users and end devices in a small geographical area. A LAN is typically used in a department within an enterprise, a home, or a small business network. 

A WAN is a network infrastructure that provides access to other networks over a wide geographical area, which is typically owned and managed by a larger corporation or a telecommunications service provider.

The figure shows LANs connected to a WAN.

<img width="515" height="366" alt="image" src="https://github.com/user-attachments/assets/c6143945-e68e-4ef7-8834-87cbdfdbb78f" />

#### LANs

A LAN is a network infrastructure that spans a small geographical area. LANs have specific characteristics:
- LANs interconnect end devices in a limited area such as a home, school, office building, or campus.
- A LAN is usually administered by a single organization or individual. Administrative control is enforced at the network level and governs the security and access control policies (these are set up by the single organization or individual)
- LANs provide high-speed bandwidth to internal end devices and intermediary devices.

Bandwidth means the maximum amount of data that can be transmitted over a network connection in a given amount of time.

#### WANs

A WAN is a network infrastructure that spans a wide geographical area. WANs are typically managed by service providers (SPs) or Internet Service Providers (ISPs). It is a company or organization that provides access to the Internet to individuals, businesses, and other organizations.

WANs have specific characteristics:
- WANs interconnect LANs over wide geographical areas such as between cities, states, provinces, countries, or continents.
- WANs are usually administered by multiple service providers.
- WANs typically provide slower speed links between LANs.

### 1.4.3 The Internet

The internet is a worldwide collection of interconnected networks (internetworks, or internet for short).

The figure shows one way to view the internet as a collection of interconnected LANs and WANs.

<img width="507" height="325" alt="image" src="https://github.com/user-attachments/assets/eba12f7c-6675-4ac0-a6b2-a9d78e86962e" />

Some of the LAN examples are connected to each other through a WAN connection. WANs are then connected to each other. WANs can connect through copper wires, fiber-optic cables, and wireless transmissions.

The internet is not owned by any individual or group. Ensuring effective communication across this diverse infrastructure requires the application of consistent and commonly recognized technologies and standards as well as the cooperation of many network administration agencies. 

There are organizations that were developed to help maintain the structure and standardization of internet protocols and processes. These organizations include the Internet Engineering Task Force (IETF), Internet Corporation for Assigned Names and Numbers (ICANN), and the Internet Architecture Board (IAB), plus many others.

### 1.4.4 Intranets and Extranets

There are two other terms which are similar to the term internet: intranet and extranet.

Intranet is a term often used to refer to a private connection of LANs and WANs that belongs to an organization. An intranet is designed to be accessible only by the organization's members, employees, or others with authorization.

An organization may use an extranet to provide secure and safe access to individuals who work for a different organization but require access to the organization’s data. Here are some examples of extranets:
- A company that is providing access to outside suppliers and contractors
- A hospital that is providing a booking system to doctors so they can make appointments for their patients
- A local office of education that is providing budget and personnel information to the schools in its district

The figure illustrates the levels of access that different groups have to a company intranet, a company extranet, and the internet.

<img width="494" height="331" alt="image" src="https://github.com/user-attachments/assets/3680d685-7973-46dd-93a0-f9b43a33be9e" />

## 1.5. Internet Connections

### 1.5.1 Internet Access Technologies

How do you actually connect users and organizations to the internet? As you may have guessed, there are many different ways to do this.

Home users, remote workers, and small offices typically require a connection to an ISP to access the internet. Connection options vary greatly between ISPs and geographical locations. However, popular choices include broadband cable, broadband digital subscriber line (DSL), wireless WANs, and mobile services.

Organizations don’t just need their own local network; they also need to connect with their other offices and the wider Internet. To do this, they require fast and reliable connections so that important services like online phone calls (IP phones), video meetings, and large data transfers between data centers work smoothly without lag. This is where Service Providers (SPs) come in. They offer special business-class connections that are more secure, faster, and more dependable than regular home Internet. 

Examples of these services are business DSL (a faster version of DSL for companies), leased lines (dedicated private lines just for one organization), and Metro Ethernet (high-speed connections used in cities to link different offices).

### 1.5.2 Home and Small Office Internet Connections

The figure illustrates common connection options for small office and home office users.

<img width="509" height="299" alt="image" src="https://github.com/user-attachments/assets/cdf48793-2a04-4434-9803-e7d649348c43" />

- **Cable** - Typically offered by cable television service providers, the internet data signal transmits on the same cable that delivers cable television. It provides a high bandwidth, high availability, and an always-on connection to the internet.
- **DSL** - Digital Subscriber Lines also provide high bandwidth, high availability, and an always-on connection to the internet. DSL runs over a telephone line. In general, small office and home office users connect using Asymmetrical DSL (ADSL), which means that the download speed is faster than the upload speed.
- **Cellular** - Cellular internet access uses a cell phone network to connect. Wherever you can get a cellular signal, you can get cellular internet access. Performance is limited by the capabilities of the phone and the cell tower to which it is connected.
- **Satellite** - The availability of satellite internet access is a benefit in those areas that would otherwise have no internet connectivity at all. Satellite dishes require a clear line of sight to the satellite.
- **Dial-up Telephone** - An inexpensive option that uses any phone line and a modem. The low bandwidth provided by a dial-up modem connection is not sufficient for large data transfer, although it is useful for mobile access while traveling.

The choice of connection varies depending on geographical location and service provider availability.

### 1.5.3 Businesses Internet Connections

Corporate connection options differ from home user options. Businesses may require higher bandwidth, dedicated bandwidth, and managed services. Connection options that are available differ depending on the type of service providers located nearby.

The figure illustrates common connection options for businesses.

<img width="501" height="294" alt="image" src="https://github.com/user-attachments/assets/d284811a-c743-4c1a-ac24-32e2aa00c8f6" />

- **Dedicated Leased Line** - Leased lines are reserved circuits within the service provider’s network that connect geographically separated offices for private voice and/or data networking. The circuits are rented at a monthly or yearly rate.
- **Metro Ethernet** - This is sometimes known as Ethernet WAN. In this module, we will refer to it as Metro Ethernet. Metro ethernets extend LAN access technology into the WAN. Ethernet is a LAN technology you will learn about in a later module.
- **Business DSL** - Business DSL is available in various formats. A popular choice is Symmetric Digital Subscriber Line (SDSL) which is similar to the consumer version of DSL but provides uploads and downloads at the same high speeds.
- **Satellite** - Satellite service can provide a connection when a wired solution is not available.

### 1.5.4 The Converging Network

#### Traditional Separate Networks

Consider a school built thirty years ago. Back then, some classrooms were cabled for the data network, telephone network, and video network for televisions. These separate networks could not communicate with each other. 

Each network used different technologies to carry the communication signal. Each network had its own set of rules and standards to ensure successful communication. Multiple services ran on multiple networks.

<img width="502" height="299" alt="image" src="https://github.com/user-attachments/assets/2ae94c2c-90d2-4f8b-af01-b2e979cb53f5" />

#### Converged Networks

Today, the separate data, telephone, and video networks converge. Unlike dedicated networks, converged networks are capable of delivering data, voice, and video between many different types of devices over the same network infrastructure. 

This network infrastructure uses the same set of rules, agreements, and implementation standards. Converged data networks carry multiple services on one network.

<img width="495" height="269" alt="image" src="https://github.com/user-attachments/assets/fece8374-8267-478c-ac6e-0bce0524e495" />

## 1.6. Reliable Networks

### 1.6.1 Network Architecture

Have you ever been busy working online, only to have “the internet go down”? As you know by now, the internet did not go down, you just lost your connection to it. With so many people in the world relying on network access to work and learn, it is imperative that networks are reliable. 

In this context, reliability means more than your connection to the internet. This topic focuses on the four aspects of network reliability.

The role of the network has changed from a data-only network to a system that enables the connections of people, devices, and information in a media-rich, converged network environment. For networks to function efficiently and grow in this type of environment, the network must be built upon a standard network architecture.

Networks also support a wide range of applications and services. They must operate over many different types of cables and devices, which make up the physical infrastructure. 

The term network architecture, in this context, refers to the technologies that support the infrastructure and the programmed services and rules, or protocols, that move data across the network.

As networks evolve, we have learned that there are four basic characteristics that network architects must address to meet user expectations:
- Fault Tolerance
- Scalability
- Quality of Service (QoS)
- Security

### 1.6.2 Fault Tolerance

A fault tolerant network is one that limits the number of affected devices during a failure. It is built to allow quick recovery when such a failure occurs. These networks depend on multiple paths between the source and destination of a message. If one path fails, the messages are instantly sent over a different link. 

Having multiple paths to a destination is known as redundancy.

Implementing a packet-switched network is one way that reliable networks provide redundancy. Packet switching splits traffic into packets that are routed over a shared network. 

A single message, such as an email or a video stream, is broken into multiple message blocks, called packets. Each packet has the necessary addressing information of the source and destination of the message. The routers within the network switch the packets based on the condition of the network at that moment. 

This means that all the packets in a single message could take very different paths to the same destination. In the figure, the user is unaware and unaffected by the router that is dynamically changing the route when a link fails.

<img width="608" height="346" alt="image" src="https://github.com/user-attachments/assets/4ad509f8-cdff-4ecf-9022-b64263cc2975" />

### 1.6.3 Scalability 

A scalable network expands quickly to support new users and applications. It does this without degrading the performance of services that are being accessed by existing users. The figure shows how a new network is easily added to an existing network. 

These networks are scalable because the designers follow accepted standards and protocols. This lets software and hardware vendors focus on improving products and services without having to design a new set of rules for operating within the network.

<img width="502" height="323" alt="image" src="https://github.com/user-attachments/assets/e527430b-c361-4d07-8a7e-5614e13f38de" />

### 1.6.4 Quality of Service

Quality of Service (QoS) is an increasing requirement of networks today. New applications available to users over networks, such as voice and live video transmissions, create higher expectations for the quality of the delivered services. 

As data, voice, and video content continue to converge onto the same network, QoS becomes a primary mechanism for managing congestion (overcrowding) and ensuring reliable delivery of content to all users.

Congestion occurs when the demand for bandwidth exceeds the amount available. Network bandwidth is measured in the number of bits that can be transmitted in a single second, or bits per second (bps). When simultaneous communications are attempted across the network, the demand for network bandwidth can exceed its availability, creating network congestion.

When the volume (amount of data over time) of traffic is greater than what can be transported across the network, devices will hold the packets in memory until resources become available to transmit them. In the figure, one user is requesting a web page, and another is on a phone call. 

With a QoS policy in place, the router can manage the flow of data and voice traffic, giving priority to voice communications if the network experiences congestion.The focus of QoS is to prioritize time-sensitive traffic. The type of traffic, not the content of the traffic, is what is important.

<img width="503" height="308" alt="image" src="https://github.com/user-attachments/assets/ae05c1a8-8a9e-497e-8db1-cfabd55e8db5" />

### 1.6.5 Network Security

The network infrastructure, services, and the data contained on network-attached devices are crucial personal and business assets. Network administrators must address two types of network security concerns: network infrastructure security and information security.

Securing the network infrastructure includes physically securing devices that provide network connectivity and preventing unauthorized access to the management software that resides on them, as shown in the figure.

<img width="503" height="303" alt="image" src="https://github.com/user-attachments/assets/e4bfaf5e-0674-4c31-b3ed-ce8a3da398be" />

Network administrators must also protect the information contained within the packets being transmitted over the network, and the information stored on network attached devices. In order to achieve the goals of network security, there are three primary requirements.
- **Confidentiality** - Data confidentiality means that only the intended and authorized recipients can access and read data.
- **Integrity** - Data integrity assures users that the information has not been altered in transmission, from origin to destination.
- **Availability** - Data availability assures users of timely and reliable access to data services for authorized users.




























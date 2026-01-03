# Packet Tracer - Network Representation

## Objectives

It represents a simplified version of how a small to medium-sized business network might look. 

<div style="text-align: center;">
  <img 
    src="https://github.com/user-attachments/assets/79dff245-d7b2-4d54-813e-4bdebed11fdb"
    alt="image"
    width="700"
  >
</div>

## Instructions

### Part 1: Identify common components of a network as represented in Packet Tracer.

**Question**: List the intermediary device categories.

**Answer**: There are total 6 intermediary device categories:

1. Routers
2. Switches
3. Hubs
4. Wireless Devices
5. Security
6. WAN Emulation

<img width="105" height="68" alt="image" src="https://github.com/user-attachments/assets/43bb25c8-b5d5-4c1b-85cf-46d118ce5e5b" />

---

**Question**: Without entering into the internet cloud or intranet cloud, how many icons in the topology represent endpoint 
devices (only one connection leading to them)?

**Answer**: There are total 15 Endpoints with having 1 connection leading to them.

Endpoint devices are devices with only one connection leading to them (like PCs, laptops, tablets, printers, IP phones). Lets count the endpoint devices from each office:

**Step 1: Home Office**
- PC-PT HomeDesktop → 1 connection
- Laptop-PT HomeLaptop → 1 connection
- Printer-PT Inkjet → 1 connection
- TabletPC-PT Tablet → 1 connection 

**Home Office total**: 4 endpoints

**Step 2: Central Office**
- PC1, PC2, PC3, PC4 → each has 1 connection 

**Central total**: 4 endpoints

**Step 3: Branch Office**
- PC-PT Sales → 1 connection 
- PC-PT Accounting → 1 connection 
- Laptop-PT Guest → 1 connection 
- SMARTPHONE-PT SmartPhone → 1 connection 
- IP Phone0, IP Phone1 → each has 1 connection 
- Printer-PT Laser → 1 connection 

**Branch total**: 7 endpoints

**Step 4: Total Endpoints**

$$
4 (Home) + 4 (Central) + 7 (Branch) = 15
$$

**Note**: A server is an endpoint device, but unlike a normal PC, it can have:
- Multiple network interfaces (NICs)
- Multiple cables connected to it

---

**Question**: Without counting the two clouds, how many icons in the topology represent intermediary devices (multiple 
connections leading to them)?

**Answer**: There are total 11 intermediary devices having multiple connections leading to them

Intermediary devices are devices that connect multiple devices and forward traffic, like routers, switches, APs, etc.

**Step 1: Home Office**
- WRT300N Wireless Router → multiple connections 
- Cable Modem → connects home network to ISP 

**Home Office total**: 2

**Step 2: Central Office**
- 2911 Router (R2) 
- 2960-24TT Switch (S3) 
- 3560-24PS Switch (D1) 
- 3560-24PS Switch (D2) 
- 2960-24TT Switch (S1) 
- 2960-24TT Switch (S2) 

**Central total**: 6

**Step 3: Branch Office**
- 1941 Router (R4) 
- 2960-24TT Switch (S4) 
- Wireless Access Point 

**Branch total**: 3

**Step 4: Total Intermediary Devices**

$$
2 (Home) + 6 (Central) + 3 (Branch) = 11
$$

---

**Question**: How many end devices are not desktop computers?

**Answer**: There are total 10 end devices that are not desktop computers

**Step 1: Home Office**
- Laptop-PT (HomeLaptop) 
- TabletPC-PT (Tablet) 
- Printer-PT (Inkjet) 

**Home Office Total**: 3

**Step 2: Central Office**
- Server-PT (CentralServer)

**Central Office Total**: 1

**Step 3: Branch Office**
- Server-PT (BranchServer) 
- Printer-PT (Laser) 
- Smartphone-PT (Smart Phone) 
- Laptop-PT (Guest) 
- IP Phone 0 
- IP Phone 1 

**Branch Office Total**: 6

**Step 4: Total non-desktop end devices**

$$
3 (Home)+1 (Central)+6 (Branch)=10
$$	

---

**Question**: How many different types of media connections are used in this network topology?

**Answer**: There are total 4 media connections in this network topology.

1. Copper Straight Through (Wired LAN) (Ethernet)
2. Wireless (Wi-Fi)
3. Serial DCE (WAN Links)
4. Coaxial Cable

### Part 2: Explain the purpose of the devices

**Question**: In Packet Tracer, only the Server-PT device can act as a server. Desktop or Laptop PCs cannot act as a server. Based on your studies so far, explain the client-server model. Perform an internet search if needed.

**Answer**: The client–server model is a network model where clients (PCs, laptops) request services and servers provide those services. The server waits for requests, processes them, and sends responses back to the clients. In Packet Tracer, only Server-PT devices can run services (like HTTP, DNS, FTP), while desktops and laptops act only as clients that use those services.

---

**Question**: List at least two functions of intermediary devices.

**Answer**: Intermediary devices are devices that help connect computers and other devices on a network. Two main jobs are:

1. **Directing Data**: They make sure the data goes the right way to reach the correct device (like a router finding the best path).
2. **Helping Network Work Better and Safe**: They can split the network into parts and protect it, so it doesn’t get too crowded and stays secure (like switches and firewalls).

--- 

**Question**: List at least two criteria for choosing a network media type.

**Answer**: Two important criteria for choosing a network media type are:

1. **Speed and Distance**: How fast the network needs to be and how far the data must travel.
2. **Cost**: How much it costs to install and maintain the network media.

---

### Part 3: Compare and contrast LANs and WANs

**Question**: Explain the difference between a LAN and a WAN. Give examples of each.

**Answer**: Following is the difference between LAN and WAN

**LAN (Local Area Network)**:
- Covers a small area, like a home, office, or school.
- Devices are close together and usually connected with cables or Wi-Fi.
- Example: The Wi-Fi network in your home or the computers in a school computer lab.

**WAN (Wide Area Network)**:
- Covers a large area, like a city, country, or even the whole world.
- Connects multiple LANs together over long distances, often using the internet.
- Example: The internet or a company’s network that connects offices in different cities.

In short: LAN = small area, fast connection; WAN = large area, slower connection.

---

**Question**: In the Packet Tracer network, how many WANs do you see?

**Answer**: There are 3 WAN connections:

1. Home Office ↔ Central Office (via Internet)
2. Branch Office ↔ Central Office (via Internet)
3. Branch Office ↔ Central Office (via CloudPT Intranet)

---

**Question**: How many LANs do you see?

**Answer**: There are 3 LANs in this topology diagram:

1. Home Office LAN
2. Central LAN
3. Branch LAN

---

**Question**: The internet in this Packet Tracer network is overly simplified and does not represent the structure and 
form of the real internet. Briefly describe the internet.

<img width="400" height="300" alt="image" src="https://github.com/user-attachments/assets/ae846f8c-c856-4a52-a8ed-1bc64ac7ac13" />

**Answer**: The Internet is a huge global network of networks. It connects millions of smaller networks (like home, school, company, and ISP networks) all over the world.

There is no single owner or central control. Different ISPs (Internet Service Providers) connect to each other using high-speed links and routers.

Data moves across the Internet in packets, choosing the best path to reach its destination using standard rules called protocols (like TCP/IP).

---

**Question**: What are some of the common ways a home user connects to the internet?

**Answer**: Common ways a home user connects to the Internet (easy English):
- Cable Internet – Uses cable TV lines
- DSL (Digital Subscriber Line) – Uses telephone lines
- Fiber – Very fast internet using fiber-optic cables
- Mobile Data (4G/5G) – Internet through a SIM card on phone or hotspot
- Satellite Internet – Uses satellites (common in remote areas)
- Wi-Fi – Connects devices wirelessly through a home router

---

**Question**: What are some common methods that businesses use to connect to the internet in your area?

**Answer**: Common ways businesses connect to the Internet (easy English):
- Fiber-optic connection – Very fast and reliable, used by offices and companies
- Dedicated leased line – Private and stable internet link for businesses
- DSL – Uses phone lines (for small offices)
- Cable Internet – Shared connection, cheaper option
- Wireless ISP (radio link) – Used where fiber is not available
- 4G / 5G backup – Used as a backup if main internet fails




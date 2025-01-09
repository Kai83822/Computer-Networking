## Definitions And Terminologies

End devices connected to a network are called **Host**. They are either the source or destination of a message transmitted over the network. It is a _network node_ that is assigned a unique network address.

A **Server** is a computer/system running the software designed to provide services to other end devices on the network.

A **Client** is a computer/system with software installed that request or display the information obtained from the server.

> E.G Users access their emails (service) by using software on their end devices like Gmail or Outlook, which then communicates with the corresponding email server which provides such services.

A **Peer-To-Peer** Network is a network of interconnected computers/systems (peers) sharing resources directly with one another without relying on a central server.

> BitTorrent is a P2P network that provides file sharing services. Each computer/system in this network acts as both downloader (client) and uploader (server). Meaning each computer/system is simultaneously downloading chunks of the file and uploading chunks of it for peers in the network.

**Intermidiary Network Devices** help connect *hosts with networks* OR individual networks together forming an *internetwork*

> Examples of Intermdiary Network devices include - Routers, wireless access point, firewall appliances etc.

A **Network Interface Media (NIC)** is a circuit board installed in an end device enabling them to connect to a network via a *network media*. The network media is the wired/wireless path that data travels over from source to destination.

# LAN VS. WAN

A **Local Area Network** is a network that links network devices within a small localized area such as a home, office building or campus. It is typically owned and maintained by an individual or organization.

A **Wide Area Network** is a network that spans over a large geographical area such as cities, countries or continents. It connects small networks such as LANs to form a WAN. it is typically owned and maintained by telecommunication companies or Internet Service Providers.

## Comparing LAN. & WAN.

|Features | LAN | WAN |
|---------|-----|-----|
|Size of Interconnection| Interconnect end devices in limited areas | Interconnect LANs over wide geographical areas
|Administer| Single Organization/Individual| Multiple service providers|
|Speed|High-speed bandwidth btw End and Intermediary devices|Slower-speed links btw LANs|
---

## Rules of Communication

All communications have these 3 elemements;
1. Message Source / Sender
2. Destination / Receiver
3. Pathway - Channel where message travels from source to destination

When 2 devices communicate, both must follow the same rules governing the communication (**Protocols**).

Commmon communication protocols meet these requirements:
* Message Encoding
* Message Formatting and Encapsulation
* Message Size
* Message Timing
* Message Delivery Options

### Message Encoding
This involves converting (encoding) the message into an acceptable form of transmission, and then decoding the transmission to interpret the information.

### Message Formatting and Encapsulation
There is a specified format for messages between the source and destination.

The type of format will depend on the type of message and channel used to transmit the data.

The data is then encapsulated with additional information into a specific format called a **frame**. This frame is then sent over the network.

The data is then de-capsulated which is the reverse of Encapsulation to process the original data.

### Message Delivery Options
1. *Unicast*: one-to-one delivery option. Single destination for delivery.
2. *Multicast*: one-to-many delivery option. Target group of host receive message simultaneously.
3. *Broadcast*: one-to-all delivery option. All host in network recei message simultaneously.

### Network Protocols 
For successful network communication, computer and network protocols must interact and work together. 

A group of inter-reated protocols working together to provide a network communication function is called a **protocol suite**.

A protocol suite can be visualised to be a stack of layered protocols.

Layers interacting with each other would be considered protocol interaction. Higher level services depend on the functionality defined by protocols in lower layers. Lower layers are concerned with moving data over the network and providing services to higher levels while higher layers are concerned with the content of the message sent.

💩testing hehe








# Overview
### what is Internet
- basic hardware and software components that make up the Internet
- Internet in terms of a networking infrastructure that provides services to distributed applications

* known as packets in the jargon of computer networks, are then
sent through the network to the destination end system, where they are reassembled
into the original data.

* but the two most prominent types in
today’s Internet are routers and link-layer switches

* The Transmission Control Protocol (TCP) and the Internet Protocol (IP) are two of
the most important protocols in the Internet. 

### What Is a Protocol?

* A protocol defines the format and the order of messages exchanged between two or more communicating entities, as well as 
the actions taken on the transmission and/or receipt of a message or other event.

* Hosts are sometimes further divided into two categories: clients and servers.


### The Network Core

* the mesh of packet switches and links that interconnects the Internet’s end systems

* To send a message from a source end system to a destination end system,the source breaks long messages into smaller 
chunks of data known as packets.Between source and destination, each packet travels through communication links and packet 
switches (for which there are two predominant types, routers and linklayer

* Store-and-Forward Transmission
Most packet switches use store-and-forward transmission at the inputs to the links.

* Queuing Delays and Packet Loss
Each packet switch has multiple links attached to it. For each attached link, the packet switch has an output buffer (also called an output queue), which stores packets that the router is about to send into that link.

### Forwarding Tables and Routing Protocols

  In the Internet, every end system has an address called an IP address. When asource end system wants to send a packet to a 
destination end system, the source includes the destination’s IP address in the packet’s header.
  When a packet arrives at a router in the network, the router examines a portion of the packet’s destination address and forwards
the packet to an adjacent router.
  each router has a forwarding table that maps destination addresses
  When a packet arrives at a router, the router examines the address and searches its forwarding table, using this destination
address, to find the appropriate outbound link.

* Routing protocol
  Internet has a number of special routing protocols that are used to automatically set the forwarding tables. A routing protocol may, for example,determine the shortest path from each router to each destination and use the shortest path results to configure the forwarding tables in the routers.
  
* Circuit Switching  
  
  

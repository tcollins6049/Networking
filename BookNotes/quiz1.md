1) Which of the following is both an end system and a host?
   - a **PC, an internet connected game console, and a PDA** are all examples of both end systems and hosts.
   - *End System* -> Refers to any device connected to the internet that hosts applications or services.
   - *Host* -> A term used to describe a device that has an IP address and can communicate over the network.

2) Provide a matching between the terms and descriptions:
   - The principal protocols of the internet -- **TCP/IP**
   - Protocol that defines the format of a packet -- **IP**
   - Document that contains an IETF standard -- **RFC**
   - Application that consists of more than one software component running on different end systems -- **Distributed applications**
   - Powerful machine that stores and distributes web pages -- **Server**
   - Programming interface that allows sotware components of a distributed application to communicate -- **Socket Interface**
   - Example of an end system that is a client -- **Smartphone**
   
3) The type of packet switch that is typically used within an access network:
   - a. communication link - Refers to the physical or logical connection between two or more devices in a network.
   - c. **link-layer switch** - Operates at the data link layer and is used to forward frames based on MAC address within LAN.
   - access network - Refers to the part of a network that connects end users to the broader network.

4) Order [DSL, cable, FTTH, satellite, dial-up] from fastest to slowest:
   - FTTH (Fiber optic), cable, DSL (phone lines), Satellite, Dial-up
  
5) Which of the following is true about an ethernet network:
   - The physical media between the end system and the ethernet switch is guided. (Guided because often use physical cables to connect devices.)
   - The physical media between the end system and the ethernet switch is twisted pair.

6) The physical medium used by WiFi (Wireless LAN) is:
   - **Terrestrial radio channels** - These signals operate in specific frequency bands  (2.4 GHz and 5 GHz) to transmit data wirelessly within a local area.

7) Matching definitions:
   - **PoP (Point of Presence)** -- Group of routers where a customer ISP connects to a provider ISP.
   - **message** -- The unit of information exchanged between two network applications.
   - **Store-and-forward** -- Protocol in which an entire packet must be recieved by a switch before transmitting any of the bits in the packet.
   - **Packets** -- What messages are broken into by a source end system.
   - **FDM (Frequency Division Multiplexing)** -- Implementation of circuit switching in which the link is divided into seperate frequency bands.
   - **TDM (Time Division Multiplexing)** -- Implementation of circuit switching in which the use of a link is allocated by time.
   - **Forwarding table** -- Table used by a router to determine the outgoing link of a packet to be transmitted.
   - **IP address** -- What is used to index into a forwarding table.
   - **IXP (Internet Exchange Point)** -- Place where ISPs can peer with one another.
   
9) The equation: "d(end-to-end) = N * (L / R)" gives the formula for end to end delay of sending one packet of length L over N links of transmission rate R. Generalize this formula for sending P packets back to back over the N links.
   - First packet takes (N * (L/R)) time but all others take only (L/R) time. So the formula would be: (N * (L/R)) + ((P - 1) * (L/R)) == ((N + P - 1) * (L/R))

10) Suppose users share a 3 Mbps link. Also suppose each user requires 150kbps when transmitting, but each user transmits only 10 percent of the time. When circuit switching is used, how many users can be supported?
    - Number of users = (Total bandwidth / bandwidth per user)
    - (3 * 10^6 bits per/second) / (150 * 10^3 bits per/second) = 20

11) Same as above, what is the probability that a given user is transmitting?
    - A given user is only transmitting 10% of the time so the probability would be 10%.

















   

### 1. Based on Transmission Mode
 Transmission mode defines the direction of signal flow between two linked devices. There are three types of transmission modes.
- **simplex** : In simplex mode, the communication is unidirectional. Among the stations only one can transmit and the other can only receive.
- **Half-Duplex** : In half-Duplex mode, the communication is bidirectional. In this both station can sent and receive but not at the same time.
- **Full-Duplex** : In Full-Duplex mode, both stations can transmit and receive simultaneously

### 2. Based on Time in Transmission Type
- **Synchronous Transmission** : In synchronous Transmission both the sender and the receiver use the same time cycle forthe transmission. We send bits one after another without start/stop bits or gaps. It is the responsibility of the receiver to group the bits. Bit stream is delivered with a fixed delay and given error rate. Each bit reaches the destination with the same time delay after leaving the source.
- **Asynchronous Transmission** : In Asynchronous Transmission we send one start bit at the beginning and one stop bit at the end of each byte. There may be a gap between each byte. Bit stream is divided into packets. Packets are received with varying delays, so packets can arrive out of order. Some packets are not received correctly

### 3. Based on Authentication
- **Peer to Peer Connection** : In peer-to-peer networks, there are no dedicated servers. All the computers are equal and, therefore, are termed as peers. Normally, each computer functions as both a client and a server. No one can control the other computers.
- **Server Based Connection** : Most networks have a dedicated server. A dedicated server is a computer on a network which functions as a server, and cannot be used as a client or a workstation. A dedicated server is optimized to service requests from network clients. A server can control the clients for its services.

### 4. Based on Geographical location
- **Local Area Networks (LAN)** : LAN is a small high speed network. In LAN few numbers of systems are interconnected with networking device to create network. As the distance increases between the nodes or system it speed decreases. So it is limed to few meters only. Networks which cover close geographical area. LAN used to link the devices in a single office, building or campus. It provides high speeds over short distance. Systems are connecting directly to Network. The LAN is owned by private people.
- **Wide Area Network (WAN** : WAN is collection of network (or LAN). This network speed is less than the LAN network speed.WAN network connect systems indirectly. WAN spread over the world may be spread over more than one city country or continent. Systems in this network are connected indirectly. Generally WAN network are slower speed than LAN’s. The WAN network are owned or operated by network providers. If it is owned by a single owner then it is called Enterprise network. Often these types have combination of more than one topology.
- **MAN (Metropolitan Area Network)** : Metropolitan area network is an extension of local area network to spread over the city. It may be a single network or a network in which more than one local area network can share their resources.

### 5. Based on Reliability
Reliability is maintained by authentication
- **Connection-oriented** : This type of communication establishes a session connection before data can be sent. This method is often called a "reliable" network service. It can guarantee that data will arrive in the same order.
- **Connection less** : This type of communication does not require a session connection between sender and receiver for data transfer. The sender simply starts sending packets to the destination. A connectionless network provides minimal services.
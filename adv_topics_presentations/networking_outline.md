# Networking Advanced Topic Presentations

## Presentation 1 (10/14):
-Strucutre of the internet; Regional networks, content provider networks, packets, IP's, TCP/IP Model and OSI network stack, their layers and differences between eachother<br /> 
-Protocols; TCP, Ethernet, HTTP, What is a protocol?<br />
-TCP & UDP; Differences, why we're using TCP, encapsulation of packets, layers of TCP<br />
-Client Side and Server Side; what happens on user side vs on a web server? NAT and IPv4 exhaustion<br />
-How will this relate to our game goals?

## Prsentation 2 (11/13):
#### Talk Structure
	
##### Alec Cantor(15 min):
1. Discuss advantages and disadvantages of p2p vs server/client
   * Peer-to-peer structure
     * Advantages
     * Disadvantages
   * Server/client structure
     * Advantages
     * Disadvantages
2. Discuss why we chose server/client
     * Scalability
     * “Server is law”
       * Elaborated on later
     * Trade offs for errors
       * Bullet missing visually and tank dying
       * Bullet hitting visually and no hit
     *  Standard map generation
        * Host map vs server map 
	
##### Jakob Strobl(15 min):
3. Discuss the actual data packets
   * Creating the Map? 
     * Map Packets
   * What information is being transferred. 
     * Game State Packets 
       * From server->client
       * What does it do?
     * Map State Packets
       * From server->client
       * What does it do?
     * Keyboard Events Packet
       * From client->server
       * What does it do?
4. Discuss the server data is law
      * Sole responsibility is on the server
        * Wherever the server thinks you are, that’s your location.
      * Interpolating movement
        * What do we do in between updates from the server/clients?
      * One example of Client-Server connection during a particular event
        * Player Shooting
          * Or… Player Movement, Player Collision
	
##### Adam Ibrahim (15 min):
5. Discuss receiving protocols (blocking vs non blocking)
   * What is blocking? Non-blocking? Asynchronous?
   * Sockets
     * What are they? - everything is a file
     * Berkeley sockets & POSIX
     * Stream vs datagram -- also mention raw & sequenced packet sockets
     * Socket states in blocking vs nonblocking in different calls(read,write,accept,connect)
     * How do we change a sockets state? 
     * Why does it matter?
6. Discuss multithreading
   * Why multithreading? 
   * How do we synchronize data?
     * readers vs writers
     * Busy waiting vs sleeping
   * Spinlocks - busy
   * Semaphores  & mutex - sleeping
   * Context switching
   * Multithreading in a client
   * Multithreading in a server


## Presentation 3 ():

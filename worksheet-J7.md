# Questions
## Zoe Bogan
1. A packet has a header, which stores the address of a packet, and a payload which stores the data of the packet. 

2. The purpose of an internet layer is to interconnect networks and the way that computers are identified. The client needs to specify the internet protocol address or an ip address. 

3. The transport layer provides abstraction for two porcess to appear as if they are communicating directly with each other. The client needs to specify different ports that are used to differentiate communication for one process versus another. 

4. SMTP is used to transmit email messages and HTTP is used to download web content. 

5. An IP address is an 4-byte number assigned to devices so that routers can determine where to send a packet next. A domain name is used to identify networked devices, however it uses IP addresses.

6. Ports allow the operating system to divide up the data arriving from the network based on the destination process. 

Write code that creates a socket connection to ip address 123.45.678.900 at port 4040. Then, print a color to that socket’s output.

7. 

8. Input stream reads data from a source using ```readLine()``` and output stream writes data to the destination using ```flush()```. 

9. A Socket is used as the client socket in a two way communication with a server. A SocketServer is initialized with the port that is listening for an incoming connect, once that is established a new Socket can be returned to communicate with the client. 

10. Threads are useful to managing multiple programs at the same time. A threaded socket server starts a new thread for each thread so that the main thread can continue to listen to incoming connections.

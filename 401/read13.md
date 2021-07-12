
What does it mean that web sockets are bidirectional? Why is this useful?

Send data from client to server and from the server and client  in a real time without the need for user request , it's useful so the server can respond without making a request (waiting for something to be happen) and the client can listen to server if any updates happen it will be rendered without the need for making a request to render them..

What happens when a client emits an event?
The sharable event with serverwill make be executes

What happens when a server emits an event?
The sharable event with client will make be executes

What happens if a client “misses” an event?
There will be no real time change for this event , we can mitigate this by using message queues

Sockets:
Allow communication between two different processes

Websocket is bidirectional, protocol  used in the same scenario of client-server communication provide a real time communication

Socket.Io is a library that enables real-time, bidirectional and event-based communication

Client: web browser / application / user
Server:machine

Osi model: a model that represent layers of how computer is connected to each other ,
Tcp model : set of standards that represent how two devices should be connected and how data is exchanged between them
Tcp: set of standards that applies when exchanging data over the internet

Udp:is a communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet

Packets:when data is sent over the internet it's divided into small segments called packets

## preview
Talks about how hard was writing an application with lamp technology  so sockets come provideng bi-directional communicatio channel

Socket.Io is composed of two parts:

- 
Note:during development,  `socket.Io`  serves the client automatically for us, as we’ll see, so for now we only have to install one module:  a server that integrates with (or mounts on) the node.Js http server  
-   a client library that loads on the browser side  socket.Io-client
You can call  `join`  to subscribe the socket to a given channel:, its saying that each socket on the server also has a default room if you dont give it based on the id since this is making send a provate message faster




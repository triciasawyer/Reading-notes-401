# Reading notes class 12

## [Web sockets](https://en.wikipedia.org/wiki/WebSocket)

**What is a Web Socket?**

A WebSocket is a communication protocol that provides full-duplex communication channels over a single, persistent connection between a web browser and a server.

**Describe the Web Socket request/response handshake and what happens once the connection is established.**

The WebSocket handshake is a process that occurs between the client (web browser) and the server to establish a WebSocket connection. It involves an initial HTTP-based handshake and, once the connection is established, allows for full-duplex communication over a single, persistent connection.

**Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.**

Request

## [Socket.io tutorial](https://www.tutorialspoint.com/socket.io/)

**What does the event handler io.on() do?**

The io.on() method is used to define event handlers for different events that can occur within the Socket.IO connection. It allows you to listen for specific events emitted by the client or the server and execute custom code in response to those events

**Describe some possible proof of life or proof that the code works as expected.**

You can use console.log() statements within the event handlers to output relevant information to the console. Within the event handlers, you can emit response events back to the client or trigger other events. Also, if your application has a user interface, you can provide visual or interactive feedback to users to indicate that their actions are being processed correctly.

**What does socket.emit() do?**

The socket.emit() method is used to emit a custom event from the server to the connected client. It allows the server to send data or trigger an event on a specific client socket.

## [Socket.io vs web sockets](https://www.educba.com/websocket-vs-socket-io/)

**What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).**

WebSocket is like the underlying protocol, similar to Git, which is a protocol for version control. Git defines the rules and mechanisms for managing code versions and facilitating collaboration between developers.
On the other hand, Socket.IO is like a higher-level library or service built on top of WebSocket, similar to GitHub, which is a platform that provides Git hosting, collaboration tools, and additional features. Socket.IO extends WebSocket functionality and provides additional capabilities and abstractions, making it easier to work with real-time communication.

**When would you use Socket.IO?**

Where real-time, bidirectional communication is required between clients (such as web browsers) and servers. For example, you would use it to develop chat applications where multiple users can exchange messages in real-time. It allows for instant message delivery, typing indicators, and presence notifications. Socket.IO's event-based communication model and room support make it well-suited for building collaborative chat applications.

**When would you use WebSockets?**

Where you need to establish a persistent, low-latency, bidirectional communication channel between a client (such as a web browser) and a server. You would use it if your application requires continuous, real-time data streaming, where WebSockets will provide an efficient solution. It allows the server to push data to the connected clients instantly, ensuring that the clients receive the latest updates. WebSockets are also useful in applications that involve collaborative editing, such as code editors, document editors, or whiteboarding tools. With WebSockets, multiple users can work together in real-time, seeing each other's changes as they happen.

## [OSI model explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

**What are a couple of key takeaways from this video?**

* That an OSI model is made up of 7 protocols: Application, Presentation, Session, Transport, Network, Data Link, and Physical.
* All of these protocols work together to provide a common basis for the coordination of standards development for the purpose of systems interconnection.

## [TCP handshakes explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

**Translate the gist of this video to a non-technical friend.**

Suppose a client wants to get web pages from a server, but before any web page transmission, TCP connection must be established first, through a 3 way handshake. First, the client sends a SYN segment to the server, asking for synchronization (connection). "Hello server, can you open a connection for me?" Then, the server responds with a SYN-ACK, meaning synchronization and acknowledgment, so asks the client to open a connection and acknowledges that connection request from the client. Next, the client replies with ACK, "yes." Then the two way connection is established between them.

## Bookmark and Review

[Socket.io documentation](https://socket.io/docs/v4/)

[Socket.io server API](https://socket.io/docs/v4/server-api)

[Socket.io client API](https://socket.io/docs/v4/client-api)

[Socket testing tool](https://amritb.github.io/socketio-client-tool/)

## Reflection

**What are your learning goals after reading and reviewing the class README?**

To apply a little bit of my knowledge that I now have about socket.io and web sockets. Get some experience coding it out and messing with it.

## Things I want to know more about

# Reading notes class 13

## Socket.io chat example

**Explain to a non-technical recruiter what the Chat Example (above) does.**

**What proof of life are we getting on the backend from the above app?**
A console log with a message saying , "a user connected."

**Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?**
The Broadcast flag (Socket.broadcast.emit('event', 'Message to everyone except me')).

## Rooms

**What is a room and how might a room be useful?**
A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients

**How do you join a room?**
You can call join to subscribe the socket to a given channel

**how do you leave a room?**
To leave a channel you call leave in the same fashion as join.

## Namespaces

**What is a Namespace and what does it allow you to do?**
A namespace is a way to create separate communication channels or scopes within a Socket.IO server. It allows you to group related sockets and events together, providing a logical separation and organization of functionality.

**Each namespace potentially has its own what? (hint: 3 things).**

- Each namespace can have its own set of connected sockets. Sockets within the same namespace can communicate with each other and exchange events, while sockets in different namespaces are isolated and do not directly interact with each other.
- Namespaces can have their own event handlers that are specific to that namespace. You can define different event handlers for each namespace to handle events and perform actions specific to that namespace. This allows for custom logic and behavior within each namespace.
- Namespaces have their own room management system. Rooms in Socket.IO are a way to group sockets within a namespace. Each namespace can have its own set of rooms, allowing you to organize sockets into different groups based on their functionality or purpose. This provides a way to selectively emit events to specific groups of sockets within a namespace.

**Discuss a possible use case for separate namespaces.**
Imagine you are building a real-time application that consists of two main sections, a chat feature and a live auction feature. Both features require real-time communication, but they have distinct functionality and behavior. In this scenario, using separate namespaces can provide a more organized and modular structure to your application.

## Bookmark and Review

[Socket.io emit cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

## Reflection

**What are your learning goals after reading and reviewing the class README?**
To learn about building an event based messaging server.

## Things I want to know more about

# Reading notes class 13

## Socket.io chat example

**Explain to a non-technical recruiter what the Chat Example (above) does.**

**What proof of life are we getting on the backend from the above app?**

**Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?**

## Rooms

**What is a room and how might a room be useful?**

A room is an arbitrary channel that sockets can join and leave. It can be used to broadcast events to a subset of clients

**How do you join a room?**

You can call join to subscribe the socket to a given channel

**how do you leave a room?**
To leave a channel you call leave in the same fashion as join.

## Namespaces

**What is a Namespace and what does it allow you to do?**

**Each namespace potentially has its own what? (hint: 3 things).**

**Discuss a possible use case for separate namespaces.**

## Bookmark and Review

[Socket.io emit cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

## Reflection

**What are your learning goals after reading and reviewing the class README?**

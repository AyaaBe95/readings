# Spring and Sockets

- the process of creating a “Hello, world” application that sends messages back and forth between a browser and a server. 
- WebSocket is a thin, lightweight layer above TCP. This makes it suitable for using “subprotocols” to embed message

## Procese
- server  accepts a message that carries a user’s name. In response, the server will push a greeting into a queue to which the client is subscribed.

## What You Need
Unresolved directive in <stdin> - include::https://raw.githubusercontent.com/spring-guides/getting-started-macros/main/prereq_editor_jdk_buildtools.adoc[]

Unresolved directive in <stdin> - include::https://raw.githubusercontent.com/spring-guides/getting-started-macros/main/how_to_complete_this_guide.adoc[]
  
## Steps
- Spring Initializr
- Adding Dependencies
- Create a Resource Representation Class
- Create a Message-handling Controller
- Configure Spring for STOMP messaging
- Create a Browser Client
- Make the Application Executable

## Test the service
- Now that the service is running, point your browser at http://localhost:8080 and click the Connect button.
- Upon opening a connection, you are asked for your name.
- Enter your name and click Send.
- Your name is sent to the server as a JSON message over STOMP. 
- After a one-second simulated delay, the server sends a message back with a “Hello” greeting that is displayed on the page. 
- At this point, you can send another name or you can click the Disconnect button to close the connection.

# MULTITHREADED-CHAT-APPLICATION

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: GAJJELLY VARSHITHA

*INTERN ID*: CTIS0641

*DOMAIN*: JAVA PROGRAMMING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

##DESCRIPTION

I complied this in Virtual Studio code platform.The objective of this task is to design and implement a multithreaded client-server chat application using Java sockets. The application enables multiple users (clients) to communicate with each other in real time through a centralized server. The system is built using the principles of network programming and multithreading, ensuring efficient and simultaneous communication among connected clients.

In this application, the server acts as the central controller that listens for incoming client connections using the ServerSocket class. The server runs continuously and waits for multiple clients to connect on a specific port number. Whenever a new client connects, the server creates a separate thread for that client using a dedicated client handler class. This multithreaded approach allows the server to handle multiple client connections concurrently without blocking other users.

Each client connects to the server using the Socket class by specifying the server address and port number. Once connected, input and output streams are established using BufferedReader and PrintWriter to enable message transmission. The client application runs two parallel operations: one for sending messages to the server and another for receiving messages from the server. This ensures seamless two-way communication and real-time message exchange.

When a client sends a message, it is transmitted to the server. The server receives the message through the corresponding client thread and then broadcasts it to all other connected clients. To manage active connections, the server maintains a collection of connected clients and iterates through it to forward messages efficiently. The sender’s message is not echoed back to itself, maintaining proper chat behavior.

Multithreading plays a crucial role in this application by allowing each client to operate independently. Even if one client disconnects or becomes inactive, the server continues running and other clients remain unaffected. This improves the reliability and scalability of the application.

The final deliverable of this task is a fully functional chat application consisting of a server program and multiple client programs that can communicate in real time. The application demonstrates core Java concepts such as socket programming, multithreading, client-server architecture, and input/output stream handling. This task serves as a practical implementation of networking concepts and provides a strong foundation for developing more advanced communication-based applications.

##OUTPUT

<img width="1039" height="308" alt="Image" src="https://github.com/user-attachments/assets/a2b8c35e-913e-487a-8bb5-ab1b7b394ec5" />

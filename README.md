# Java-Chatting
This is a simple chatting application implemented in Java using Swing for the graphical user interface and sockets for communication. It consists of a server component and a client component.

## Features

- **Graphical User Interface**: The application provides a user-friendly GUI for chatting.
- **Server-Client Communication**: It allows communication between multiple clients via a central server.
- **Real-time Messaging**: Messages are sent and received in real-time.

## How to Use

### Server

1. Compile the `Server.java` file: `javac chatting/application/Server.java`.
2. Run the server: `java chatting.application.Server`.
3. The server will start listening for client connections on port 6001.

### Client

1. Compile the `Client.java` file: `javac chatting/application/Client.java`.
2. Run the client: `java chatting.application.Client`.
3. Enter the IP address and port number of the server to connect.
4. Start chatting with other connected clients.

## Dependencies

- Java Development Kit (JDK)
- Swing Library

## File Structure

The file structure of the project is as follows:

chatting/
│
├── application/
│ ├── Server.java
│ └── Client.java
│
└── icons/
├── 1.png
├── 3.png
├── 3icon.png
├── phone.png
└── video.png

## License

This project is licensed under the [MIT License](LICENSE).

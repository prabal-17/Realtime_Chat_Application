
# Real-Time Chat Application in Java

This real-time chat application is developed using Java, enabling seamless communication between multiple users. It uses socket programming and multithreading to ensure efficient message delivery and responsiveness.

## Key Features:
- **Multi-User Chat**: Supports multiple clients connecting to the server and exchanging messages simultaneously.
- **Server-Client Architecture**: A central server manages all communication between clients, ensuring real-time message exchange.
- **Private & Group Chats**: Users can send private messages or join group chats visible to all connected clients.
- **Real-Time Messaging**: Instant message delivery ensures a smooth chatting experience.
- **Simple Text-Based Interface**: Easy-to-use and intuitive interface for users to interact.

## Technical Overview:
- **Server**: The server uses multithreading to handle multiple client connections, broadcasting messages to the correct recipients without delays.
- **Client**: Each client connects to the server to send and receive messages in real time.

## Technologies Used:
- **Java**: Used for developing both server and client-side applications.
- **Socket Programming**: Facilitates network communication between clients and the server.
- **Multithreading**: Ensures the server can manage multiple users concurrently without performance issues.

## Getting Started:
1. Clone the repository:
   ```bash
   git clone https://github.com/prabal-17/realtime-chat-app.git
   ```
2. Compile the Java code:
   ```bash
   javac *.java
   ```
3. Start the server:
   ```bash
   java Server
   ```
4. Connect the client:
   ```bash
   java Client
   ```

## Future Enhancements:
- Implementing user authentication for secure access.
- Adding file sharing capabilities.
- Saving and retrieving chat history.

---

This version includes all necessary details while staying within the 350-word limit.
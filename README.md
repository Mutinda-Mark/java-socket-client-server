# Java Socket Client-Server Communication

This project demonstrates a **basic client-server communication model** using Java Sockets. It allows message exchange between a client and a server running on the same machine via TCP/IP using port `5555`.

---

## 🧠 Overview

The goal of this project is to help you understand how distributed systems work through **simple two-way communication** using Java. The client connects to the server, sends messages, receives responses, and ends the conversation when either side types `bye`.

---

## 📁 Project Structure

JavaSocketProject/
├── client/
│ └── MyClient.java
└── server/
└── MyServer.java


---

## 🔧 Requirements

- Java Development Kit (JDK) installed
- A terminal or command prompt
- Git (for cloning, if needed)

---

## 🚀 Getting Started

### 1. Clone the Repository

  ```bash
  git clone https://github.com/Mutinda-Mark/java-socket-client-server.git
  cd java-socket-client-server
```

### 2. Compile the Code
Compile Server:
  ```bash
  cd server
  javac MyServer.java
```
Compile Client:
  ```bash
  cd ../client
  javac MyClient.java
```
### 3. Run the Server
In a terminal window:
   ```bash
    cd server
    java MyServer
```
Output:
Server Initiated, Waiting for Client to Connect...

## 4. Run the Client
In a second terminal window:
  ```bash
  cd client
  java MyClient
```
Output:
Connected to Server, Please type your message and hit Enter to send

---

## Conversation 
Server-side:
![image](https://github.com/user-attachments/assets/55a85fdd-a315-46cf-b0bd-73ae2ba73012)

Client-side:
![image](https://github.com/user-attachments/assets/ccb3fab2-b0ed-4f39-bb9d-af6600fb450a)

💬 Communication Flow
Type messages on the client terminal → server receives and replies
Server's reply is displayed on the client terminal
This continues until either side types bye
Both terminals display Connection Terminated


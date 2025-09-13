Multi-Client TCP Chat System

  A socket-based multi-client chat application built in Python, featuring concurrency with threading. This system allows real-time communication between multiple clients through a central server.

Features

  📡 Multi-client support – multiple clients can connect to the server simultaneously.

  ⏳ Real-time communication – instant message exchange between connected clients.

  🧵 Threaded concurrency – each client connection is handled via Python’s threading module.

  🛡️ Reliable TCP sockets – ensures ordered, loss-free message delivery.

Toolstack

  Language: Python

  Libraries/Modules: socket, threading

Relevance

  This project simulates satellite ↔ ground station communication protocols, mirroring how ISRO and similar organizations establish reliable networking fundamentals in mission-critical systems.

Project Structure

  Multi-Client-TCP-Chat
  
   ┣ 📜 server.py   # Central server to manage client connections
   
   ┣ 📜 client.py   # Client script to connect and chat
   
   ┣ 📜 README.md   # Project documentation

▶️ Usage

  1️⃣ Start the Server

      python server.py

  2️⃣ Run a Client (in a new terminal)

      python client.py


  👉 Multiple clients can be started in separate terminals.

🖼️ Demo
<img width="1365" height="719" alt="Screenshot 2025-09-12 184042" src="https://github.com/user-attachments/assets/947310d1-6bf2-41d2-8bf1-f505075cdb87" />

📚 Learning Outcomes

Fundamentals of socket programming in Python.

Practical application of threading for concurrency.

Understanding real-time communication systems.

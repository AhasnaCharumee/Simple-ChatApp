Here’s a complete `README.md` in **English** for your **Java Socket Programming - Simple Chat Application**, suitable for submitting under your **Network Programming** module with **Udara San Sir**:

---

### ✅ `README.md`

```markdown
# 🗨️ Java Socket Programming - Simple Chat Application

This repository contains a simple chat application built using **Java Socket Programming**. It allows real-time communication between a **Server** and multiple **Clients**, supporting both **text messages** and **image file** transfer.

This project was developed as part of the **Network Programming** module under the guidance of **Udara San Sir**.

---

## 💡 Features

- ✅ Real-time text messaging between client and server
- 🖼️ Image file transfer capability
- 📱 JavaFX GUI for the client interface
- 🔌 Multi-client support on the server
- 🎯 Simple, educational design for learning socket communication

---

## 🛠️ Technologies Used

- Java SE (Standard Edition)
- JavaFX (for GUI)
- Sockets (TCP-based communication)
- Multithreading (for handling multiple clients)
- FXML (for designing UI)

---

## 📂 Project Structure

```
ChatApp/
├── server/
│   └── Server.java
├── client/
│   ├── Client.java
│   ├── ChatController.java
│   └── chatApp.fxml
├── shared/
│   └── FileTransferUtils.java
├── README.md
└── assets/
    └── demo-image.png
```

---

## 🚀 How to Run

1. **Start the Server**
   ```bash
   cd server
   javac Server.java
   java Server
   ```

2. **Run the Client**
   ```bash
   cd client
   javac *.java
   java Client
   ```

> ⚠️ Make sure the server is running before starting the client.

---

## ✉️ Text Message Communication

- Messages typed into the client's text field are sent to the server.
- The server broadcasts the message to all connected clients.
- TextArea updates in real time.

---

## 📸 Image File Transfer

- Client can choose and send an image file.
- Image is read as bytes, sent over socket, and reconstructed on the receiving side.
- Files are saved to a designated `received/` folder.

---

## 🧑‍💻 Author

- Developed by: [Ahasna Charumee]
- Module: Network Programming
- Lecturer: Udara San Sir

---

## 🖼️ Screenshots

![Chat Screenshot](src/main/resources/images/Screenshot%202025-04-30%20055944.png)

---

## 📜 License

This project is open for educational use. Feel free to learn and expand.
```

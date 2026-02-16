# 📶 Bluetooth File Transfer Application

An Android application that enables file transfer between two devices using Bluetooth communication. The app establishes a secure connection where one device acts as a server and the other as a client.

---

## 📌 Aim

To implement a Bluetooth network application that enables file transfer between two Android devices.

---

## 🧠 Description

This Android application establishes a Bluetooth connection between two devices using Bluetooth sockets. One device operates as a server that listens for incoming connections, while the other functions as a client that initiates the connection request.

Once connected, files are transferred using input and output streams, ensuring reliable data communication between devices.

---

## 🛠 Tools & Technologies Used

- Android Studio
- Java
- Android Bluetooth API
- Android SDK
- Emulator / Physical Android Device

---

## ⚙️ Working Principle

1. Enable Bluetooth on both devices.
2. One device starts in server mode (waiting for connection).
3. The second device connects as a client.
4. A Bluetooth socket connection is established.
5. Files are transferred using InputStream and OutputStream.
6. Connection closes safely after successful transfer.

---

## 🚀 Features

- Bluetooth device discovery
- Secure socket-based communication
- Server–Client architecture
- File transfer using streams
- Reliable peer-to-peer communication

---

## 🎯 Result

The application successfully connects two Android devices via Bluetooth and transfers files securely between them using socket communication.

# 🧑‍💻 Auto Attendance Tracker

An automated attendance tracking system built using **C programming** and **socket programming**. This project enables multiple students (clients) to connect to a server and submit their attendance in real time, which is stored in a CSV file.

---

## 📁 Folder Structure

auto-attendance-tracker/
│
├── client.c # Client-side program to send attendance details
├── server.c # Server-side program to collect and log attendance
├── students.csv # Output file where attendance records are stored
└── README.md # Documentation

---

## 🚀 How It Works

1. The server runs on port `65001` and waits for client connections.
2. Students connect as clients and send attendance details in the format:


---

## ⚙️ How to Compile and Run

### Compile

```bash
gcc server.c -o server
gcc client.c -o client
Run Server
./server
Run Client (in another terminal)
./client

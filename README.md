# Face Recognition Attendance System

A C++ and OpenCV-based project for automating attendance tracking using facial recognition technology. This system is designed to detect faces in real-time, store recognized faces, and mark attendance accurately and efficiently.

---

## 💡 Features
- Real-time face detection and recognition via web camera.
- Automatic attendance recording and export.
- Ability to add new faces and manage face data.
- Simple interface for monitoring and controlling attendance.
- Hardware integration with ESP32-CAM for remote face recognition.

---

## 📌 Tech Stack
- **Languages:** C++, Python
- **Libraries:** OpenCV
- **Hardware:** ESP32-CAM, FTDI Programmer
- **Software:** Visual Studio, VS Code, Arduino IDE

---

## 🚀 Live Demo
Not applicable — this project is a desktop and hardware-integrated system.

---

## 🖥️ Software Overview

### 🔴 Web Camera Interface
When you run the system on your local device, the software connects to your web camera.  
It detects faces in real-time, highlights them, and counts the total number of faces in the frame.

![Web Camera](assets/web_camera.png)

---

### 🆕 Detecting New Faces
The system allows adding new faces to the dataset for future recognition.

![Detect New Face](assets/detect_new_face.png)

---

### 📂 Open Attendance Record
Displays the attendance record for all recognized faces.

![Attendance Record](assets/open_attendance.png)

---

### 🗑️ Delete Face Data
Easily delete stored face data from the system.

![Delete Face](assets/delete_face.png)

---

### ℹ️ About Section
Details about the system and its purpose.

![About](assets/about.png)

---

### 🖼️ Known Images
A display of registered face images used for attendance recognition.

![Known Image](assets/known_image.png)

---

## 🔧 Hardware Overview

### 🧰 Required Components
- ESP32-CAM Module
- FTDI Programmer
- Female-to-Female Jumper Wires
- Arduino Nano Cable (Type A USB)

![Hardware Tools](assets/tools.png)
![ESP32-CAM](assets/esp32_cam.png)

---

### 🔗 FTDI — ESP32-CAM Connection Diagram
Illustrates the connection between FTDI Module and ESP32-CAM for flashing and serial communication.

![FTDI Connection](assets/ftdi_connection.png)
![ESP32 Connection](assets/esp32_connection.png)

---

### 💻 ESP32-CAM — Source Code & Upload Process
Program the ESP32-CAM module with the provided source code for remote attendance capture.

![Source Code](assets/source_code.png)
![Upload](assets/upload_code.png)

---

### ✅ ESP32-CAM — Attendance Capture
The ESP32-CAM captures faces remotely and logs attendance automatically.

![Attendance ESP32](assets/esp32_attendance.png)
![Attendance Log](assets/esp32_log.png)

---

### 📄 Show Attendance Records
Display recorded attendance data for review and validation.

![Show Attendance](assets/show_attendance.png)

---

## ⚙️ Algorithm Overview
Visual flow of the face detection and attendance marking process.

![Algorithm](assets/algorithm.png)

---

## 💻 Recommended Tools & Software
- **Visual Studio** (C++ Desktop Environment)  
  [Download](https://visualstudio.microsoft.com/downloads/)
- **Visual Studio Code**  
  [Download](https://code.visualstudio.com/download)
- **Python 3.11.0**  
  [Download](https://www.python.org/downloads/release/python-3110/)
- **Arduino IDE 2.3.2**  
  [Download](https://www.arduino.cc/en/software)

---

✅ **Note:**  
This project combines software and hardware development for an end-to-end face-based attendance system — ideal for classrooms, offices, or secure access control scenarios.

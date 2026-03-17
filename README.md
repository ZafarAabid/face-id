# 🧑‍💻 face-id - Simple Real-Time Face Recognition

[![Download face-id](https://img.shields.io/badge/Download-face--id-brightgreen?style=for-the-badge)](https://github.com/ZafarAabid/face-id/releases)

---

## 📝 What is face-id?

face-id is a lightweight application that recognizes faces in real time. It works with your computer camera and shows you who is in front of it. The system uses FastAPI and WebSockets to process video quickly. It also uses InsightFace, a proven face recognition tool, to identify faces accurately.

This application runs on Windows and uses your computer’s GPU for faster results if available. It works without heavy setup or programming knowledge.

---

## ⚙️ System Requirements

Before you start, make sure your computer meets these needs:

- Windows 10 or later (64-bit)
- Intel or AMD processor with at least 4 cores
- 8 GB of RAM minimum (16 GB recommended)
- A webcam (built-in or USB)
- GPU with NVIDIA CUDA support (optional but recommended for speed)
- Internet connection to download files

If you don’t have a compatible GPU, the program will still work using your processor but may run slower.

---

## 🌐 Topics Used in This Project

This project uses key technologies listed below:

- **cuda, cudnn** — For GPU acceleration  
- **docker** — For containerized running (advanced use)  
- **face-detection, face-recognition** — Core features to detect and identify faces  
- **fastapi, websockets** — To send and receive data with low delay  
- **gpu, nvidia** — To speed up processing with hardware  
- **insightface** — The main engine behind face recognition  
- **onnxruntime, onnxruntime-gpu** — For running AI models efficiently  
- **opencv** — To handle video and camera input  
- **python** — Main programming language behind the app  
- **vanilla-js** — Simple front-end tech to display results  

---

## 🚀 Getting Started

This section guides you step-by-step to download, install, and run face-id on Windows without programming knowledge.

---

### 1. Download face-id

Click the big green button below to visit the official release page. This page has all files you need to get started.

[![Download face-id](https://img.shields.io/badge/Download-face--id-blue?style=for-the-badge)](https://github.com/ZafarAabid/face-id/releases)

On the release page, look for the latest Windows installer file. It usually ends with `.exe`. Click the file to download it to your computer.

---

### 2. Install the program

After downloading the `.exe` file, follow these steps:

- Double-click the downloaded file.
- If Windows asks for permission, click "Yes" to allow installation.
- A setup window will open. Follow the instructions on the screen.
- Choose where to install face-id or keep the default folder.
- Finish the setup by clicking "Install" or "Finish".

The program is ready to use after installation finishes.

---

### 3. Connect your webcam

face-id uses your camera to detect faces. Make sure your webcam is connected and working.

- For built-in cameras, just ensure it is enabled.
- For USB webcams, plug them into a free USB port.

The program will ask for permission to access the camera the first time it runs.

---

### 4. Launch face-id

Find the face-id icon on your desktop or in your Start Menu.

- Double-click the icon to start.
- A small window opens, showing your camera feed.
- The system will automatically detect and recognize faces shown to the camera in real time.

---

### 5. Using face-id

When the application runs:

- Face boxes appear around detected faces.
- Recognized faces show names if known.
- You can add new faces to the database for future recognition (advanced use).

You do not need to configure anything to see the basic detection.

---

### 6. Optional: Enable GPU support

If you have an NVIDIA GPU:

- Make sure your system has CUDA and cuDNN installed.
- The program will detect and use GPU to process video faster.
- Without GPU, the app uses the CPU but runs slower.

If you are unsure about GPU, just start the app. It will work with what is available.

---

## 🎯 Features

- Real-time face detection and recognition
- Supports multiple faces at once
- Uses GPU if available for fast performance
- Simple user interface with live video feed
- Built with reliable open-source components  
- Requires no programming skills to operate

---

## 🛠️ Troubleshooting

**Face detection does not work**

- Check if your webcam is connected.
- Make sure no other app is using the webcam.
- Restart the face-id application.

**Performance is slow**

- Close other programs that use CPU heavily.
- Use an NVIDIA GPU for better speed if available.

**Software won’t start**

- Make sure you ran the installer with administrator rights.
- Check your Windows system for updates.

---

## 📂 File Structure (for curious users)

Installed face-id folder contains:

- `face-id.exe` — Main application file  
- `models/` — AI face recognition files  
- `config/` — Settings files  
- `logs/` — Logs for debugging and errors  

You do not need to change anything here to use the app.

---

## 📊 How face-id Works

face-id captures video from your webcam using OpenCV. It sends the video frames to a built-in FastAPI server. This server uses WebSockets to communicate efficiently.

InsightFace models analyze images and find faces. Recognized faces show names on the screen. Face detection and recognition happen within milliseconds.

---

## 💻 Advanced Users

For users with some experience in programming or AI:

- You can run face-id with Docker for isolated environments.
- Modify configuration files to adjust detection sensitivity.
- Use Python scripts in the source code for customization.
- Inspect WebSocket messages for integration with other systems.

---

## 🔗 Useful Links

Main releases page for downloads:  
https://github.com/ZafarAabid/face-id/releases

Official documentation:  
Check the repository’s wiki or documentation folder for detailed guides.

---

# Download face-id and try it today using this link:  
[https://github.com/ZafarAabid/face-id/releases](https://github.com/ZafarAabid/face-id/releases)
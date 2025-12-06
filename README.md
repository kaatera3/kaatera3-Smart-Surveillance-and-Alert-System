# Smart-Surveillance-and-Alert-System - README

## 📌 Project Overview

This project is a **Smart-Surveillance-and-Alert-System** that uses computer vision and deep learning to detect weapons (such as pistols and rifles) in images or video streams. The system can be used for safety monitoring applications such as CCTV surveillance.

---

## 🚀 Features

* Detects **guns (pistol, rifle, firearm)** in real-time.
* Works with:

  * Images
  * Webcam
  * Recorded videos
  * CCTV/IP camera streams (optional)
* High accuracy and fast inference.
* Option to trigger alert or notification.

---

## 🛠️ Technologies Used

| Component            | Technology                       |
| -------------------- | -------------------------------- |
| Programming Language | Python 3.x                       |
| AI Model             | YOLOv8 (or custom trained model) |
| Frameworks           | PyTorch, OpenCV, Ultralytics     |
| Hardware Support     | CPU / GPU                        |

---

## 📂 Project Structure

```
📁 gun_detection
│── 📁 models
│   └── gun_model.pt
│── 📁 data
│── app.py
│── requirements.txt
│── README.md
```

---

## 🧩 Installation

### 1️⃣ Install Python

Make sure you have **Python 3.8 or above** installed.

### 2️⃣ Install Dependencies

Run:

```
pip install -r requirements.txt
```

If using GPU (optional):

```
pip install torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/cu121
```

---

## ▶️ Usage

### 🔹 Detect from Webcam:

```
python app.py --mode webcam
```

### 🔹 Detect in Image:

```
python app.py --mode image --path test.jpg
```

### 🔹 Detect in Video:

```
python app.py --mode video --path clip.mp4
```

---

## ⚠️ Warning / Disclaimer

This project is for **educational and research purposes only.**
It should not be used for:

* Illegal spying
* Harmful activities
* Misusing surveillance systems

Use responsibly.

---

## 🧑‍💻 Author

Harsha (Gun Detection Project)

---

### 📬 Support

If you need help, improvements, or custom model training, you can ask here.

---

💡 *Stay safe and innovate responsibly!*

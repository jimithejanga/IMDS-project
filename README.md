# IMDS-project
an intelligent malpractice detection system
# 🧠 Intelligent Malpractice Detection System (IMDS)

A lightweight, real-time AI-powered proctoring system for Computer-Based Testing (CBT). IMDS combines webcam-based gaze estimation with object detection to flag potential cheating behaviors without relying on the cloud or high-end hardware. It is optimized for deployment in West Africa and other resource-constrained environments.

---

## 🚀 Key Features

- 👁️ Real-time **gaze tracking** using mobilenetv2 that accepts input of left and right eye which is then concatenated and then used to learn features for on and offscreen gaze
-  **YOLOv8 object detection** to identify unauthorized items (e.g. phones, books)
-  Gaze-controlled **activation** of object detection for accuracy and efficiency
-  Works **offline** on low-end machines (≥ 4GB RAM)
-  Cross-platform: Windows, macOS (M1), and Linux

---

## Technology Stack

| Category       | Stack / Tool                         |
|----------------|--------------------------------------|
| **Language**   | Python 3.9                           |
| **Frameworks** | TensorFlow, Ultralytics (YOLOv8), OpenCV, MediaPipe(opensource software used to get eye landmarks |
| **Runtime**    | CPU-only (no GPU required)           |
| **Deployment** | Local execution (fully offline)      |

---

## 👥 Contributors

- **Philip Toye Joshua** – ai/ml engineer – [@jimithejanga](https://github.com/jimithejanga)  
- **Abdulraheem Balikis** – ai/ml engineer – [@billiraheem](https://github.com/billiraheem)

---

## 🛠 How to Run This Project

### 1. Clone the Repository

```bash
git clone https://github.com/jimithejanga/IMDS-project.git
cd IMDS-project


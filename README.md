🎧 Object Audio Detector

# 📖 Project Overview

This project is an AI-powered Object Detection system with Audio Feedback.
It detects objects in real-time using a camera and provides audio alerts (text-to-speech) for accessibility and assistance.

Useful for:

Visually impaired users

Smart surveillance systems

Hands-free interaction with devices



---

# 🎯 Features

Real-time object detection using YOLOv5 / SSD / Faster R-CNN

Converts detected objects into speech output

Supports multiple objects at once

Works with live camera feed or pre-recorded videos

Cross-platform support (Windows / Linux)



---

# 🛠️ Tech Stack

Python 3.x

Deep Learning Frameworks: PyTorch / TensorFlow

Computer Vision: OpenCV

Object Detection Model: YOLOv5 (pre-trained on COCO dataset)

Text-to-Speech: pyttsx3 / gTTS

Optional Deployment: Streamlit / Flask



---

# 📂 Project Structure

object-audio-detector/
│-- data/
│   │-- sample_videos/
│   │-- test_images/
│-- models/
│   │-- yolov5s.pt
│-- src/
│   │-- detect.py
│   │-- audio_alert.py
│-- requirements.txt
│-- README.md


---

# ⚡ Installation & Setup

1️⃣ Clone the Repository

git clone https://github.com/username/object-audio-detector.git
cd object-audio-detector

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Detector

python src/detect.py --source 0

(Use --source 0 for webcam, --source path/to/video.mp4 for video)


---

# 🔎 How It Works

1. Capture Frame → Video stream from webcam or file


2. Object Detection → YOLOv5 detects objects in real-time


3. Audio Conversion → Detected objects are announced using TTS


4. Output → Audio + bounding boxes displayed




---

# 🎤 Example Output

If the camera sees a dog and a person, the system will say:
“Dog detected. Person detected.”



---

# 🚀 Future Enhancements

Add multi-language audio support

Deploy as a mobile app (TensorFlow Lite)

Optimize for Raspberry Pi / Edge devices

Add custom object training (train YOLO on custom dataset)



---

# 📬 Contact

👤 Your Name

GitHub: 34MOHDIRSHAD

LinkedIn: https://linkedin.com/in/mohd-irshad-

Email: mohdirshadmi36542@gmail.com

# FlappyVision: Human-Motion Controlled Game (Mediapipe · Pygame)

A computer-vision powered Flappy Bird clone using Mediapipe + Python. Move your real body → control the in-game bird. A playful demo of real-time pose estimation, motion detection, and interactive CV systems.

# Table of contents
1. Highlights
2. Demo
3. Tech stack
4. Repository layout
5. Quick start (local)
6. Flow and Architecture
7.  Troubleshooting & gotchas
8.  Contact
9. License

# Highlight
- Real-time pose estimation via Mediapipe Pose
- Jump-detection logic using landmark velocity + displacement
- Fully interactive game loop powered by Pygame
- Clean architecture for CV-to-action mapping
- Great demo for AI + game dev + real-time input engineering

# Demo
As seen on [TikTok](https://www.tiktok.com/@edwinjaya.py/video/7552595072357862674).

# Tech Stack
- Python 3.9
- Mediapipe (Pose Detection)
- OpenCV
- Pygame
- NumPy
- Real-time signal smoothing & motion classification
Tip: The higher you jump, the longer you’ll *probably* last.  

# Repository layout
```
.
├── app.py                
├── game.py      
├── bird.py       
├── pipe.py
├── controller.py
├── assets/                
├── requirements.txt
└── README.md

```
# Quickstart (Local)
## 1️⃣ Create and activate environment 
<code>conda create -n flappyvision python=3.9 <br>
conda activate flappyvision</code>

## 2️⃣ Install dependencies
<code>pip install -r requirements.txt</code>

## 3️⃣ Run the game
<code>python game.py</code>

# Flow and Architecture

# Troubleshooting & Gotchas
- Laggy performance?
  Reduce camera resolution or lower Pygame FPS cap.
- Model not detecting your jumps?
  Ensure good lighting + stand far enough for full-body capture.
- Webcam not accessible?
  Some laptops reserve the camera—close other apps using it.
- Pose jitter causing false jumps?
  Tune the velocity threshold inside pose_detector.py.

# Contact
- LinkedIn: [(Cick Here)](https://www.linkedin.com/in/edwin-jaya/)
- Email: [(Cick Here)](edwinlionaj@gmail.com)
- TikTok: [(Cick Here)](https://www.tiktok.com/@edwinjaya.py)
- Portfolio: [(Cick Here)](https://www.edwinlionajaya.tech/)

# License
MIT License — feel free to use, modify, and build on this project.

⚽ AI-Powered Football Analytics

An AI-powered Computer Vision system for analyzing football match videos using YOLO11, ByteTrack, OpenCV, and HSV color classification.

The system detects and tracks players and the ball, assigns persistent IDs, classifies teams based on jersey colors, and generates an annotated football analytics video.

🚀 Features
👤 Player Detection — Detects football players from video frames using YOLO11.
🆔 Player Tracking — Tracks players across frames using ByteTrack.
🎯 Persistent Player IDs — Assigns consistent IDs to detected players.
👕 Team Classification — Classifies players based on jersey colors using HSV color analysis.
🇺🇿 Uzbekistan Team Detection — Blue jerseys.
🇮🇷 Iran Team Detection — White jerseys.
🧤 Goalkeeper Detection — Light green jerseys.
🟥 Referee Detection — Red jerseys.
⚽ Ball Detection & Tracking — Detects and tracks the football.
☄️ Ball Motion Visualization — Displays a dynamic meteor-style motion effect.
⭕ Player Position Markers — Draws clean visual markers under each player.
🎥 Annotated Video Output — Generates a processed football analytics video.
🧠 Technologies Used
Technology	Purpose
Python	Main programming language
YOLO11	Player and ball detection
ByteTrack	Multi-object tracking
OpenCV	Video processing and visualization
HSV Color Classification	Team and jersey color classification
NumPy	Coordinate and motion calculations
Google Colab	GPU-based processing
🏗️ System Architecture

<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/d6644714-5f93-4031-b7d9-695dba52fb09" />

Football Video
      │
      ▼
YOLO11 Object Detection
      │
      ├───────────────┐
      ▼               ▼
Player Detection    Ball Detection
      │               │
      ▼               ▼
ByteTrack         Ball Tracking
      │               │
      ▼               ▼
Player IDs        Motion Analysis
      │
      ▼
HSV Jersey Classification
      │
      ▼
Team Identification
      │
      ▼
OpenCV Visualization
      │
      ▼
AI Football Analytics Video
🎯 Current Output

The system processes football videos and generates visual analytics including:

UZB 1      IRN 3      UZB 7
   ⭕         ⭕          ⭕


              ⚽☄️

Each detected player receives:

A persistent tracking ID
Team classification
A visual ground marker

The ball is detected and visualized with a dynamic motion effect.

📊 Future Improvements

Planned features include:

📊 Player Heatmaps
⚡ Player Speed Analysis
📏 Distance Covered
⚽ Ball Possession Detection
🔄 Pass Detection
🎯 Shot Detection
🗺️ Tactical Formation Analysis
📈 Advanced Match Statistics Dashboard
⚙️ How It Works
Upload a football match video.
YOLO11 detects players and the ball.
ByteTrack assigns and maintains player IDs.
HSV color analysis identifies teams based on jersey colors.
OpenCV draws player markers, IDs, and ball motion effects.
The processed result is exported as a new video.
🛠️ Installation
pip install ultralytics opencv-python-headless lap numpy

Run the project:

python football_analytics.py
📌 Example Use Cases
Football match analysis
Player tracking
Sports analytics research
Computer Vision projects
AI-based video analysis
Tactical analysis systems
👨‍💻 Author

Ikromjon Tojiboev

Master's Degree in Computer Engineering
AI / Machine Learning / Computer Vision Enthusiast

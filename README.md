# FocusMate+
FocusMate+ is an intelligent, real-time productivity assistant that helps students and professionals stay focused while studying or working.
It uses computer vision, machine learning, and gaze detection via your webcam to track your attention, detect distractions, and provide actionable feedback — all wrapped in a beautiful dark-mode interface.

🚀 Features

🎯 Real-Time Focus Detection – Tracks your gaze and identifies distractions using MediaPipe & YOLOv8.

⏱️ Pomodoro Timer System – Choose burst study durations (e.g., 25 minutes) or custom sessions.

🔔 Distraction Alerts – Subtle audio alerts when your attention drifts for too long.

🎧 Ambient Music Support – Select your own .mp3 for a perfect focus environment.

🌙 Dark Mode UI – Minimalist, modern interface that reduces eye strain.

📊 Detailed Progress Summary – End-of-session stats and progress graphs showing your focus trends.

🧠 Daily Improvement Tracking – Logs your average Focus Scores across sessions automatically.

🧩 Tech Stack

Python 3.10+

OpenCV – video capture & frame processing

MediaPipe FaceMesh – facial landmark & gaze estimation

YOLOv8 (Ultralytics) – phone/object distraction detection

Tkinter – GUI interface

Matplotlib / Pandas – progress visualization & data logging

Pygame – background ambient music

🖥️ How It Works

Launch the app and set your study duration.

Optionally choose an ambient music file to play in the background.

The webcam tracks your gaze direction and checks for phone usage.

The app calculates your Focus Score in real time.

At the end of the session, a summary screen shows your performance and graphs your progress.

📈 Results Visualization

At the end of each session:

View your average focus percentage

See a line chart of your daily progress

Compare performance across sessions

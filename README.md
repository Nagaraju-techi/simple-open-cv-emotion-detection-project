Emotion Detection from Video using Deep Learning 🎭🎥

This project analyzes the emotions of people in a video using DeepFace and OpenCV, then overlays a summary of detected emotions onto the final output video. The processed video and an emotion frequency report are both downloadable.

🔹 Features
✅ Full Video Analysis: Detects emotions from the entire video, not frame by frame.
✅ Deep Learning Model: Uses DeepFace to analyze facial expressions.
✅ Emotion Summary Overlay: Displays detected emotions on the final video.
✅ Downloadable MP4 Video: Processed video is saved in MP4 format.
✅ Emotion Report: Generates a CSV file showing the frequency of detected emotions.

🛠 Technologies Used
Python 🐍
OpenCV 🎥 (for video processing)
DeepFace 🤖 (for facial emotion detection)
Pandas 📝 (for generating emotion reports)
FFmpeg 🎞️ (for video conversion)
📌 How It Works
Upload a video file.
Extract key frames and analyze emotions using DeepFace.
Count and summarize detected emotions.
Overlay the summary onto the entire video.
Convert the output to MP4 format.
Download the processed video and emotion report.
🚀 Installation & Usage🔧 Install Dependencies
bash
Copy
Edit
pip install opencv-python-headless deepface ffmpeg-python pandas tqdm
▶️ Run the Script
bash
Copy
Edit
python emotion_detection.py
📥 Expected Output
📹 output_emotion_detection.mp4 → Video with emotion summary overlay
📊 emotion_report.csv → Emotion frequency report
📷 Sample Emotion Report (CSV)
Emotion	Frequency
Happy	120
Sad	30
Neutral	50
📢 Future Enhancements
🚀 Support for real-time webcam analysis
🎨 Better emotion visualization on video
📊 Interactive emotion analytics dashboard

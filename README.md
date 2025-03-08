# 🎭 Emotion Detection from Video using Deep Learning 🎥  

This project analyzes the **emotions of people in a video** using **DeepFace** and **OpenCV**, then overlays a summary of detected emotions onto the final output video. The processed video and an emotion frequency report are both **downloadable**.  

---

## **🔹 Features**  
✅ **Full Video Analysis:** Detects emotions from the entire video, not frame by frame.  
✅ **Deep Learning Model:** Uses **DeepFace** to analyze facial expressions.  
✅ **Emotion Summary Overlay:** Displays detected emotions on the final video.  
✅ **Downloadable MP4 Video:** Processed video is saved in MP4 format.  
✅ **Emotion Report:** Generates a CSV file showing the frequency of detected emotions.  

---

## **🛠 Technologies Used**  
- **Python** 🐍  
- **OpenCV** 🎥 (for video processing)  
- **DeepFace** 🤖 (for facial emotion detection)  
- **Pandas** 📝 (for generating emotion reports)  
- **FFmpeg** 🎞️ (for video conversion)  

---

## **📌 How It Works**  
1️⃣ Upload a **video file**.  
2️⃣ Extract key frames and **analyze emotions** using DeepFace.  
3️⃣ Count and summarize detected emotions.  
4️⃣ Overlay the **summary onto the entire video**.  
5️⃣ Convert the output to **MP4 format**.  
6️⃣ Download the **processed video** and **emotion report**.  

---

## **🚀 Installation & Usage**  
### **🔧 Install Dependencies**  
Run the following command in your terminal or Google Colab:  
```bash
pip install opencv-python-headless deepface ffmpeg-python pandas tqdm

# 💪 Real-Time Bicep Curl Counter using Mediapipe + OpenCV

This project uses your **webcam** and **AI-powered pose detection** to count **bicep curls (dumbbell reps)** in real-time. It provides smart feedback on your form, counts your reps accurately, and gives audio alerts — just like a virtual gym trainer! 🏋️‍♀️

---

## 🧠 Features

- ✅ **Webcam-based curl detection**
- 🎯 Detects **left and right arm landmarks**
- 🧮 Calculates **elbow joint angles**
- 🎯 Measures **form accuracy**
- 🔢 Counts **only valid reps**
- 📢 Speaks **“Rep complete”** after each correct curl
- 🖥️ Displays:
  - Elbow angles
  - Rep count
  - Form score (%)
  - Curl stage (`up/down`)
  - FPS
- 💾 Saves total reps to a `pushup_count.txt` file

---

## 🛠️ Technologies Used

- [Python](https://www.python.org/)
- [Mediapipe](https://google.github.io/mediapipe/)
- [OpenCV](https://opencv.org/)
- [NumPy](https://numpy.org/)
- [pyttsx3](https://pypi.org/project/pyttsx3/) (for speech)
- [OBS Studio](https://obsproject.com/) (optional, for screen recording with webcam)

---


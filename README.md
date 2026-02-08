
🖐️ **SignTalk** is a real-time sign language translator that converts hand gestures into text and speech, bridging communication gaps between hearing and non-hearing individuals.
---
**📌 Project Overview**
The system uses a **webcam** to detect hand movements via **MediaPipe**, and a **Random Forest Classifier** model to classify gestures into English letters (A-Z). Detected letters are then combined to form full words and sentences.

**Key points:**
- Real-time hand gesture recognition.
- Visual hand landmarks drawn on screen.
- Sentence-building from consecutive letters.
- Easy editing: space, backspace, clear.
---
**✨ Features**
- 🖐️ Real-time single-hand detection.
- 🎯 Visual hand landmark points.
- ⏱️ Save letters every 5 seconds to avoid duplicates.
- 🔤 Support for all English letters A-Z.
- 📝 On-screen sentence display.
- ⌨️ Keyboard controls for space, backspace, and clearing the sentence.
---
**🛠️ Requirements**
- Python 3.8+
- Libraries:
```bash
pip install opencv-python mediapipe numpy scikit-learn

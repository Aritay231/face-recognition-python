😊 Emotion Detection from Facial Expressions
This project uses deep learning and computer vision to detect human emotions from facial expressions in real time. It combines face detection with expression classification using ONNX models and OpenCV, enabling fast and accurate emotion recognition.

**You should download <ins>emotion-ferplus-8.onnx</ins> to use this project**

🔍 Overview
- 🎥 Real-time face detection using RFB-320
- 🧠 Emotion classification with emotion-ferplus-8.onnx
- 🧪 Built with OpenCV (cv2) and Python
- 📦 Modular pipeline via expression_ssd_detect.py
- 😄 Detects emotions like happiness, sadness, anger, surprise, and more

🧠 How It Works
- Face Detection
- Uses RFB-320 SSD model to locate faces in video frames
- Efficient and lightweight for real-time performance
- Emotion Recognition
- Cropped face passed to emotion-ferplus-8.onnx model
- Outputs probability scores for 8 emotion classes
- Visualization
- Detected faces are annotated with bounding boxes and emotion labels
- Live video feed displays results in real time

  😎 Supported Emotions
- Neutral
- Happiness
- Surprise
- Sadness
- Anger
- Disgust
- Fear
- Contempt

📚 Models Used
- RFB-320: SSD-based face detector with receptive field blocks
- emotion-ferplus-8.onnx: Pretrained emotion classifier based on FER+ dataset

  ##👨‍💻 AuthorDeveloped by @Aritay231 Feel free to reach out or fork the project for your own experiments!##

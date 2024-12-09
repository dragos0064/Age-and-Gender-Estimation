# Gender and Age Classification

🎯 **Project Overview**  
The Gender and Age Classification project uses deep learning with OpenCV's DNN module to classify gender and estimate age in real-time. The system processes images, videos, or webcam streams and overlays predictions directly on the input frames.

---

✨ **Features**  
- **Real-Time Predictions**  
  - Detects gender (Male/Female) and age range (e.g., 25-32) in real-time.  
  - Works with webcam streams, image files, and video inputs.  
- **Face Detection**  
  - Utilizes OpenCV's DNN module to accurately detect faces in input frames.  
- **Hardware Acceleration**  
  - Supports both CPU and GPU inference for faster processing.  
- **Pre-Trained Models**  
  - Leverages robust Caffe models for gender and age classification.  

---

🛠️ **Requirements**  
- **Python**: 3.x  
- **OpenCV**: 4.x  
- **Pre-trained models**:  
  - `age_net.caffemodel` & `age_deploy.prototxt` for Age Classification  
  - `gender_net.caffemodel` & `gender_deploy.prototxt` for Gender Classification  
  - `opencv_face_detector_uint8.pb` & `opencv_face_detector.pbtxt` for Face Detection  

---

📦 **Installation**  

1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-repo-name>/Gender-Age-Classification.git
   cd Gender-Age-Classification

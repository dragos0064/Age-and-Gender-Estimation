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
   ```
  
2. Install dependencies:
```bash
pip install opencv-python opencv-python-headless
```


3. Download and place the required model files in the project directory.



**▶️ Usage**

To run the script:

```bash
python main.py --input <input_file>
```
Leave --input blank to use the webcam.
Use the --device flag (cpu or gpu) to specify hardware acceleration.



📊 Outputs

- **Predictions**:
  - Gender: Male/Female
  - Age: Range (e.g., 25-32)
  - Predictions are displayed directly on the image or video feed.

  
**📂 Models**

- **Age Classification**:

  - age_net.caffemodel (Pre-trained age model)
  - age_deploy.prototxt (Configuration for age model)
 

- **Gender Classification**:

  - gender_net.caffemodel (Pre-trained gender model)
  - gender_deploy.prototxt (Configuration for gender model)
  
- **Face Detection**:
  - opencv_face_detector_uint8.pb (Binary face detection model)
  - opencv_face_detector.pbtxt (Configuration file for face detection)
 
**📝 Example**

- **Using an image**:

```bash
Copy code
python main.py --input example.jpg 
```

## *🔍 License Plate Detection using YOLOv8 and OCR* 


This project aims to detect license plates from vehicle images using a YOLOv8 deep learning model and extract the text from the plates using Optical Character Recognition (OCR). It was submitted to the IEEE Info Pixel competition and secured 3rd rank 🥉.

## 📌 Project Highlights

- 🧠 YOLOv8 trained on a labeled Kaggle dataset for license plate detection

- 🔍 Detection Accuracy: 86.26%

- 🎯 Precision: 82.96%

- ✂️ Cropping detected license plates from vehicle images

- 📝 OCR to extract alphanumeric text from license plates

- 🏆 IEEE Competition: Ranked 3rd in Info Pixel

## 🚀 Tech Stack
- Tool	Purpose
- YOLOv8 (Ultralytics)	Object detection
- Python	Scripting & backend
- OpenCV	Image processing
Tesseract OCR	Text recognition
Kaggle	Dataset source
Matplotlib / Seaborn	Visualization (optional)

## 🗂️ Project Structure
- graphql


## 📦license-plate-detection
```bash
 ┣ 📁dataset/
 ┣ 📁runs/                 # YOLO training logs & weights
 ┣ 📁images/               # Sample input/output images
 ┣ 📁notebooks/            # Jupyter notebooks for experiments
 ┣ 📜best.pt               # Trained YOLOv8 model
 ┣ 📜detect.py             # Detection + OCR pipeline
 ┣ 📜train.py              # Custom training script (if any)
 ┣ 📜README.md             # Project overview
```
## 📥 Dataset
- Dataset used: Kaggle License Plate Dataset

- Contains annotated images with bounding boxes around license plates

- Format: YOLO TXT annotations

## 🧪 Results
- Metric	Value
- Accuracy	86.26%
- Precision	82.96%
- OCR Accuracy	~90% on clear plates

## ⚙️ How to Run
- Clone the repository:
```bash
git clone https://github.com/DilkhushYash/license-plate-detection.git
cd license-plate-detection

```
## Install dependencies:
```bash
pip install -r requirements.txt
```
- Download best.pt model and place it in the root directory.

## Run detection:
``` bash
python detect.py
--source path/to/image_or_video
```

## 🔍 Future Improvements
- Add real-time detection from webcam or CCTV feed

- Integrate with vehicle database for verification

- Improve OCR post-processing

- Convert into a web or mobile app

# For Flow chart:
![image](https://github.com/user-attachments/assets/5a36a591-e113-491b-9427-235b521ab250)


# OUTPUTS:

## For image:

![image](https://github.com/user-attachments/assets/b33ee74c-c527-43cf-aab8-b6bae541ad8f)
![image](https://github.com/user-attachments/assets/67badc7b-7fb5-4e59-8e8b-c50e19653793)

👨‍💻 Author
Dilkhush Yash
B.Tech CSE, 2nd Year
IEEE Info Pixel Finalist – Top 3



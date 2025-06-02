# 🚗 Automatic Number Plate Recognition (ANPR) using YOLOv8

This project implements an **Automatic Number Plate Recognition (ANPR)** system using **YOLOv8**. It detects license plates from vehicle images or video frames and provides utilities for preprocessing, visualization, and future OCR integration.

---

## 📁 Project Structure

```plaintext
automatic-number-plate-recognition-python-yolov8/
├── __pycache__/
├── models/
├── add_missing_data.py
├── main.py
├── util.py
├── visualize.py
├── yolov8n.pt
├── test.csv
├── requirements.txt
└── README.md
```

---

## 🚀 Features

- Number plate detection using YOLOv8
- Modular structure for scalability and easy integration
- Utilities to clean missing data
- Easy visualization of detection results

---

## 🛠 Installation

### 1. Clone the repository


git clone https://github.com/nitishkrtalukdar/number-plate-detection.git
cd number-plate-detection
### 2. Install dependencies
bash
Copy code
pip install -r requirements.txt
📌 Python 3.8+ is recommended.

### 3. Install YOLOv8
bash
Copy code
pip install ultralytics

## 📸 Usage
Run Detection
bash
Copy code
python main.py
Modify main.py as needed to define your input source (image, video, webcam, etc.).

### Visualize Results
bash
Copy code
python visualize.py
## 📂 Key Files Explained
File	Description
main.py	Runs the detection pipeline using YOLOv8
add_missing_data.py	Script to clean and handle missing data in datasets
util.py	Helper functions used across scripts
visualize.py	Script to display YOLOv8 predictions visually
yolov8n.pt	Pretrained YOLOv8 model weights (nano version)
test.csv	Sample data (used for testing or preprocessing logic)

## 💡 Future Improvements
✅ Integrate OCR (e.g., EasyOCR or Tesseract) to extract plate numbers

✅ Real-time detection from webcam or CCTV feeds

✅ Add Streamlit or Flask interface for web-based UI

✅ Model training on custom datasets for regional accuracy

## 📄 License
This project is provided for educational and academic purposes only.
Please use responsibly and adhere to your local laws and data privacy regulations.

## 🙌 Acknowledgments
Ultralytics YOLOv8

Python, OpenCV, and PyTorch communities

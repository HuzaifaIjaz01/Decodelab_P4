# AI Project 4 - Image Recognition using MobileNetV2

## Overview

This project demonstrates an AI-powered image recognition system using TensorFlow's pre-trained MobileNetV2 deep learning model.

The application allows users to provide an input image and predicts the top five object categories with confidence scores using transfer learning.

This project was developed as **Project 4** for the **DecodeLabs Artificial Intelligence Internship**.

---

## Features

- Load a pre-trained MobileNetV2 model
- Accept an image from the user
- Preprocess the image automatically
- Perform image classification
- Display Top-5 predictions
- Show confidence scores
- Easy to understand and beginner-friendly implementation

---

## Technologies Used

- Python 3
- TensorFlow
- NumPy
- Pillow

---

## Deep Learning Model

**MobileNetV2**

- Pre-trained on the ImageNet dataset
- Lightweight Convolutional Neural Network (CNN)
- Recognizes over 1,000 object categories

---

## Project Structure

```
AI-Project-4-Image-Recognition-MobileNetV2/
│
├── project4.py
├── requirements.txt
├── README.md
├── Project4_Report.pdf
├── sample.jpg
└── Screenshots/
    ├── output1.png
    ├── output2.png
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/AI-Project-4-Image-Recognition-MobileNetV2.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Required Libraries

```
tensorflow
numpy
pillow
```

---

## Run the Project

```bash
python project4.py
```

Enter the image path when prompted:

```
sample.jpg
```

---

## Example Output

```
Top Predictions

1. Tabby Cat ............97.83%
2. Tiger Cat............1.46%
3. Egyptian Cat.........0.41%
4. Lynx.................0.17%
5. Persian Cat..........0.08%
```

---

## Applications

- Object Recognition
- Smart Surveillance
- Medical Imaging
- Robotics
- Autonomous Vehicles
- Wildlife Monitoring
- Retail Automation

---

## Future Improvements

- Real-time webcam recognition
- Object detection using YOLO
- Custom dataset training
- Flask web application
- Streamlit deployment

---

## Author

Huzaifa Ijaz

Artificial Intelligence Intern

DecodeLabs (Batch 2026)

---

## License

This project is created for educational and internship purposes.

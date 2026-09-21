# 🔍 Forged Image Detection Using Machine Learning

A machine learning-based image forgery detection project designed to identify whether an image is **genuine or forged/manipulated**. The project uses image-processing and machine-learning techniques, including **Local Binary Pattern (LBP)** based processing and a trained model for image classification.

## 📌 Project Overview

Digital images can be easily manipulated using modern image-editing tools. Detecting forged images is therefore an important application of machine learning and image processing.

This project provides a system for analyzing images and detecting potential image forgery. It includes preprocessing, feature extraction using **Local Binary Patterns (LBP)**, model-based prediction, and testing using sample images.

## 🎯 Objectives

* Detect whether an input image is genuine or forged.
* Apply image-processing techniques for extracting useful visual information.
* Use **Local Binary Pattern (LBP)** features for image analysis.
* Use a trained machine-learning/deep-learning model for classification.
* Test the system using individual and multiple images.

## 🧠 Techniques Used

### Local Binary Pattern (LBP)

LBP is a texture-descriptor technique that represents local texture patterns in an image. It can help identify differences in texture and pixel-level characteristics that may be useful for forgery detection.

### Machine Learning Model

The project includes a trained model and corresponding model weights:

* `model.json` — model architecture
* `model_weights.h5` — trained model weights

These files are used by the application for making predictions on input images.

## ⚙️ Project Workflow

```text
Input Image
     ↓
Image Preprocessing
     ↓
LBP Feature Extraction
     ↓
Trained Model
     ↓
Image Classification
     ↓
Forgery Detection Result
```

## 📂 Project Structure

```text
Forged-Image-Detection/
│
├── data/
│   └── Dataset / project data
│
├── LBP/
│   └── LBP-related files
│
├── testimages/
│   └── Images used for testing
│
├── FakeImage Detect.py
├── LBP.py
├── list.py
├── me.py
├── multiple.py
├── test.py
│
├── model.json
├── model_weights.h5
│
├── run.bat
├── test.jpg
└── test1.jpg
```

## 🛠️ Technologies Used

* **Python**
* **Machine Learning**
* **Image Processing**
* **Local Binary Pattern (LBP)**
* **Trained Neural Network Model**
* **H5 Model Weights**
* **JSON Model Architecture**

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/sanjana-silveru/Forged-Image-Detection.git
```

### 2. Open the project folder

```bash
cd Forged-Image-Detection
```

### 3. Install the required Python libraries

Install the dependencies required by the Python files. For example:

```bash
pip install numpy opencv-python tensorflow scikit-image
```

> **Note:** The exact dependencies may vary depending on the Python environment and the libraries imported by the project files.

### 4. Run the application

The project includes:

```text
run.bat
```

You can also execute the relevant Python script directly:

```bash
python "FakeImage Detect.py"
```

## 🧪 Testing

The repository includes sample test images and testing scripts.

Examples:

* `test.jpg`
* `test1.jpg`
* `testimages/`
* `test.py`
* `multiple.py`

These can be used to test the image-forgery detection workflow.

## 📊 Model Files

The trained model is represented by:

| File               | Purpose                          |
| ------------------ | -------------------------------- |
| `model.json`       | Stores the model architecture    |
| `model_weights.h5` | Stores the trained model weights |

The model files allow the trained model to be loaded without retraining it from scratch.

## 🚀 Key Features

* 🔍 Image forgery detection
* 🖼️ Image preprocessing and analysis
* 📊 LBP-based feature extraction
* 🤖 Trained ML/deep-learning model
* 🧪 Single-image testing
* 🖼️ Multiple-image testing
* 💻 Windows batch execution support

## 🎓 Project Type

**Mini Project — Machine Learning / Image Processing**

## 👩‍💻 Author

**Sanjana Silveru**

GitHub:
https://github.com/sanjana-silveru



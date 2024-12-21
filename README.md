# EmoVision-FaceEmotion
Emphasizing facial emotion detection using a neural network

This repository contains a project that uses a Convolutional Neural Network (CNN) to classify facial moods from images. The model is designed to handle limited datasets by leveraging data augmentation techniques. Learning curves and evaluation metrics are used to assess the model's predictability.

# Features
- Facial Mood Classification: Predict moods from face images.
- Data Augmentation: Handles limited dataset sizes by artificially expanding the training set.
- Model Evaluation: Includes learning curves and performance metrics for evaluation.
# Dataset
The dataset used for this project is available here. Note that the dataset is not included in this repository. Please download it directly from the provided link.

# Requirements
Install the necessary dependencies using:

```bash
pip install -r requirements.txt
```
# Dependencies
- TensorFlow
- NumPy
- OpenCV
- Matplotlib

# Usage
1. Clone the repository:
```bash
git clone https://github.com/yourusername/facial-mood-recognition.git
```
2. Navigate to the project directory:
```bash
cd facial-mood-recognition
```
3. Run the Jupyter notebook:
```bash
jupyter notebook jupyter.ipynb
```

# File Overview
jupyter.ipynb: Contains the code for training and evaluating the CNN model.
README.md: Documentation about the project.
requirements.txt: Lists all the Python dependencies.
# Results
The model achieves good predictive performance, as evidenced by its learning curves and evaluation metrics.
<img src="https://raw.githubusercontent.com/AISoltani/EmoVision-FaceEmotion/refs/heads/main/face.png" alt="Face Emotion Recognition" width="600"/>


Acknowledgements
The dataset is sourced from [Spencer Yee's CS229 repository](https://github.com/spenceryee/CS229/tree/master).

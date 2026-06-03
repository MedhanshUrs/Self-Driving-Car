# Self-Driving Car using Deep Learning

This project implements a deep learning–based self-driving car system capable of predicting steering angles from front-facing road images. The model uses a Convolutional Neural Network (CNN) inspired by NVIDIA’s end-to-end autonomous driving architecture.

The system processes dashboard camera images and predicts steering wheel angles in real time to simulate autonomous driving behavior.

## Features

* End-to-end steering angle prediction
* CNN-based autonomous driving model
* Real-time steering simulation
* Image preprocessing and normalization
* TensorBoard loss visualization
* Steering wheel animation output

## Dataset

The project uses Sully Chen’s Self-Driving Car Dataset containing:

* Dashboard camera images
* Corresponding steering wheel angles

Dataset Link:
https://github.com/SullyChen/driving-datasets

## Model Architecture

The CNN architecture consists of:

* 5 Convolutional Layers
* Fully Connected Layers
* ReLU Activation
* Dropout Regularization

The model predicts steering angles directly from input road images.

## Technologies Used

* Python
* TensorFlow
* OpenCV
* NumPy

## Project Files

```text id="sd1"
model.py           # CNN architecture
driving_data.py    # Data loading and preprocessing
train.py           # Model training
run_dataset.py     # Real-time prediction and simulation
```

## Run the Project

### Install Dependencies

```bash id="sd2"
pip install tensorflow opencv-python numpy scipy
```

### Train the Model

```bash id="sd3"
python train.py
```

### Run Real-Time Simulation

```bash id="sd4"
python run_dataset.py
```

## Results

* The model successfully predicts steering angles from road images.
* Real-time simulations demonstrate smooth steering behavior.
* Training loss decreases consistently across epochs.

## Future Improvements

* Real-world testing
* Better dataset balancing
* Lane detection integration
* Object detection and obstacle avoidance
* Migration to TensorFlow 2.x / PyTorch

## Report

The detailed project report is included in this repository.

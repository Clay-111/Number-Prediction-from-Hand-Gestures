# Number Prediction from Hand Gestures

- This project is a hand gesture recognition system using Convolutional Neural Networks (CNN) with Keras and OpenCV. 
- The system can recognize six different numbers from hand gestures: ZERO, ONE, TWO, THREE, FOUR, and FIVE.

## Project Structure

- `collect-data.py`: Script to collect training and testing data using a webcam.
- `train.py`: Script to train the CNN model.
- `predict.py`: Script to predict hand gestures using the trained model.
- `model-bw.h5` and `model-bw.json`: Trained model and its architecture for grayscale images.
- `model.h5` and `model.json`: Trained model and its architecture for color images.
- `dataset.rar`: Compressed dataset of hand gesture images.

## Requirements

- Python
- OpenCV
- Keras
- TensorFlow
- NumPy

# Hardware-Acceleration-and-Optimization-for-Machine-Learning
# Audio Classification Model: Bird and animal call detection

This repository contains an audio classification model that distinguishes between bird, cat, and dog sounds. It includes model files in various formats, as well as a Jupyter Notebook used to build, train, and convert the model.

## Files

- **Bird_Cat_dog_audio_classification.ipynb**: Jupyter Notebook containing code for data preprocessing, model training, and evaluation.
- **audio_classification_model.h5**: The trained Keras model saved in HDF5 format.
- **audio_classification_model.tflite**: A TensorFlow Lite version of the model for deployment on mobile and edge devices.
- **audio_classification_model_quant.tflite**: A quantized TensorFlow Lite model, optimized for low-resource environments.

## Requirements

To run the Jupyter Notebook and reproduce the model, you'll need the following libraries:

- TensorFlow
- Keras
- Numpy
- Librosa (for audio processing)

You can install the dependencies by running:

```bash
pip install tensorflow numpy librosa

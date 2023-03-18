# Design of AI model for the automatic identification of defective products using deep learning
## Návrh AI modelu pro automatickou detekci vadných výrobků pomocí metod hlubokého učení
## This software has the following technical parameters:

- Input image size: 1024x1024 pixels in RGB format, but it can also work with smaller images.
- Minimum number of images required for training: 200.
- Programming language: Python, used to develop the application.
- Machine learning library: Tensorflow, used for building and training the autoencoder model.
- Anomaly detection techniques: This software uses the kernel density estimation (KDE) and reconstruction loss techniques available in the scikit-learn library (sklearn) to define the threshold for detecting anomalous objects in the images.
- The software uses convolutional neural networks (CNNs) as the underlying architecture for the autoencoder. The model is trained using a dataset of images, and then it can be used to detect anomalies in new images.
- The software‘s performance can be further optimized by adjusting parameters such as the number of hidden layers, the learning rate, and the activation functions used in the model.
- The output of the software is a binary classification of the input images into normal or anomalous.
- The software can be deployed on a variety of platforms and operating systems, and can be integrated into existing workflows and systems for quality control in manufacturing.

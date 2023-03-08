# Detection of COVID-19 from chest X-Ray images

Highlights
Built a binary classification model using chest X-Ray images and VGG-16 convolutional neural network architecture pre-trained on ImageNet.
New fully-connected layer was added to the pre-trained network to classify images as either normal or COVID-affected.
Model was trained and achieved an accuracy of 93%.
Tags: Python, Computer Vision, TensorFlow, Deep Learning, Convolutional Neural Networks

Summary
In recent years, deep learning has shown promising results in medical image analysis, including detecting COVID-19 from chest X-rays. One popular approach is to use pre-trained convolutional neural network (CNN) models, such as VGG-16, ResNet, or DenseNet, and fine-tune them on COVID-19 chest X-ray datasets. The fine-tuning process involves removing the original classification layer and adding a new one to adapt the model to the specific COVID-19 detection task.

Besides using pre-trained models, researchers have also developed specialized architectures for COVID-19 detection. For example, COVID-Net is a CNN model specifically designed for COVID-19 detection from chest X-rays. COVID-Net uses a series of convolutional and pooling layers followed by several fully-connected layers to classify chest X-rays as normal, pneumonia, or COVID-19.

The goal of the project is to develop a machine learning model that can accurately and quickly detect COVID-19 infection from chest X-ray images. By achieving an accuracy of 93%, the model shows promise as a potential tool for COVID-19 screening and diagnosis.

# Image-Captioning using TensorFlow and Keras
This repository provides an implementation of image captioning using TensorFlow and Keras, with the InceptionResNetV2 model as the encoder and a GRU model with attention as the decoder. The model is trained on the COCO Captions dataset.

# Overview
Image captioning is the task of generating a textual description that accurately captures the content of an image. This project implements an image captioning model using a deep learning architecture. The model consists of two main components: an encoder and a decoder.

The encoder utilizes the pre-trained InceptionResNetV2 model, which extracts meaningful features from the input image. These features are then used as the initial hidden state of the decoder.

The decoder is a GRU (Gated Recurrent Unit) model with attention. It takes the features from the encoder as input and generates a caption word by word. Attention mechanisms help the model focus on different parts of the image while generating each word.

The model is trained on the COCO Captions dataset, which contains over 120,000 images with five captions per image. The dataset is widely used for image captioning tasks and provides a diverse range of images with corresponding captions.

# Results
The model is trained on the COCO Captions dataset for only 2 epochs. After training, the model is used to generate captions for new images.

![Screenshot 2023-06-26 at 4 11 26 pm](https://github.com/erictom97/Image-Captioning/assets/40288848/cb56821a-1320-4310-8eab-6acf6c903fe4)

# Acknowledgements
This project is based on the TensorFlow tutorial on Image Captioning provided by Google. I would like to express my gratitude to the TensorFlow team at Google for their excellent work in creating and sharing this tutorial.
The notebook referred: https://github.com/GoogleCloudPlatform/asl-ml-immersion/blob/master/notebooks/multi_modal/solutions/image_captioning.ipynb

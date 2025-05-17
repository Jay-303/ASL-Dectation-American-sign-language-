# ASL-Dectation-American-sign-language-
This project focuses on recognizing American Sign Language (ASL) hand gestures using deep learning. The model is capable of classifying static ASL alphabet signs (A–Z) from images. It's built using ResNet50V2 and deployed with Gradio for easy real-time interaction.
 Objective

To build an image classification model that can detect and classify ASL alphabets from hand gesture images. This helps bridge communication gaps for people with hearing or speech impairments.

 Model Highlights

* **Architecture**: ResNet50V2 (Pre-trained on ImageNet)
* **Frameworks**: TensorFlow / Keras, PyTorch (used in experimentation)
* **Dataset**: ASL Alphabet Dataset (image dataset with A–Z signs)
* **Preprocessing**: Resizing, normalization, augmentation
* **Interface**: Gradio-based web UI for uploading an image and getting predictions
Features

* Detects 26 ASL signs (A–Z) from images
* Real-time image input via upload or camera (in extended version)
* High accuracy on test data after transfer learning
* Lightweight UI for demonstration

Future Scope

* Real-time **video stream detection**
* Predict full **ASL words or phrases**
* Integrate with webcam for **live translation**
* Build mobile app or browser extension

Tech Stack

* Python, Keras, TensorFlow, PyTorch
* OpenCV (for preprocessing)
* Gradio (for UI)
* Docker (for containerization)

JAY KUNJIR
MSc Statistics | Deep Learning Practitioner


## Abstract:

The objective of this project is to develop a system that can accurately detect and recognize hand signs and gestures used in American Sign Language (ASL). This will be accomplished using computer vision and deep learning techniques, specifically convolutional neural networks (CNNs) and transformers. 

ASL is a complex and expressive language that is used by deaf and hard-of-hearing individuals to communicate.  It consists of a unique set of hand signs, facial expressions, and body language.

Unfortunately, many people who are not deaf or hard-of-hearing may not be familiar with ASL or may have difficulty understanding and recognizing the hand signs. Once the model has been trained, it will be able to accurately recognize ASL signs in real-time providing instant or live translations, making it a useful tool for those using it to engage in learning the language and further improving communication between the deaf and hearing communities.

Overall, the goal of this project is to create a powerful and accurate ASL interpreter system that can help bridge the communication gap between the deaf and hearing communities. 


## Files:

### Input-->
data.zip - Dataset containing 400 images for 25 classes (A-Z excluding J and Z, including Blank Space)

### Models-->
CNN.ipynb - Implementation of CNN model

FCN.ipynb - Implementation of Fully Connected model (ANN)

VGG16.ipynb - Implementation of VGG16 model (Variation of CNN architecture)

### Live Test-->
Recognize-Predict.ipynb - Used to predict Sign Language on live video feed


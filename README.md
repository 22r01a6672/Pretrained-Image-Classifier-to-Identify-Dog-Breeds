# Pre-trained Image Classifier for Dog Breed Identification
<br>This repository contains a pre-trained image classifier developed using Python to identify dog breeds. The classifier utilizes three well-known Convolutional Neural Network (CNN) architectures: AlexNet, VGG, and ResNet. Each of these architectures is leveraged to classify images into different dog breeds, as well as determine whether an image contains a dog.<br><br>

## Overview
This project is designed to identify different dog breeds from images and check if an image contains a dog. It includes the following features:

-***Dog Breed Classifier:*** The main part of the project, using pre-trained neural networks to recognize different dog breeds in images.
- **Dog Detector:** Checks whether an image contains a dog or not.
- **Image Preprocessing:** Prepares the images by resizing, normalizing, and transforming them so they work well with the CNN models.
- **Results Analysis:** Measures the performance of the classifier, calculating key metrics such as accuracy, correct matches, and misclassifications.

1. Clone the repository to your local machine:
`git clone https://github.com/22r01a6672/Pretrained-Image-Classifier-to-Identify-Dog-Breeds.git`
2. Navigate to the project directory:
`cd Pretrained-Image-Classifier-to-Identify-Dog-Breeds`
3. Install the required packages:
`pip install -r requirements.txt`
<br><br>

### Instructions
1. Testing the Classifier:
- To test the classifier's performance on a set of images, run the following command:
  `python test_classifier.py`
- The results will display the accuracy, correct matches, and misclassifications.
2. Using the Classifier:
- Save your dog images in the `uploaded_images` folder of the repository. Then, use the provided functions to classify dog breeds in your own Python applications.
- To process the images, run the following command in your terminal:
`
sh run_models_batch_uploaded.sh
` 
-Once the script runs, you can view the results in the following text files  "resnet_uploaded-images.txt", "alexnet_uploaded-images.txt", and "vgg_uploaded-images.txt", in the main repository:
  - **resnet_uploaded-images.txt** - contains the results using ResNet CNN model.
  - **alexnet_uploaded-images.txt** - contains the results using AlexNet CNN model.
  - **vgg_uploaded-images.txt** - contains the results using VGG CNN model.
-Run the main class file, `check_images.py`, with the following command:
`
python check_images.py
`
-Then, compare the results to those produced by your program when you ran run_models_batch.sh
## CNN Architectures
### AlexNet
AlexNet is a deep CNN architecture designed for image recognition tasks. It consists of five convolutional layers followed by three fully connected layers. To use AlexNet with the classifier, use the command `--arch alexnet`.

### VGG
VGG (Visual Geometry Group) is a CNN architecture known for its simplicity and depth, uses 3x3 convolutional layers throughout the architecture. To use VGG with the classifier, use the command `--arch vgg`.

### ResNet
ResNet (Residual Neural Network) is a CNN architecture designed to solve the vanishing gradient problem in deep networks. It uses residual connections to allow smoother gradient flow during training. To use ResNet with the classifier, use the command `--arch resnet`.
ResNet (Residual Neural Network) is a CNN architecture designed to solve the vanishing gradient problem in deep networks. 
<br><br>

## Contributions Welcome
Feel free to contribute to this project: 
-If you find a bug or have a suggestion, Open an issue to let me know.
-Want to improve the project? Submit a pull request with a clear explanation of your changes.
<br/><br/>

![Dog Image](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRxTxyeu1HFzHNCgHJzgN_lJQ1bpIuzSGA3iQ&s)

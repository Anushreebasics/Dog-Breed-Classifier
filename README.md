# Dog-Breed-Classifier

# City Dog Show Image Classification Project

## Project Description

This project aims to classify images of dogs submitted for a citywide dog show. Using a pre-trained convolutional neural network (CNN) model, we will determine whether the submitted images are of dogs and, if so, classify their breeds. The project focuses on utilizing Python to implement and evaluate different CNN architectures: AlexNet, VGG, and ResNet.

## Project Goals

1. **Identify Dog Images**: Correctly identify which pet images are of dogs (even if the breed is misclassified) and which images aren't of dogs.
2. **Classify Dog Breeds**: Correctly classify the breed of dog for images that are identified as dogs.
3. **Evaluate CNN Architectures**: Determine which CNN model architecture (ResNet, AlexNet, or VGG) best achieves objectives 1 and 2.
4. **Analyze Performance**: Consider the time resources required to best achieve objectives 1 and 2, and determine if an alternative solution would have given a "good enough" result given the amount of time each of the algorithms takes to run.

## Results

The results for each architecture will be saved in separate files in the following files:
- `resnet_pet-images.txt`
- `alexnet_pet-images.txt`
- `vgg_pet-images.txt`

Each file will contain the classification results, including the number of images, number of dog images, number of not-dog images, percentage of correct dog classifications, percentage of correct breed classifications, and percentage of correct not-dog classifications, as well as the total elapsed runtime of the script.
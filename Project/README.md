## Tiny ImageNet Classification

### Overview

This project explores various convolutional neural network (CNN) architectures for image classification tasks using the Tiny ImageNet dataset. We start with basic CNNs and progress to more complex models, evaluating their performance and scalability in handling 200 classes of 64x64 pixel images.

### Goals
1. Evaluate the efficacy of CNN architectures for image classification on a reduced-size dataset.
2. Assess the impact of increasing network depth and incorporating dropout for regularization.
3. Utilize transfer learning techniques with pre-trained models like ResNet-50 to boost classification accuracy.
4. Compare and analyze the results to highlight the benefits of deeper networks and transfer learning strategies.
   
### Dataset
Tiny ImageNet consists of 100,000 images categorized into 200 classes, each resized to 64x64 pixels. This dataset provides a challenging yet manageable platform for testing deep learning models due to its reduced size and diverse class distribution.

### Approach
# Baseline CNN Models: 
Starting with a simple three-layer CNN and incrementally adding layers to explore depth's influence on model performance.
# Advanced Techniques: 
Implementing dropout to enhance model generalization and mitigate overfitting.
# Transfer Learning: 
Leveraging pre-trained models trained on full ImageNet weights to transfer learned features and improve classification accuracy.

### Results
The project culminates in a comparative analysis demonstrating the superior performance of deeper networks with dropout and transfer learning strategies. These findings contribute to optimizing CNN architectures for enhanced image classification accuracy on challenging datasets like Tiny ImageNet.

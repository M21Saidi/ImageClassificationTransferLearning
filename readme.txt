# Transfer Learning in Image Classification

This repository houses a project focused on using neural networks for image classification. The primary dataset consists of images of horses and humans.


## Overview

We begin with a straightforward CNN model to set our baseline. To enhance our model's performance, we delve into transfer learning, leveraging the EfficientNet_B0 architecture. By doing so, we aim to benefit from the features already learned by this model on vast datasets and adapt them to our specific task.

## ## Dataset Description

The dataset used in this project is organized into specific folders:

- **Image_classification_data**: The primary dataset is separated into 'train' and 'test' folders. Within each, there are further sub-folders dedicated to 'humans' and 'horses', ensuring a clear distinction between the two classes.
  
- **Test_Real_Images_Human_Horsesr**: Apart from the standard training and testing sets, there's an additional folder containing real-world images. These images serve as a practical testbed, allowing us to evaluate our model's performance in real-life scenarios.

Using this structured dataset ensures that our models can be trained, validated, and tested effectively.

## Key Features

- **Data Loading and Preprocessing**: Properly structured and preprocessed data ensures that our neural network can be trained effectively.
- **Base Model Training**: Using a simple CNN to understand the foundational performance.
- **Transfer Learning**: Implementing the EfficientNet_B0 model to harness the power of pre-trained networks.

## Results

Our exploration provides valuable insights into the performance gains possible using transfer learning. 

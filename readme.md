# Transfer Learning in Image Classification

This repository houses a project focused on using neural networks for image classification. The primary dataset consists of images of horses and humans.


## Overview

We begin with a straightforward CNN model to set our baseline. To enhance our model's performance, we delve into transfer learning, leveraging the EfficientNet_B0 architecture. By doing so, we aim to benefit from the features already learned by this model on vast datasets and adapt them to our specific task.

## Dataset Description

The project relies on a dataset comprising two distinct subsets: 'humans' and 'horses'. These subsets are not based on real-world images but rather examples where the primary object in the image is distinctly either a horse or a human. Each subset is neatly organized into its dedicated folder, ensuring that the images are effectively labeled.

Furthermore, to gauge our model's performance in real-life situations, we use a set of actual real-world images. This practical testbed challenges the model outside of the controlled dataset environment, offering insights into its real-world applicability.

## Key Features

- **Data Loading and Preprocessing**: Properly structured and preprocessed data ensures that our neural network can be trained effectively.
- **Base Model Training**: Using a simple CNN to understand the foundational performance.
- **Transfer Learning**: Implementing the EfficientNet_B0 model to harness the power of pre-trained networks.

## Results

Our exploration provides valuable insights into the performance gains possible using transfer learning. 

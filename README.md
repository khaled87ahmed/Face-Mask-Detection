# Face Mask Detection

## Dataset
- The dataset used for this project is the [Face Mask 12k Images Dataset](https://www.kaggle.com/datasets/ashishjangra27/face-mask-12k-images-dataset) from Kaggle.
- This dataset consists of images categorized into 'WithMask' and 'WithoutMask' classes, essential for training a face mask detection model.

## Problem Statement
- Detection of individuals wearing face masks is crucial for public health and safety.
- Automated face mask detection using deep learning can aid in enforcing mask-wearing protocols.

## Objectives
1. **Data Preparation:**
   - Import essential libraries.
   - Load the Face Mask 12k Images Dataset.

2. **Data Exploration:**
   - Examine image shapes and visualize random samples to understand data distribution.

3. **Data Preprocessing:**
   - Normalize pixel values for uniformity and better model performance.
   - Prepare dataset for training, validation, and testing.

4. **Model Building:**
   - Define a CNN architecture tailored for face mask detection.
   - Construct model using convolutional, max-pooling, and dropout layers.

5. **Model Training and Evaluation:**
   - Compile model with appropriate settings.
   - Train on training dataset and evaluate on test dataset.
   - Monitor learning progress and performance using visualization techniques.

6. **Model Deployment:**
   - Deploy trained model for real-time face mask detection.
   - Integrate model into applications for enforcing mask-wearing guidelines.

## Installation
- Clone this repository:
  ```bash
  git clone https://github.com/your_username/face-mask-detection.git

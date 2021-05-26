# Dogs-vs-Cats-Image-Classification
I used a convolutional network to classify images of dogs and cats

## Dataset
The dataset used in this project is the training dataset from the "Dogs vs. Cats" Kaggle competition: https://www.kaggle.com/c/dogs-vs-cats

## Implementation
The training dataset from Kaggle contains 25,000 images of dogs and cats. This was randomly split into training and validation datasets which contain 20,000 and 5,000 images respectively. The convolutional neural network was trained using the 20,000 images in the training dataset. In each epoch, the model was validated using the 5,000 images to ensure that the model performs well on data it has never been trained on.

## Results
Training accuracy: 90.20%

Validation accuracy: 79.98%

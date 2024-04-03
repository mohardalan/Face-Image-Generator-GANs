# GANs for Generating Human Faces
This project aims to create two distinct Generative Adversarial Network (GAN) models for generating human faces. The first model employs Fully Connected (FC) layers, while the second model leverages Convolutional Neural Network (CNN) layers, incorporating VGG16 as a pre-trained model to enhance the generator module. The dataset comprises 10,000 high-quality face images of various races, resized to 256 pixels. However, due to resource constraints, only 5,000 images were used for training.

## Model Overview
### FC Layers Model
**Architecture**: Fully Connected layers

**Results**: Demonstrated high image quality, albeit with limitations on input image size and epochs, potentially indicating overfitting to a single image.


### CNN Layers Model with VGG16
**Architecture**: CNN layers with VGG16 pre-trained model

**Enhancements**: Implemented Data Augmentation, Regularization methods, Label Smoothing, and a learning rate scheduler

**Results**: Showed a need for more data and epochs to further improve the quality of the generated images


## Dataset
Link to Input Database:

https://www.kaggle.com/code/theblackmamba31/generating-fake-faces-using-gan/input

## Conclusion
While the FC layers model demonstrated high image quality, the CNN layers model with VGG16 showed potential for further improvement with additional data and training epochs.

Feel free to explore the code and experiment with different architectures and hyperparameters to enhance the generated image quality.

# Dog Breed Classifier


### Overview
This is the last project of Udacity Machine Learning Engineer Nanodegree. In this project, A dog app is developed to classify the input image, if containing a dog into its true breed. As a proof of concept, I built a CNN from scratch and obtained a 13% accuracy. Moreover, I used Transfer learning to transfer the knowledge obtained by ResNet50 to utilise in my problem domain.

### Purpose and Results
This Project had multiple steps. 
1. Using Haar Cacasdes, I defined a function that detect humans in an image.

2. Using VGG16, I defined a dunction that detect dogs in an input images.

3. Training a CNN from scratch for 25 epochs
```
Test Loss: 3.74
Test Accuracy: 13% (114/836)
```

4. Using Transfer Learning and ResNet50
```
Test Loss: 0.768759
Test Accuracy: 80% (675/836)
```

# Requirements

Download and Unzip [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).

Download and Unzip [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).


Jupyter notebook must be installed.
Python must be installed. The following python modules must be installed.
```
jupyter
numpy
glob
opencv-python
matplotlib
tqdm
pytorch
PIL
```

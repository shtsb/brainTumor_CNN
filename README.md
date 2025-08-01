# Brain Tumor Classification Using CNN on MRI images
This project uses CNN to analyse brain MRI images and determine whether a tumor is present or not.

# Dataset
The dataset consists of 253 MRI images divided into:
- Tumor : 155 images
- No Tumor : 98 images
  All images are resized to 128*128 pixels and normalized between 0 and 1.
- **Source** : https://github.com/zione-kushwaha/Brain-Tumor-detection-MRI-/tree/main/data
- **Target** : classify brain MRI images based on the presence or absence of a tumor.

# Method 
- **Language** : python
- **Libraries** : os, sklearn, tensorflow, keras, numpy, matplotlib
- The CNN model consists of:
  - 2 Convolutional layers with Relu activation
  - MaxPooling after each convolution layer
  - A Dense layer with Dropout
  - Final Dense layer with softmax activation
    
- Loss : categorical_crossentropy
- Optimizer : adam
      

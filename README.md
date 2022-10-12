# Realtime Gender Recognition from Face

The keras model is created by training from scratch on around 2200 face images (~1100 for each class). Face region is cropped by applying `face detection` using `cvlib` on the images gathered from Kaggle. It acheived around 96% training accuracy and ~90% validation accuracy. (20% of the dataset is used for validation)

## Python packages
* numpy
* opencv-python
* tensorflow
* keras
* requests
* progressbar
* cvlib

We would first need to generate model by executing the `train_model.ipynb` file. Once the model is generated successfully,it is saved and then we can use `detect_gender.ipynb` to get realtime gender classification.

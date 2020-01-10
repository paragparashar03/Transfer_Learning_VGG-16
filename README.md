# Transfer_Learning_VGG-16

Transfer learning refers to the technique of using knowledge of one domain to another domain .i.e. a NN model trained on one dataset can be used for other dataset by fine-tuning the former network.

#Here, we have used VGG-16 model and used our own data set. There are two cases:

#1. Train as a classifier:

I have changed the last layer of VGG model as we have only 4 categories as compared to ImageNet that has 1000 categories.

#2. Fine tune the Model
In this case, I have removed last 3 layers from the  VGG model and added 7 layers ( 4 dense and 3 dropout layers)

# Both ipynb files have been uploaded.

#Deep learning models-Keras link:
https://github.com/fchollet/deep-learning-models 
clone the repository

#Dataset:
Data file is provided as zip file along with ipynb file

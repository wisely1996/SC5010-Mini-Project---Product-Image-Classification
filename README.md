# SC5010-Mini-Project-Product-Image-Classification
# About
A mini project for our course SC5010 - Introduction to Data Analysis, we obtained our dataset from Kaggle and used Tensorflow to form a CNN in order to create an Image Classification model to classify product images from [Shopee](https://www.kaggle.com/c/shopee-product-detection-open/overview), resized and reuploaded by a [kaggle user](https://www.kaggle.com/datasets/tanyongkeong/shopee-code-league-2020-product-detection?select=train.csv).

# Contributors
* @
* @wisely1996

# Problem Definition
* Given images of topwear and bottomwear, able to classify them correctly
* 

# Model Layers
1. 4 CNN Layers, with ReLu as activation in each layer
  -   
2. 3 Dense Layers, with ReLU as activation
3. Optimized with Adaptive Moment Estimation (Adam) 

# Outcome of Project
* Classification Accuracy of 93.57%

# Conclusion
* Model may be underperfoming considering the potential of how powerful CNNs are
* Test out with more hyperparameters to improve model
* Including a neutral class (neither top nor bottom)

# Learning Points
* Exploring high-level operation 'shutil'
* Building a Convolution Neural Network Layer from scratch
* Gradient Descent vs Adam Optimizers
* Ensemble CNN
* K-fold Cross Validation on top of CNN


# References
https://www.analyticsvidhya.com/blog/2019/10/building-image-classification-models-cnn-pytorch/

https://www.youtube.com/watch?v=zfiSAzpy9NM&list=PLeo1K3hjS3uu7CxAacxVndI4bE_o3BDtO&index=24

https://www.youtube.com/watch?v=7HPwo4wnJeA&list=PLeo1K3hjS3uu7CxAacxVndI4bE_o3BDtO&index=24

https://www.kaggle.com/c/shopee-product-detection-open/overview

https://www.kaggle.com/datasets/tanyongkeong/shopee-code-league-2020-product-detection?select=train.csv

# Image similariy using autoencoders


**Goal** of this project is to find similar images given a collection of images

* **Input**: image_id
* **Output**: Images similar to the given input image_id

### Dataset

* The dataset consist of roughly 5000 images of wild animals
* unlabeled -> unsupervised learning

### Aproach

* used ImageDataGenerator to generate data with a target size of 128x128
* Used VGG16 and Auto-Encoders for feature extraction (Refer only the auto encoder part, which gives good results, the VGG16 does not produce good results)
* Tried visualising the extracted feature using PCA and t-SNE
* Used K-means algorithm to cluster the features into groups.
* Used Euclidean distance to find similar images to the given input image.


This project was done for educational purpose, any comments positive/negative related to this work is welcome

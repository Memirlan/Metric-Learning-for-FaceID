# In progress...
![](https://github.com/Memirlan/Metric-Learning-for-FaceID/blob/main/metric%20cats.png)

### Cleaned the LFW (Labelled Faces in the Wild) dataset: [Kaggle Link](https://www.kaggle.com/datasets/jessicali9530/lfw-dataset) 
- removed folders with <4 images
- removed photos with != 1 number of faces
- cropped faces from the photos
- implemented triplets (anchor, positive, and negative samples) and the triplet loss
- trained a ResNet without a head to extract features and compare images by compute distances between their vector representations

### Soon: thresholding on a test set and making a verificator using a threshold; checking transformer models for feature extraction. I will also try to deploy it for demo

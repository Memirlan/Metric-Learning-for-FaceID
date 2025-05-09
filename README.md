# In progress...

### Cleaned the LFW (Labelled Faces in the Wild) dataset: https://www.kaggle.com/datasets/jessicali9530/lfw-dataset 
- removed folders with <4 images
- removed photos with != 1 number of faces
- cropped faces from the photos
- implemented triplets (anchor, positive, and negative samples) and the triplet loss
- trained a ResNet without a head to extract features and compare images by compute distances between their vector representations

# Soon: thresholding on a test set and making a verificator using a threshold. I will try to deploy it for demo

# In progress...
## Many parts of the code were shared by Kolesnikov Dmitriy on YT: [Video Link](https://www.youtube.com/watch?v=bvorduzJ9E0&ab_channel=%D0%94%D0%BC%D0%B8%D1%82%D1%80%D0%B8%D0%B9%D0%9A%D0%BE%D0%BB%D0%B5%D1%81%D0%BD%D0%B8%D0%BA%D0%BE%D0%B2)

### Cleaned the LFW (Labelled Faces in the Wild) dataset: [Kaggle Link](https://www.kaggle.com/datasets/jessicali9530/lfw-dataset) 
- removed folders with <4 images
- removed photos with != 1 number of faces
- cropped faces from the photos
- implemented triplets (anchor, positive, and negative samples) and the triplet loss
- trained a ResNet without a head to extract features and compare images by compute distances between their vector representations

### Soon: thresholding on a test set and making a verificator using a threshold; checking transformer models for feature extraction. I will also try to deploy it for demo

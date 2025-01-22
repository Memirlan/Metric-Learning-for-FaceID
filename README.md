### Cleaned the LFW (Labelled Faces in the Wild) dataset: https://www.kaggle.com/datasets/jessicali9530/lfw-dataset 
- removing folders with <4 images
- removing photos with != 1 number of faces
- cropped faces from the photos

### Implemented triplets (anchor, positive, and negative samples) and the triplet loss

### Trained the ResNet by removing the last layer to get vector representations of images for training via Metric Learning
- trained Resnet-18 for 10 epochs only (to be improved)

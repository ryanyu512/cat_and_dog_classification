# cat_and_dog_classification

For object detection, it combines classification and localization. This project aims to complete the classification. Then, the next project would use this classification model as the backbone of detection model.

1. The data for training and validation is extracted from https://www.kaggle.com/c/dogs-vs-cats. It contains 12500 cat and 12500 dog images. Training/validation ratio is set as 0.8/0.2. 
2. explore_cls_data.ipynb: This notebook aims at exploring the bad images in the dataset
3. cls_network_explore.ipynb: This notebook aims at exploring the network achitechure
4. prepare_cls_data.ipynb: This notebook aims at preparing cat and dog data for training and validation
5. network.py: Aims at defining the architechure of classification model
6. train_cls_model.py: Aims at provide custom library for training the classification model
7. train_cls_network.py: Aims at training the classification model
8. best_mode: the folder that stores the best model and related training and validation result

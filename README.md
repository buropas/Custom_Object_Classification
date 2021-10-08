# Transfer Learning for Custom Object Classification (VGG16)

We can think of TRANSFER LEARNING as utilizing the feature learning layers of a pre-trained CNN to classify a different problem than the one it was created for, without retraining the Convolutional Blocks of the network but simply adding a Custom Classification Head (one or more Fully Connected Layers) on top of Convolutional part.  Then, only Fully Connected Layers are trained on our own custom dataset in order to solve our specific classification task.

For istance, let's assume we want to classify Sunflowers in images.    
We can take advantage of a Neural Network, called VGG16, that was trained on the ImageNet dataset, containing more than 14 million high-resolution images belonging to 1000 different labels.  This Network was not trained to classify specific kind of flowers. But we can take advantage of the Feature Learning part of the network (features extractor) and reuse it in order to solve our specific problem.

![alt text](https://github.com/buropas/Custom_Object_Classification/blob/main/VGG16.png?raw=true)
![alt text](https://github.com/buropas/Custom_Object_Classification/blob/main/VGG16_2.png?raw=true)

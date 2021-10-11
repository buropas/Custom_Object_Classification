# Transfer Learning for Custom Object Classification (VGG16)

We can think of TRANSFER LEARNING as utilizing the feature learning layers of a pre-trained CNN to classify a different problem than the one it was created for, without retraining the Convolutional Blocks of the network but simply adding a Custom Classification Head (one or more Fully Connected Layers) on top of Convolutional part.  Then, only Fully Connected Layers are trained on our own custom dataset in order to solve our specific classification task.

For istance, we can take a Neural Network, called VGG16, that was trained on the ImageNet dataset, containing more than 14 million high-resolution images belonging to 1000 different labels.  The idea is to take advantage of the Feature Learning part of this network (features extractor) and reuse it in order to solve our specific problem.

 <br/>
 
![alt text](https://github.com/buropas/Transfer_Learning_for_Custom_Object_Classification/blob/main/VGG16.png?raw=true)
![alt text](https://github.com/buropas/Transfer_Learning_for_Custom_Object_Classification/blob/main/VGG16_2.png?raw=true)
   
 <br/> 
   
## Folder content:

- Transfer Learning Custom Object Classification - VGG16 (Notebook)
- csv_format_custom_object_classification.png (image)
- VGG16.png (image)
- VGG16_2.png (image)

## Technologies      
Image Classification Model: VGG16         
Libraries: Tensorflow, Keras, Sklearn, Matplotlib, Numpy   
Language: Python

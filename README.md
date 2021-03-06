# Image_Caption
Predicting Captions for Images using AI

The model helps in predicting captions regarding an image, it uses Word Embeddings, Transfer Learning, RNN, Text and Image Pre-Processing techniques for the prediction and text generation. The dataset used is flicker8 dataset from Kaggle and the model is inspired by Microsoft CaptionAI.

The problem can be recognized as a Supervised Learning Problem as there are multiple data points corresponding to an image. I have used techniques like Transfer learning which helped in training the model on a resnet50 pretrained model with weights as imagenet. Other than that, Text Preprocessing and Image Preprocessing have been used so as to convert the images and text into a feature vector. Since the estimated requirement of the number of blocks would require approximately 3GB of main memory, so to ensure the space and memory taken would be less, we have used the Data Generators. A glove.6B.50d.txt file is used to provide embedding to the words. The training was done using the Mini-Batch approach. The correct ground truth was given as an input during the training phase. 


![a1](https://user-images.githubusercontent.com/41800767/77341627-ff87ed00-6d54-11ea-93dc-f2acc41dcce4.png)
![a2](https://user-images.githubusercontent.com/41800767/77341785-470e7900-6d55-11ea-9914-b97bba9da7f3.png)
![a3](https://user-images.githubusercontent.com/41800767/77341810-4c6bc380-6d55-11ea-8602-7857676c5c76.png)
![a4](https://user-images.githubusercontent.com/41800767/77341907-69a09200-6d55-11ea-850f-d03ff289771d.png)





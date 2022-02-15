# Hand-Drawn-Sketches-Prediction
Using Transfer learning for hand drawn doodles predictions live in browser.

## Overview
This was just a fun experiment to make predictions on hand-drawn sketch or doodles using transfer learning.
For this, I used <a href="https://github.com/yining1023/doodleNet" target="_blank">'DoodleNet'</a> Convolutional Neural Network (CNN) model.
This model was created by <a href="https://github.com/yining1023/doodleNet" target="_blank">'Yining Shi'</a> and the model is hosted on ml5 library. So using p5 and ml5, I was able to write a small and high level code to load the pretrained model and then make a prediction on the model.
                                               
## Code and Resources Used
- JS, HTML, CSS
- Tensorflow.JS 
- Packages: ml5.JS, p5.Js.


## Dataset and EDA

This pretrained model was trained using 345 categories of doodles with 50K images per category dataset,
which is gives total 17,250,000 images, so getting the data, preprocessing and training the data would have taken 
alot of time and resources. This data was collected from <a href="https://quickdraw.withgoogle.com/" target="_blank">"Google’s Quick, Draw!"</a> game, 
which at this point contains 50M hand-drawn images. To check the data and categories please visit  <a href="https://quickdraw.withgoogle.com/data" target="_blank">"Google’s Quick Draw!, The Data".</a> 

some examples from the 101Food datasets:

![alt text](https://github.com/ozzmanmuhammad/FoodVision/blob/main/Images/Food101_examples.png "Train data examples")

## Model Building and Performance

Model was loaded and predicted using ml5 JS libaray, which provides high level coding interface for users, so that they can easily deploy and
the models that are hosted by ml5. Build mostly using p5-1.4.1 library.
<br/><br/>

## Predictions on Custom Images
The model predicts all the 10 images correct with high probability score. These images were collected from different sources.
<img src="https://github.com/ozzmanmuhammad/FoodVision/blob/main/Images/predictions_custom_images.png" alt="Custom Predictions" width="700"/>

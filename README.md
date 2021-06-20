## Predicting the evaluative age-classification of video games using the image features of the video game cover art

Attempt to predict if a video game will have PEGI age rating over or under 16 (binary classification problem). Instead of using all pixel values of the images as 
features, features are extracted from the images. Examples of these features are the presence of human faces in the covers and the median brightness of the covers. 
The relevance scores of all features are then extracted from the model to analyze which information contained in the images is most useful for this task. The best model
 has an accuracy of roughly 73%. We found that human level performance on this task is around 70%.
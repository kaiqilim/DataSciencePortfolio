# Facial Keypoints Detection

### Matthew Brimmer, Kai Qi Lim, Rodrigo Luna, Joe Mercer

This project is based on Kaggle competition for facial keypoints detection (https://www.kaggle.com/c/facial-keypoints-detection). The goal is to identify 15 key points on eyes, nose, mouth from a set of images.

Challenges encountered in this project included variations in position of the face on the image, lighting and presence of sunglasses.

The final model is a Keras 5 layers of 2D Convolution network with Maxpooling2D as filtering and three final dense layers to estimate parameters. The RMSE achieved was 13.4 compared to baseline model of 77.8.

![sample prediction](/images/predicted.png)

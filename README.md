# binary_classifcation_uisng_svm
Have vou ever watch the movie alien vs predator? Guess yes... Through our visual capability, it's easy for us to differenciate them. Here by using AI, we will try to achieve the same result. We develop a CNN+SVM classifier to predict if a given image is a predator image or an alien image. Therefore we have a binary classifcation to train from scratch. Acceptable result have been obtained but can be imporved by adopting transfer learning technique.

## Model
![model_plot](https://user-images.githubusercontent.com/48753146/155255846-c545c642-13b6-48c6-8c50-44c12065ca90.png)

## Ploting preformance
### Accuracy
![acc_plot](https://user-images.githubusercontent.com/48753146/155255928-be569c2e-e2d2-40f9-80ae-14addd399493.png)

### Loss
![loss_plot](https://user-images.githubusercontent.com/48753146/155255932-b5fc3545-78bb-4f2c-8b62-fdd51fa251cb.png)

The network have been trained for only 15 epochs and has been able to reach 70%+ accuracy. You can trained for longer to achieve better results. 

## Dependencies
1. Tensorflow
2. Matplotlib
3. OpenCV
4. Numpy

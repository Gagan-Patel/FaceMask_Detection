#                                                                     FaceMask_Detection
![OIP](https://user-images.githubusercontent.com/122751229/230236143-bc26e292-da47-4434-8eed-e6edfbeab689.jpg)

### About Project
This project uses a Deep Neural Network, more specifically a Convolutional Neural Network, to differentiate between images of people with and without masks. With the webcam capturing the video, the frames are preprocessed and and fed to the model to accomplish this task. The model works efficiently with no apparent lag time between wearing/removing mask and display of prediction.
The model is capable of predicting multiple faces with or without masks at the same time

### Image Processing
Before implementing face mask detection problem, first we need to understand that how to handle images. Images are simply a collection of colors in red, green and blue format. As a human we see an image with some object or shape in it, but for computer it is just an array with color values range from 0 to 255.

### Steps to Perform Image Processing :
- Load images using Python or any other programming language.
- Convert images into array
- And finally apply some algorithm on that array.
### Face Detection Using OpenCV
 Face detection algorithm was introduced by Viola and Jones in 2001. They divided this algorithm in four stages :

1. Haar Features Selection
2. Integral Images
3. AdaBoost
4. Cascading Classifier

### Data preprocessing
Real- time data is used in this, so camera is required or data can be replaced with any url of image/video.

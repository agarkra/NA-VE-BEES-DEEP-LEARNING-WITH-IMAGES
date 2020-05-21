# NA-VE-BEES-DEEP-LEARNING-WITH-IMAGES

In this project we are doing classification on the image to identify if the bee in image provided is a honey bee or a bumble bee.
It becomes challenging when we do this with the help of their apperances in the image, position and image resolution.

This notebbok can be used by a individual who is starting working on classification of image as in this project we will be designing a simple deep learning model to detect honey bee or a humbe bee.

The project has these major components
-Importing python libraries like 
  pickle
  pandas
  numpy
  sklearn
  keras
  matplot
  skiimage
  
- Loading image data
  In this we will load our labels.csv file into a DataFrame called labels, where the index is the image name (e.g. an index of 1036 refers to an image named 1036.jpg) and the genus column tells us the bee type. genus takes the value of either 0.0 (Apis or honey bee) or 1.0 (Bombus or bumble bee).

- Now we will examile the Red Green Blue Color in the loaded image dataset

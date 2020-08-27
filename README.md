[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/vgg16_model.png "VGG-16 Model Layers"
[image3]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Project Overview

This project is part of the Machine Learning Engineer Nanodegree! In this project, we developed a Python application that can identify whether a human or a dog is present in a given image and estimate the corresponding or most resembling dog breed. This application can be expanded onto a web or mobile app to process real-world, user images.

We explore the use of Convoluted Neural Network (CNN) models and other artifacts for classification and localization to improve the accuracy of the classifications (at least 80%). The resulting application will be imperfect, but accurate enough to determine with high accuracy the dog breed.

## Requirements

1. Python 2.7 or higher
2. NumPy
3. Pandas
4. Sklearn
5. Matplotlib
6. Jupyter notebook
7. OpenCV
8. Pillow

## Dataset

1. [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).

2. [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).

### Instructions

1. Clone the repository and navigate to the downloaded folder.

	```
		git clone https://github.com/abkoma/dog-breed-project.git
		cd dog-breed-project
	```

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder.

4. Make sure you have already installed the necessary Python packages according to the requirements above in the program repository. Anaconda is highly recommended.

5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

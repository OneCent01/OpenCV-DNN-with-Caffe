# OpenCV-DNN-with-Caffe
Detect faces on images and video using OpenCV's dnn module and pre-trained caffe models


Provides two functions of interest:
  1. detect_face
  2. detect_video_faces

## Getting Started

1. Make sure you have Python2 or Python3 installed
2. Clone the repo
3. Setup virtual environment
4. Install dependencies from requirements.txt
5. Running Jupyter Notebook

### Prerequisites

Were going to need to install pip, virtualenv, and the packages listed in the requirements.txt file. 

Currently only have Mac terminal commands. I think it works with Git shell as well for Windows users.

If there are any questions to help get started please post them!

### Installing

1. Open the terminal

2. Clone the repo 
```
git clone https://github.com/OneCent01/OpenCV-DNN-with-Caffe.git
```

3. Install pip

```
sudo easy_install pip
```
4. Install virtualenv

```
sudo -H pip install virtualenv
```
5. Navigate to the cloned repo directory
6. Create a virtualenv

```
virtualenv env
```

7. Activate virtualenv

```
source env/bin/activate
```

8. Install packages from requirements.txt

```
pip install -r requirements.txt
```

### Running it: 
  1. Navigate to the root directory where you cloned this repo in terminal/git bash/command prompt
  2. Drag videos or photos you want to have scanned for faces into any accessible folder in your local env
  3. Run this command in your root dir
```
jupyter notebook "Caffe DNN.ipynb"
``` 
  4. Navigate to the Jupyter local server provided in your terminal
  5. Use Jupyter local server UI to run `Caffe DNN.ipynm` to track faces via documentation below

  - a) For images: call the detect_faces function with the path to the image, assign it to a variable and display it or save it to an output folder. 
    
  - b) For videos: call detect_video_faces with the path to the video. It will automatically be processed into a file named `output.mov` in the root folder of this directory

# OpenCV-DNN-with-Caffe
Detect faces on images and video using OpenCV's dnn module and pre-trained caffe models


Provides two functions of interest:
  1. detect_face
  2. detect_video_faces

Requirements: 

  1. numpy 
  - easily pip/pip3 installed 
  2. OpenCV 
  - full library must be installed and available to import as cv2
  - ceasily pip/pip3 installed with opencv-python 
  3. Jupyter
  - easily pip/pip3 installed 
    
Running it: 
  1. clone this library and install all dependencies
  2. drag videos or photos you want to have scanned for faces into any accessible folder in your local env
  
  3.
  - a) For images: call the detect_faces function with the path to the image, assign it to a variable and display it or save it to an output folder. 
    
  - b) For videos: call detect_video_faces with the path to the video. It will automatically be processed into a file named `output.mov` in the root folder of this directory

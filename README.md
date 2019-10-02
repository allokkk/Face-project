Face Recognition using Haar-Cascade Classifier, OpenCV, and Python

 Simple Face Recognition algorithm using Python and OpenCV

Prerequisites
  Numpy
  OpenCV

Installing

  Install Numpy via anaconda: conda install numpy

  Install OpenCV via anaconda: conda install -c menpo opencv

Outline
This project consist of 2 parts, which are:

  1.Creating datasets and Training of model (Generating selfie Training Data Using Webcam.ipynb)
  2.Face Recognition (face_recognition.py)
  
  
How to run ?
Make sure have executable permission.
pip install -r requirements.txt
Please make sure that you have folders called 'datasets' and 'trainer' in the same directory. (Optional, I have put the code so it will create if it's not exist.)
Run in the command line the(Generating selfie Training Data Using Webcam.ipynb) for taking your face image as datasets. Don't forget to set  each person's face to unique ID or name  everytime you run to update dataset and training If you have more face to be include,
Lastly, run face_recognition.py




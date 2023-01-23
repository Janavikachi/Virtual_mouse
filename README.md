# Virtual_mouse
This project proposes an AI virtual mouse system that makes use of the hand gestures and hand 
tip detection for performing mouse functions in the computer using computer vision. The main 
objective of the proposed system is to perform computer mouse cursor functions and scroll 
function using a web camera or a built-in camera in the computer instead of using a traditional 
mouse device. Hand gesture and hand tip detection by using computer vision is used as a HCI 
with the computer. With the use of the AI virtual mouse system, we can track the fingertip of 
the hand gesture by using a built-in camera or web camera and perform the mouse cursor 
operations and scrolling function and also move the cursor with it.Python programming 
language is used for developing the AI virtual mouse system, and also, OpenCV which is the 
library for computer vision is used in the AI virtual mouse system. 

# Pre-requisites
Python: (3.6 - 3.8.5.

Anaconda Distribution.

# Procedure
'git clone https://github.com/Janavikachi/Virtual_mouse.git'

Step 1:
open anaconda cmd

conda create --name gest python=3.8.5

Step 2:

conda activate gest

Step 3:

pip install -r requirements.txt

Step 4:

conda install PyAudio
conda install pywin32

Step 5:

cd to the GitHub Repo till src folder
Command may look like: cd C:\Users\.....\Gesture-Controlled-Virtual-Mouse\src

Step 6:

For running Voice Assistant:

python Proton.py
( You can enable Gesture Recognition by using the command "Proton Launch Gesture Recognition")
Or to run only Gesture Recognition without the voice assisstant:
Uncomment last 2 lines of Code in the file Gesture_Controller.py

python Gesture_Controller.py

# Virtual_mouse

Pre-requisites
Python: (3.6 - 3.8.5)
Anaconda Distribution.

Procedure

Step 1:

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

# Mascara_IA

Project of facial recognition of people with and without mask

Requirementes:
Pycharm 
Python interpreter = 3.11
imutils = 0.5.4
keras = 2.14.0
numpy = 1.26.0
pip = 23.2.1
sklearn = 0.0.post9
scikit=learn = 1.3.0
tensorflow = 2.13.0
wheel = 0.38.4
Obs: I was getting some issues using visual code, so with Pycharm it worked fine

This code should run in your pyhton virtual environment

Steps

1 - Open the train_mask_detector.py
2 - On line 26 change the help according to your local dataset repository
3 - On line 30 change the help according to your local mask_detector_model repository
4 - You should first train the AI to detect people with and withou mask so for that run the following command : python train_mask_detector.py -d "(your path)/dataset"
5 - Go to WebCameraDetection.py and on line 72 you alternate the src from 0 to 1 or 2 according to your camera settings, by default the laptops cameras are 0 but double check it
6 - After finishing it go to WebCameraDetection.py and run the file
7 - Sometimes the file can crash due to lack of memory or the camera size settings
8 - If you want to change the size of capture you can go to line 15 where there is a 300,300 size and change it according to your wish
9 - If you want you can add more images in with_mask and without_mask foldes and run the train file again so the capture can be more accurate

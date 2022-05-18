# Volume-Control-Using-Hand-Gesture

In this project iam  going to use Gesture Control to change the volume of a computer. At first look into hand tracking and then opencv will use the hand landmarks to find gesture of our hand to change the volume. This project is module based which means i will be using a previously created hand module which makes the hand tracking very easy.

Requirements

* Python 2.6 or Greater
* OpenCV 2.3 or Greater (Tested on OpenCV 2.4)
* python-numpy module
* (Optional) python-matplotlib (for plotting)
* Numpy 
* Math


If you are getting an error getting the x and y value using hand['lmList'][8] then use hand['lmList'][8][:2] instead.
This is because the latest version of cvzone consists of x,y,z values instead of only x,y.  So you have to define that you only need the first two elements by adding [:2]



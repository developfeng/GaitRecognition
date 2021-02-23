------------------------------------------------------------------------
* Gait demo for Tutorial V1.0                     
* By Chunfeng Song                                
* E-mail: chunfeng.song@nlpr.ia.ac.cn                   
------------------------------------------------------------------------
 ![img](https://github.com/developfeng/GaitRecognition/blob/master/ToyGaitDemo.gif)

i.    Overview
ii.   Copying
iii.  Use

i. OVERVIEW
-----------------------------

This gait recognition demo needs clean background, e.g. a white wall. 
As this demo only takes GEI as its feature, so it can only recognize 
persons with same views. For example, people walk with the same angle for both 
registration and recognition.

This code is one part of the Tutorial of ICPR 2016.

ii. COPYING
-----------------------------
We share this code only for research use. We neither warrant correctness 
nor take any responsibility for the consequences of using this code. 
If you find any problem or inappropriate content in this code, feel 
free to contact us.

iii. USE
-----------------------------
This code should work on Windows or Linux, with Python and OpenCV.
We highly recommend you install Anaconda (python 2.7) and OpenCV2.4:

1) You should install the python libraries (including PyQt4, numpy, PIL)and 
OpenCV.
2) Type 'python GaitDemoV1.py' in the command line. Then press 'Enter' button to 
start this demo.
3) Firstly, you need to type your name in the 'Name' box and click the 'Register'
 button to record the human GEI into the database. Then the human can walk 
 in front of the camera. After several frames, you need to click the 'Save' 
 button to save.
4) Now, you can click the 'Recognize' button to have a test.
5) Sometime, you need to click 'UpdataBk' button to refresh the background.
6) The GEIs will be saved in './gei/'.

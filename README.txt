------------------------------------------------------------------------
* Gait demo for Tutorial V1.0                     *
* By Chunfeng Song                                *
* E-mail: developfeng@gmail.com                   *
------------------------------------------------------------------------

i.    Overview
ii.   Copying
iii.  Use

i. OVERVIEW
-----------------------------

This gait recognition demo needs clean background, e.g. a white wall. 
As this demo only takes GEI as its feature, so it can only recognize 
the same view. For example, people walk with the same angle for both 
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
We highly recommend you install Anaconda and OpenCV2.4:

1) If you have install the python (including PyQt4, numpy, PIL)and 
OpenCV.
2) Type 'python GaitDemoV1.py' in command line. Then pressEnter button to 
start this demo.
3) Firstly, you need to type your nam in the Name box and click Register
 button to record human GEI into the database, now the human can walk 
 in front of the camera. After several frames, you need to click Save 
 button to save.
4) Now, you can cliak the Recognize button to have a test.
5) Sometimes, you need to click UpdataBk buttont to refresh the background.
6) The GEI will be saved in './gei/'.
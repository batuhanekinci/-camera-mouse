# webcam mouse
Control your mouse using your webcam

**Requirements
1-PyAutoGui
2-OpenCV 3
3-Numpy
4-Since I am using threads in the program the first thing you need to do is go to the site mentioned and apply the solution given. Here is the website https://stackoverflow.com/questions/36809788/importerror-no-module-named-thread

First run the range-detector.py to set the range for the mask for colour segmentation. The easiest way to use it is to put the yellow paper in front of the camera and then slowly increasing the lower parameters(H_MIN, V_MIN, S_MIN) one by one and then slowly decreasing the upper parameters (H_MAX, V_MAX, S_MAX). When the adjusting has been done you will find that only the yellow paper will have a corresponding white patch and rest of the image will be dark.Press 'q' to exit. Your configuration will be saved. Then run the mouse.py file.

**python3 range-detector.py -f HSV -w
**python3 mouse.py

Got a question?
**You can ask your questions at batuhanekinci78@gmail.com

-Knowledge-
You can do the project using vmware and ubuntu 16.04.You also need to load these resources with the order of pyautogui, thread, numpy, cv2, kernel error.


# Self-Driving-Car
Following along an online course that focuses on deep learning applied on self driving cars

1- I'm performing edge detection on a video of a car driving on a road. 

2- I define a region of interest within the each frame of the video. 

3- Then I extract the edges of the road lanes by using the frame image and a mask image to combine between the two using bitwise addition.

4- I then perform Hough Line Transform on the resulting image of the bitwise addition.

5- This gives me a set of lines that were detected from drawing the edges of the lanes.

6- By averaging these lines using their slopes and intercepts, I can get clearly defining lines for road lanes.

7- I merge these lines with the test video to display how the program is able to detect the road lanes.

8- Next goal is to optimize this and perform image recognition on road signs

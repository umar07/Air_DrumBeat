# Air Drums

An air-drum system, which uses object detection by color separation method and python-autoGUI library to play drum beats according to the position of the stick.

The end-point of the stick, which is of a constant color is detected by creating a mask and finding the corresponding contour of the region. The centroid point of the closed contour is used to track the movement of the stick as a cursor through the AutoGUI library. Various drum sounds are placed in portions of the screen and are played accordingly to the position of the stick. Thus, making an Air-Drum system.

# Moving-Car
This is a simple program to move a car made using C graphics.

## The various functions used in the program are:
**line(x1, y1, x2, y2)**

A function from graphics.h header file which draw a line with (x1, y1) as first coordinate of line and (x2, y2) as second coordinate of the line.


**arc(int x, int y, int start_angle,int end_angle, int radius)**

arc() function which draws an arc with center at (x, y) and given radius. start_angle is the starting point of angle and end_angle is the ending point of the angle.
The value of the angle can vary from 0 to 360 degree.


**setcolor(n)**

A function from graphics.h header file which set the color of the pointer (cursor). There are some predefined colors in computer graphics. Here n is color number.


**delay(n)**
This function is used for holding the program output for a small period of time since processing is very fast so use it to see the result.


**floodfill(int x, int y, int border_color)**

floodfill() function is used to fill an enclosed area. Current fill pattern and fill color is used to fill the area.(x, y) is any point on the screen.If (x,y) lies inside the area then inside will be filled otherwise outside will be filled,border specifies the color of boundary of area. 

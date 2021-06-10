**Project Description**: Calculate position (X,Y) and plot graphical representation of components placed at the vertices of a geometric shape.

**Motivation**: As my _PCB software CAD_ didn't have the feature of placing components equally spaced in a circle, I created my solution by calculating the (X,Y) coordinates + rotation angle of each element:

<img src="https://github.com/RicardoATB/plot-vertices-position/blob/main/output/board-top.png" width="80%" height="80%" /><br /><br />

**Input example**: `./plot-vertices.py --vertices 8 --width 3 --height 5 --diameter 50 --flat no --output vertices.txt`

**Output**:

<img src="https://github.com/RicardoATB/plot-vertices-position/blob/main/output/output.gif" width="65%" height="65%" />


Output file containing (X,Y) position and inclination angle for each vertex-element:
```
#  X       Y            Comment
 20.79 	 -8.61	# vertex  1 @ -112.50°
 20.79 	  8.61	# vertex  2 @  -67.50°
  8.61 	 20.79	# vertex  3 @  -22.50°
 -8.61 	 20.79	# vertex  4 @   22.50°
-20.79 	  8.61	# vertex  5 @   67.50°
-20.79 	 -8.61	# vertex  6 @ -247.50°
 -8.61 	-20.79	# vertex  7 @ -202.50°
  8.61 	-20.79	# vertex  8 @  202.50°
```



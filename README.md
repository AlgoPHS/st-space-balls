SPACE BALLS PROGRAM DESCRIPTION
Chris Pan, 
Brendan DeMilt


The program "Space Balls" is Brendan's creative name for the Barnes Hutt
algorithm. This algorithm is an n-body space simulation that has nlogn complexity.
The algorithm groups nearby bodies and approximates them as a single body.
To tell if 2 nodes can be grouped, use the test s/d < 0.5, s being the width of 
the region represented by internal node, and d is distance between body and the
center of mass. If 2 bodies have positions (x1, y1) and (x2, y2), with masses 
of m1, and m2, then the approximated body has:

m = m1 + m2
x = (x1m1 + x2m2) / m
y = (y1m1 + y2m2) / m

The data structure we use is the quad-ST-tree, the node has a planet, and its 
corresponding square representing 2d space. The root node represents the whole
plane, with children splitting it up evenly into 4 squares. The symbol table
works well, bc we need to store 2 different objects and build a data structure.
We chose this program because Brendan is a space fanatic and also an oppressive
dictator that wouldn't let Chris do the smooth zoom.


ENJOY 

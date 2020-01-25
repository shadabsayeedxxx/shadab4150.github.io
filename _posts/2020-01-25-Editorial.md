# CodeChef Folding Paper Editorial 

* Link [**Question**](https://www.codechef.com/problems/PAPER)

### Problem Statement

Chef has a rectangular piece of paper. He puts it on a big board in such a way that two sides of the paper are horizontal and two are vertical, and then he performs a sequence of N operations. 
You are given a string S with length N; for each valid i, the i-th character of S determines the type of the i-th operation:

* 'R': Pick up the paper from the right side and fold it onto the left side.
* 'L': Pick up the paper from the left side and fold it onto the right side.
* 'U': Pick up the paper from the upper side and fold it onto the bottom side.
* 'D': Pick up the paper from the bottom side and fold it onto the upper side.

The paper is folded in such a way that there is still a flat rectangular sheet of paper lying on the table after each operation, but it consists of multiple layers of the original sheet. 
The lengths of the horizontal and vertical sides of the resulting sheet (after performing these N operations) are W and H respectively. 
Let's build an Euclidean coordinate system on the paper, where the point (0,0) corresponds to the bottom left corner and (W,H) to the upper right corner.

Chef then draws M points on this folded sheet of paper. 
The ink used to draw them soaks deep into the paper, so each point is drawn on all layers of the paper (and also on both faces of each layer).

Finally, Chef completely unfolds the paper. He's asking you to compute the distance between the nearest pair of points.

### Solution idea:







### Code
'''python3

'''

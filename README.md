# Linear-Regression
This program is to practice do not use any module or package to draw a best fit line for this dataset.


## Cost Function
H(X)= a*X + b → This line to all of data point's total Y direction sum of squares.

*a = Slope, b = y-intercept*

![alt text](https://raw.githubusercontent.com/ahoucbvtw/Linear-Regression/main/Picture/Cost%20Function.png "Cost Function")


## Gradient Descent
The minimum of Cost Function.

Partially differentiate a and b in the cost function. To put it simply, it is to calculate the slope a and y-intercept b in a line → H(X)= a*X + b

![alt text](https://raw.githubusercontent.com/ahoucbvtw/Linear-Regression/main/Picture/Gradient%20Descent.png "Gradient Descent")


## Conclusion
	 
|1 / times iteration| Cost Function | Best Fit Line |
|---------|---------| ---------| 
| 50000 | 4.714 | H(x) = 1.031x - 2.282 |
| 200000 | 4.478 | H(x) = 1.182x - 3.788 |
| 2000000 | 4.477 | H(x) = 1.193x - 3.896 |

In this table we can see 50000 times iteration and 200000 times iteration's Cost Function is decrease obviously, but in 2000000, the Cost Function is not decrease obviously.

Thus, I used dataset's x coordinate as line's x coordinate to find this line's y coordinate, and show in picture below.

**No Best Line** in Population & Profit Compare ：

![alt text](https://raw.githubusercontent.com/ahoucbvtw/Linear-Regression/main/Picture/No%20Best%20Line%20in%20Population%20%26%20Profit%20Compare.png "No Best Line in Population & Profit Compare")

**Best Line** in Population & Profit Compare ：

![alt text](https://raw.githubusercontent.com/ahoucbvtw/Linear-Regression/main/Picture/Best%20Line%20in%20Population%20%26%20Profit%20Compare.png "Best Line in Population & Profit Compare")

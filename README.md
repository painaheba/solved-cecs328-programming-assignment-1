Download Link: https://assignmentchef.com/product/solved-cecs328-programming-assignment-1
<br>






<h1>2        Euclidean Adjustments</h1>

An astronomer is making measurements with his telescope when he notices that his vision field is off by <em>x </em>micronanometers (which we will assume is a measurement that exists) to the right. His telescope can only be moved to the right or to the left, however, and only via his automated, highly-calibrated machinery by certain predetermined fixed integer amounts. If, for example, one of these amounts is 7 micronanometers, then he can move his vision field by any multiple of 7 micronanometers to the left or right.

Given a value of <em>x </em>and a set {<em>m</em><sub>1</sub><em>,m</em><sub>2</sub><em>,…,m<sub>n</sub></em>} of predetermined fixed movement amounts, your job will be to advise the astronomer as to which of the movements to choose, how many times the movement should be applied, and the direction of the movement so that he can make his field of vision perfect. You may assume that <em>x </em>is a standard Java integer, but you may want to use the java.BigInteger class for the <em>m<sub>i</sub></em>.

It is guaranteed that a solution exists.

<h1>3        Input/Output</h1>

The input file (input.txt) in the home directory will consist only of positive integers. The first line will be the value of <em>x</em>. The following lines will hold the values of the <em>m<sub>i</sub></em>, one per line.

Your output file (output.txt) should hold a sequence of lines with 2 singlespace-separated numbers per line. These will be interpreted as instructions for telescope movement. The line <em>m<sub>i </sub>y</em>

will mean to move the telescope <em>m<sub>i </sub></em>micronanometers <em>y </em>times. (If <em>y </em>is positive, then it will be moved to the right; if <em>y </em>is negative, then it will be moved to the

left.)

1
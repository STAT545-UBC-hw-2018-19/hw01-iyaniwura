# Homework I

This repository was created for homework I. It contains an addition file called *hw01_instructions.md* which is a Markdown file that contains information about the homework.


# Introduction
 I am Sarafa Iyaniwura, a third year PhD student at the  [*Department of mathematics*](https://www.math.ubc.ca/) and [*Institute of Applied Mathematics*](http://www.iam.ubc.ca/) of the [*University of British Columbia*](https://www.ubc.ca/), Vancouver.
 
Prior to coming to UBC, I was at the [*African institute for mathematical sciences*](https://aims.ac.za/) (AIMS), South Africa, where I did a masters of Science in mathematical sciences. My current research involve modeling biological systems, analysis the model using matched asymptotic method, and also solving the models  numerically. Click [*here*]( http://www.math.ubc.ca/~iyaniwura/) for more information on my research and the classes I have thought at UBC. Below are my current supervisors and their specializatons:

1. [*Michael Ward*](https://www.math.ubc.ca/~ward/)
    * Apllied Analysis
    * Asypmtotic Analysis
2. [*Colin Macdonald*](https://www.math.ubc.ca/~cbm/research/)
    * Numeircal Analysis
    * Scientific Computing
3. [*Daniel Coombs*](https://www.math.ubc.ca/~coombs/)
    * Cell signaling 
    * Modelling Virus dynamics
 
Below is a smple of the code I wrote in Matlab:

~~~
function plotcircle(x,r)
theta = 0:0.05:2\*pi;
hold on
plot(x(1)+r\*cos(theta),x(2)+r\*sin(theta));
axis equal;
end
~~~
This Matlab function plot a circle of radius r centered at position x.

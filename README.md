<h1>RandomSampleArea</h1>

12/2023 <br>
University Project

# The Task

The goal of this project is to approximate the area under the curve described by the function:

$y = 10 + x^2 - 0.1x^3$


#### 2.1 Trapezium Rule

The trapezium rule is a numerical method for approximating the area under a curve by dividing the area into trapezia. Each trapezium’s area is calculated as:

$A_{\text{trapezium}} = \frac{a + b}{2} \cdot h \$

where:

- $a$ and $b$ are the function values at the endpoints of the trapezium.
- $h$ is the width of the trapezium.

**Assessment (Option 2, Part 1):**

- Approximate the area under the curve from $x = -10$ to $x = 10$ using the trapezium rule.
- Build the model using numerical methods introduced in the course, avoiding `scipy.integrate`.
- Compute the area of each trapezium, sum these areas, and print the total area.

#### 2.2 Random Sampling

Random sampling is a technique used to estimate the area under a curve by sampling points randomly within a defined range. By comparing the number of points falling under the curve to the total number of points, you can estimate the area.


**Assessment (Option 2, Part 2):**

- Approximate the area under the curve from $x = -10$ to $x = 10$ using random sampling.
- Generate random (x, y) positions within the expected range.
- Calculate the ratio of points under the curve to the total number of points to estimate the area.
- Print the result.

**True Area:** The exact area under the curve is `866.6` . Compare your approximations to this value to evaluate their accuracy.

**Mark:** For this project I achieved a 75/100

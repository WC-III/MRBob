---
switcher-label: Subunit
---
# 1.2-3: Rates of Change

## Subunits
This section is split into these following subunits:

* 1.2: Rates of Change
* 1.3: Rates of Change in Linear and Quadratic Functions

<!-- 1.2 -->
## 1.2 Overview {switcher-key="1.2"}
Back in 1.1, Rate of Change was brought up, which is expanded on much more in this subunit.
Rate of Change is a very large pillar of the AP exam, which means it is present all over.

### The Specifics
"Rate of Change" is the umbrella that contains two different things.
One of those is *Average* Rate of Change, which is often what it's referring to in APPC.
In fact, the prior subunit's definition of RoC uses the ARoC definition.

> There is another kind, being *instantaneous* rate of change, but I don't like that definition for the first time you hear it.
It isn't important for APPC, but it's a major component of AP Calculus.
{style="note"}

### Calculating

Many times, the formula $\frac{y_2-y_1}{x_2-x_1}$ is used to represent average rate of change.

> If you see "$\Delta$" in front of a variable, it means "the change of".
$\frac{\Delta y}{\Delta x}$ is the same as the above formula.

This means, when given two points, such as $(3, 5) \; \&\& \; (7, 12)$, you can assign the intervals to respective variables, and solve:

$$
\begin{align*}
x_1 = 3 \\
x_2 = 7 \\
y_1 = 5 \\
y_2 = 12
\end{align*}
$$
$$
\frac{12-5}{7-3}
\to
\frac{7}{4}
$$

The above concludes that $\frac{7}{4}$ is the average rate of change across the two points.

> A "secant line" is asking for ARoC most of the time.
Really, the definition is a line drawn between two points on a function, but it's in the context of rates of change a lot of the time.
{style="note"}

### 1.2 Conclusion

This is really just a precursor to 1.3, most times.
Yes, there is some activity on determining if the slope is positive or negative, but realistically, you've already done that by now.

<!-- 1.3 -->
## 1.3 Overview {switcher-key="1.3"}
Finally, we get to our first two pieces of one type of standard function: linear and quadratic.

### AROC Recap
To quickly recap, last subunit was on rate of change and how it's calculated, now to quickly put it in terms of a graph.

![some weird graph](1.3.recap.png)

From the two points listed, you can easily calculate the rate of change, were a secant line drawn through the two.
Which is also just the average rate of change between the two points.
For reference, it's $\frac{-1.62276 - 2.07979}{0.59307-(-0.84307)} \to -2.578$

> More often than not, numbers will not be this messy.
While in introduction topics, people usually use nice clean whole numbers, I'm showing you the ugly things first.
On the AP Exam, it might get a little worse, but NEVER will it be worse than what I give here.
Just preparing for the worst is all.
{style="note"}

### Functions
Linear and quadratic functions both have formal definitions in terms of their rate of change.

Linear Function
: A function where the average rate of change is always constant across any length input interval.

Quadratic Function
: A function where the average rate of change is changing at a constant rate across equal-length input intervals.

As an example, for a linear function of $f(x) = 3x + 2$, the result of $\frac{\Delta y}{\Delta x}$ will always be 3.
Time for another graph, this time something simple.

![A graph of the equation f(x) = x^2](1.3.arocquad.png)

The table below is a table of points:

|x|y|
|-|-|
|0|0|
|1|1|
|2|4|
|3|9|
|4|16|

With a little bit of other math, it ends up resulting in the AROCs of $1, 3, 5, 7$.
This proves a quadratic function, since each AROC across **equal-length input intervals** is increasing by 2.

> The phrase "equal-length input intervals" is another AP Exam term to take note of.
Yet another phrase you'll need to use in your FRQs.
{style="note"}

### 1.3 Conclusion
While simple, this is a somewhat important clarification for later math and 1.4.
# 3.13-15: Polar Functions

This section contains these following subunits:

* 3.13: Trigonometry and Polar Coordinates
* 3.14: Polar Function Graphs
* 3.15: Rates of Change in Polar Functions

<!-- 3.13 -->

## 3.13 Overview{switcher-key="3.13"}
All of unit 3 has been leading to this.
Every formula, every identity, it's about time we get here.

### Terms
Polar Graph
: A graph comprised of concentric circles.
Uses Polar Coordinates in lieu of Cartesian Coordinates

Pole
: The polar equivalent of the origin on a Cartesian Plane

Polar Axis
: The polar equivalent of the x-axis on a Cartesian Plane

"$\theta = \dfrac{\pi}{2}$" Axis
: While it has no official name, it's the polar equivalent of the y-axis.

Polar Coordinates
: A coordinate system comprised of the radius and the angle, usually $(r, \theta)$.

### Coordinate Review
There are two planes we've learned.
The cartesian plane, which is $(x, y)$.
And, there's the complex plane, which while not discussed as heavily in APPC, it's $(x, yi)$.

Polar coordinates follow the pattern $(r, \theta)$.
This, expanded, is the radius of the circle, followed by the angle of the point.
The polar plane is full of concentric circles, which means circles in circles.

![An example of a polar graph](3.13.polargraph.png)

### Representations
A polar coordinate can be represented an infinite amount of ways.
Since a full circle is $2\pi$ radians, anything past that will wrap around.
Not to mention, $\theta$ can be negative, indicating a clockwise rotation instead of a counterclockwise rotation.

Usually when you run a polar coordinate, you start with the radius, which will go right when positive and you 
essentially rotate from there.
With a negative $r$ value, you start from the left instead of the right.

> A negative $r$ value does NOT indicate a negative radius, just that the point is "reflected", so to speak.
{style="warning"}

By this metric, $\left(3, \dfrac{\pi}{3}\right)$ is the same as $\left(3, \dfrac{7\pi}{3}\right)$, and $\left(-3, 
\dfrac{4\pi}{3}\right)$.

### Conversions
These use four formulas you've learned already.
$$
\begin{align*}
x &= r\cos\theta \\
y &= r\sin\theta \\
r^2 &= x^2 + y^2 \\
\frac{y}{x} &= \tan\theta
\end{align*}
$$

Follow the general steps below for each type of conversion.

#### Polar -> Cartesian
<procedure>
<step>Identify your values.</step>
<step>Use the necessary formulas for conversions.</step>
<step>Check to make sure the original and the converted set of points are in the same position.</step>
</procedure>

#### Cartesian -> Polar
<procedure>
<step>Identify your values.</step>
<step>Use the necessary formulas for conversions.</step>
<step>Do note that for this, you may get multiple answers.
Cross-compare, and figure out which one will make the most sense.</step>
</procedure>

### Complex Numbers?
Yes, this is obligatory.
For every new coordinate system, there's complex numbers to walk in its shadow.
Most of the time, they are in the form $z = a + bi$, or only $a + bi$ in most examples.

In the polar system, it's usually figured out with a conversion from Complex to Polar, which is the exact same as a 
Cartesian to Polar conversion.
However, most cite the form $a + bi \to_c (r\cos\theta) + i(r\sin\theta)$.
# 3.8: The Tangent Function

## Overview
Tangent has been glossed over for the past 7 subunits, and now it's finally here.

### Recap
In 3.2, we defined tangent in multiple ways, but here's the three that matter, all in reference to the unit circle:

$$
\begin{align*}
\tan(\theta) &= \frac{\sin(\theta)}{\cos(\theta)}\\
\tan(\theta) &= m \quad \text{in reference to} \quad f(x) = mx+b\\
\tan(\theta) &= \frac{y}{x}
\end{align*}
$$

### Limits & Rotation
Because of how tangent is calculated, every vertical line will result in an undefined value.
More specifically, it's represented in the form of a limit, especially when looking at a graph of $\tan(\theta)$.
Here's a graph now.

![A graph of the function tan(x)](3.8.tangent.png)

> $\tan(\theta)$ is always increasing across its periods.

> I'd assume that this is a common mistake to make.
Tangent's period is $\pi$, the other two are $2\pi$.
Keep that very much in mind.
{style="warning"}

The unit circle explains why it repeats; at $\dfrac{\pi}{2} \&\& \dfrac{3\pi}{2}$, the slope is directly upward, leading to an asymptote being present at every repetition of $\pi$.
The limit for the first asymptotes of the parent function are:
$$
\begin{align*}
\lim\limits_{\theta \to \frac{\pi}{2}^-} \tan(\theta) &= \infty \\
\&\&\\
\lim\limits_{\theta \to \frac{\pi}{2}^+} \tan(\theta) &= -\infty
\end{align*}
$$

Not to mention, looking at the graph, every point of inflection by default lands on the x-axis.

### Transformations
The general form of tangent comes out to be $a\tan(b(\theta +c))+d$, which should look familiar.
It's the same general form as sine and cosine, with four major differences.

1. The period begins at $\pi$, so the period is $\dfrac{\pi}{b}$.
2. Tangent does NOT have an amplitude, so $a$ instead is a vertical dilation.
3. $a$ is harder to find, with it usually requiring every other value + solving.
4. The graph does not have a typical "midline", but $d$ is now the line where the points of inflection lie.

#### Example Time

![i'm not telling you what function this is](3.8.tangenttransformed.png)

Right out of the gate, there are some things to do.

$d = 0$ because all of the points of inflection are on the midline, so that's fine.

The period is 2, which means $\dfrac{\pi}{b} = 2 \to \dfrac{\pi}{2} = b$.

The function starts at $x = 1$, which means the minimum phase shift is $c = -1$.

The fun begins when trying to find $a$.
Picking an x value is important, so we must do 1.5 because 2 won't work.
The following is how to solve for $a$:

$$
\begin {align}
3 &= a\tan(\frac{\pi}{2}(1.5 - 1))\\
3 &= a\tan(0.5\frac{\pi}{2})\\
3 &= a\tan(\frac{\pi}{4})\\
3 &= a \quad \text{because} \quad \tan(\frac{\pi}{4}) = 1
\end{align}
$$

Finally, we have the result.
a is 3, b is $\dfrac{\pi}{2}$, c is -1, and d is 0, resulting in the function of $f(\theta) = 3\tan(\dfrac{\pi}{2}(\theta -1))$.

### Representing Asymptotes
The period of a tangent function is usually represented by the first positive asymptote, added or subtracted from any amount of the period.
This is represented in equation form as $x = \dfrac{\pi}{b} \div 2 \; + \dfrac{\pi}{b}k \quad s.t. \quad  k \in \mathbb{Z}$.

As an example, take base $\tan(\theta)$.
The equation for its asymptotes is $x = \dfrac{\pi}{2} + \pi k \quad s.t. \quad k \in \mathbb{Z}$.
If any question asks for the equation of the asymptotes, and gives a $b$ value, you should be able to determine based of that alone, if it's multiple choice.

#### for fun {collapsible=true}
thanks for being here

yeah here's the general form for the limits of asymptotes
have fun

$$
\lim\limits_{\theta \to ([\{\frac{\pi}{b} \div 2\} + c] + \frac{\pi}{b}k)^\pm}a\tan(b(\theta +c))+d = \begin{cases}
\mp \infty \; s.t. \; a > 0\\
\pm \infty \; s.t. \; a < 0
\end{cases}
$$
---
switcher-label: Subunit
---
# 1.2-4: Basics of Limits

This page is split into 3 sub-units:

* 1.2: Defining Limits and Using Limit Notation
* 1.3: Estimating Limit Values from Graphs
* 1.4: Estimating Limit Values from Tables

<!-- 1.2 -->
## 1.2 Overview {switcher-key="1.2"}
While Limits should be a review, they are a critical foundation of AP Calculus.
Even if they're a review, I won't skip the concepts.
And that goes for just about everything in this course.

### Terms
Limit
: Where an output approaches as a respective input gets closer and closer to a specific point.
: Most often used with undefined / indeterminate values.

### Explaining Limits
Take a very simple graph, something like $f(x) = 2x$.
Now let's say that $x = 5$ is undefined.
By that logic, $f(5)$ is undefined, but what if you get really close without being there?
That's a limit.

A limit can be of any number; the limit of $f(x)$ from the prior example at 2 is 4, even if it can reach there.
Limits don't always have to be of undefined values, but it's a commonality.

### Basic Limit Notation
There are four big parts to a proper limit.

1. The limit itself, or $\lim$
2. The subscript, or defining where the input of the function is approaching, such as $_{x \to 2}$
3. The function itself, such as $f(x)$
4. What the limit approaches, such as 4. Can have an equals sign, but is not explicitly required.

All together, that is $\lim\limits_{x \to 2} f(x) = 4$.

### Existence of Limits
Some limits don't exist.
If a two-sided limit is the same from both sides, then it exists.
Likewise, it does NOT exist if it isn't the same on both sides.

![A graph of a piecewise function.](APCBC-1.2.nonexist.png)

The limit $\lim\limits_{x \to 3} f(x)$ does not exist.

> When dealing with holes, the limit is to where it would be if it wasn't undefined.
I specify this, because some graphs have a dot above/below a hole, but that dot is NOT what the limit equals.
{style="note"}

### 1.2 Conclusion
Limits won't be going away, but this is just the beginning.

<!-- 1.3 -->
## 1.3 Overview {switcher-key="1.3"}
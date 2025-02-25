---
switcher-label: Subunit
---
# 3.9-12: Expanded Trigonometry

This section contains these following sub-units:

* 3.9: Inverse Trigonometric Functions
* 3.10: N/A
* 3.11: N/A
* 3.12: Equivalent Representations of Trigonometric Functions

<!-- 3.9 -->

## 3.9 Overview {switcher-key="3.9"}
This subunit covers all of the inverse trigonometric functions from the first three.

### Writing Inverses
Inverses are in two forms: arc and inverse.
They are interchangeable and represent the exact same thing.
Below is both of them.

$$
\sin(\theta) = \frac{y}{r} \to \arcsin(\frac{y}{r}) \; \| \; \sin^{-1}(\frac{y}{r})= \theta
$$

Even though both notations are interchangeable, it's still nearly always said as "arcsine", or whatever other trigonometric function you're using.
This differs from Geometry, where commonly it was just "inverse sine".

> In AP Calculus BC, it's common for it to still be interchangeable.
Thought I'd mention it.
Also, for the sake of the rest of this article, I will be exclusively using arc notation.
See the collapsible section as to why.
{style="note"}

#### why {collapsible=true}
okay, so, this is a messy part of LaTeX

for those unaware, LaTeX is how I need to write math because programming sucks (sarcasm)

for arcsine, i just do `$\arcsin(x)$` which becomes $\arcsin(x)$

for inverse i need to do `$\sin^{-1}(x)$` which feels WAY worse to type, and it becomes $\sin^{-1}(x)$

and both is usually `$\arcsin(x) \; \| \; \sin^{-1}(x)$` which i HATE and it's ugly

so that's why

enjoy your day :)

### How to form
If you caught it, in the writing part, I already put how to write the inverses.
Like with any other inverse function (see [2.8](2-8-Inverse-Functions.md)), you need to flip the x and the y variables.
Therefore, $\sin(\dfrac{\pi}{3}) = \dfrac{\sqrt{3}}{2}$ will turn into
$\arcsin(\dfrac{\sqrt{3}}{2}) = \dfrac{\pi}{3}$.

### The Uses and Delimiters
Inverse trig. is used to find angle measures, instead of finding points or slopes.


<!-- 3.10 -->
## 3.10 Overview {switcher-key="3.10"}

<!-- 3.11 -->
## 3.11 Overview {switcher-key="3.11"}

<!-- 3.12 -->
## 3.12 Overview {switcher-key="3.12"}
Now that we have sine, cosine, tangent, secant, cosecant, and cotangent, as well as all of their inverses and powers, we can finally do Trigonometric Identities.

Trigonometric identities are how trigonometric functions are related to eachother, and there are 3 parts to 3.12.

### Part 1: Basic Identities
Each trig function has simple relations, represented below in this convenient table.

| Simple                            | Expanded                          |
|-----------------------------------|-----------------------------------|
| $\sin x = \dfrac{1}{\csc x}$      | $\csc x = \dfrac{1}{\sin x}$      |
| $\cos x = \dfrac{1}{\sec x}$      | $\sec x = \dfrac{1}{\cos x}$      |
| $\tan x = \dfrac{1}{\cot x}$      | $\cot x = \dfrac{1}{\tan x}$      |
| $\tan x = \dfrac{\sin x}{\cos x}$ | $\cot x = \dfrac{\cos x}{\sin x}$ |

Quite often, questions will ask for a specific function to be converted into an equivalent form with only a single trig function.
I will write these conversions, as an example, $f(x) = \csc x \to_c \sin x$.

> On the AP Exam, the above example will read as
"Let $f(x) = \csc x$. Rewrite $f(x)$ as an expression involving $\sin x$ and no other trigonometric functions."
I cannot be bothered to write all of that, every single time.
{style="note"}

Making equivalent representations is important, and here's an example to show it.

Say you have a function, like $g(x) = (\csc x)(\sec x)$, but it would be significantly more useful in terms of $\sin x$ and $\cos x$.
Therefore, $g(x) = (\csc x)(\sec x) \to_c \sin x \; \&\& \; \cos x$.

$$
\begin{align*}
g(x) &= (\csc x)(\sec x) \\
&= (\frac{1}{\sin x})(\frac{1}{\cos x})
\end{align*}
$$

These first conversions are critical, as we're about to go into the even worse part of this, so have fun.
Do note that powers carry, so $\csc^2 x \to_c \dfrac{1}{\sin^2 x}$.

#### a few more {collapsible=true}
these aren't taught explicitly but they work

$$
\begin{align*}
\tan x &\to_c (\sin x)(\sec x) \\
\cot x &\to_c (\cos x)(\csc x) \\
(\pm anytrig)(\pm \frac{1}{anytrig}) &\to_c 1 \\
(\pm anytrig)(\mp \frac{1}{anytrig}) &\to_c -1
\end{align*}
$$

#### Solving Basic Identities
<procedure>
<step>

Convert all trigonometric functions to either $\sin$ or $\cos$, or some power / fractional variation of them.
</step>
<step>

Consider the question, and begin to run basic transforms into the requested function.
</step>
</procedure>


### Part 2: Pythagorean Identities
The first identity is very simple.
For a unit circle, $\sin^2\theta + \cos^2\theta = 1$.
In fact, this is the only identity you need to remember.
All other useful identities can be derived from this alone, but there are two more commonly listed.

$$
\begin{align*}
1 + \tan^2 x &= \sec^2 x \\
1 + \cot^2 x &= \csc^2 x
\end{align*}
$$

> The pythagorean identity allows for substitution.
More forms available in the [](Glossary.md) page.

#### Solving Basic w/ Trig. Identities
<procedure>
<step>

Convert all trigonometric functions to either $\sin$ or $\cos$, or some power / fractional variation of them.
</step>
<step>

Consider the question, and begin to run basic transforms into the requested function.
</step>
<step>

If needed, convert any squared functions into their possible counterparts using transformed Trigonometric Identities
</step>
</procedure>

### Part 3: Sum and Difference Identities
The Sum and Difference identities are by far the most memory-heavy.
Each of them have their own nuances, which can make them confusing.

Sine Double-Angle Identity
: $\sin(2\theta) = 2\sin\theta\cos\theta$
: This is by far the simplest one.

Cosine Double-Angle Identity
: $\begin{align*} \cos(2\theta) &= \cos^2\theta - \sin^2\theta \\ &= 1 - 2\sin^2\theta \\ &= 2\cos^2\theta - 1 \end{align*}$
: These extra forms utilize the Pythagorean Identity substitutions.

Sum & Difference Identity
: $\sin(\alpha \pm \beta) = \sin\alpha\cos\beta \pm \cos\alpha\sin\beta$
: $\cos(\alpha \pm \beta) = \cos\alpha\cos\beta \mp \sin\alpha\sin\beta$
: Note the differences between the two.
Yes, all differences are intentional.
: Also, the $\mp$. See [](Notation.md).
{type=medium}

#### Solving S, D, & DA Identities
Two parts. One, figure out which property is needed:

<procedure>
<step>

Consider the question. If it's asking for an equivalent form, look at the function it gives you and compare across these two guidelines: trig function and formation.
</step>
<step>

If needed, assign what $\alpha$ and $\beta$ are.
</step>
</procedure>

### SECRET PART 4: Laws {collapsible=true}
If we're talking about trigonometric relationships, I might as well share some extras that I doubt are taught in AP Precalculus.
These are extensions of the Pythagorean Theorem, and these are what are used for any triangle that is not a right triangle.
For each, assume that $a$, $b$, and $c$ are sides of any triangle, and $\alpha$, $\beta$, and $\gamma$ are opposite angles of the respective sides.

![A triangle.](Law_of_sines_(simple).svg)

By Mliu92 - Own work, CC BY-SA 4.0, [](https://commons.wikimedia.org/w/index.php?curid=108296103)

Law of Sines 
: $\dfrac{\sin\alpha}{a} = \dfrac{\sin\beta}{b} = \dfrac{\sin\gamma}{c}$
: Usually this involves a circumcircle, but that's a little too complex and not required for this course.
: The circumcircle formula is below.
: $\dfrac{a}{\sin\alpha} = \dfrac{b}{\sin\beta} = \dfrac{c}{\sin\gamma} = 2R$
: such that R is the radius of the circumcircle

Law of Cosines
: $\begin{align*} c^2 &= a^2 + b^2 - 2ab\cos\gamma \\ a^2 &= b^2 + c^2 - 2bc\cos\alpha \\ b^2 &= a^2 + c^2 - 2ac\cos\beta \end{align*}$

Law of Tangents
: $\dfrac{a - b}{a + b} = \dfrac{\tan\frac{1}{2}(\alpha - \beta)}{\tan\frac{1}{2}(\alpha + \beta)}$

Law of Cotangents
: $\dfrac{\cot\frac{1}{2}\alpha}{\frac{a+b+c}{2}-a} = \dfrac{\cot\frac{1}{2}\beta}{\frac{a+b+c}{2}-b} = \dfrac{\cot\frac{1}{2}\gamma}{\frac{a+b+c}{2}-c} = \dfrac{1}{r}$
: This revolves around an inscribed circle, where $r$ is the radius of the inscribed circle.
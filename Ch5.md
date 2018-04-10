Chapter 5
================

1-a)
====

Plugging in to the cdf of rayleigh F, F(3)-F(1) should be the answer

``` r
(1-exp(-9/2))-(1-exp(-1/2))
```

    ## [1] 0.5954217

1-b)
====

If F(x)=1/j, whats x?

or *F*<sup>−1</sup>(1/*j*)=?

q1=sqrt(-2\*log(1-1/4))

``` r
sqrt(-2*log(1-1/4))
```

    ## [1] 0.7585276

q2=sqrt(-2\*log(1-2/4))

``` r
sqrt(-2*log(1-2/4))
```

    ## [1] 1.17741

q3=sqrt(-2\*log(1-3/4))

``` r
sqrt(-2*log(1-3/4))
```

    ## [1] 1.665109

2-a)
====

for x in (0,0.25) f(x)=2 this gives 1/2 probability mass

for x in (0.25,1) f(x)=2/3 this also gives 1/2 probability mass since (3/4)\*(2/3)=0.5

2-b)
====

if its bigger than 1 it will make integral&gt;1 which is not allowed

3-a)
====

To be a valid pdf it must be &gt;0 and integrate to 1

since f and F are &gt;0 g is also &gt;0 since *F*<sup>2</sup> is the antiderivative of *F**f*

*F*<sup>2</sup>|<sub>−∞</sub><sup>∞</sup>=1-0=1

3-b)
====

h is positive since f(-x) and f(x) are positive.

It integrates to 1 because for the second term of the sum the integral is 1/2.

And for the first term if we substitute -x=u then -dx=du we get the same integral with limits reversed.

u going from positive infinity to negative. The answer comes out negative. But we have a minus sign from -dx

So its 1/2

4-a)
====

P(X&lt;=x|X&gt;a)= P(a<X<=x)/P(X>a)

P(a<X<=x)=F(x)-F(a)
P(X>a)=1-F(a)

4-b)
====

derivative of above is f(x)/(1-F(a))

4-c)
====

1-F(a) is &gt;0 and f is &gt;0, so its &gt;0 it integrates to 1 because the the limit of integration is from a to infinity which gives 1-F(a) which cancels.

5-a)
====

*A* = *π**R*<sup>2</sup>

*E*(*A*)=*π**E*(*R*<sup>2</sup>)=*π*(1/3)

*V**a**r*(*A*)=*V**a**r*(*π**R*<sup>2</sup>)=*π*<sup>2</sup>*V**a**r*(*R*<sup>2</sup>)

*V**a**r*(*R*<sup>2</sup>)=*E*(*R*<sup>4</sup>)−*E*<sup>2</sup>(*R*<sup>2</sup>)

*E*(*R*<sup>4</sup>) is integral from 0 to 1 of *R*<sup>4</sup> which is 1/5

and *E*(*R*<sup>2</sup>)<sup>2</sup> = (1/3)<sup>2</sup>

so the answer is 1/5-1/9

5-b)
====

$P(\\pi R^2 \\le a)=P(R \\le \\sqrt{a/\\pi})=\\sqrt{a/\\pi}$

for 0 &lt; *a* &lt; *π*, because R is Unif(0,1)

for *π* ≤ *a* its 1

for *a* ≤ 0 its 0

Differentiating wrt to a gives the pdf.

6-a)
====

For $X \\sim Unif(0,1), \\mu=1/2, \\sigma=\\frac{1}{\\sqrt(12)}$

So

*P*(*μ* − *σ* &lt; *X* &lt; *μ* + *σ*) = length of that interval

For 1 std =&gt; 2/sqrt(12)

For 2 std =&gt; 4/sqrt(12)

For 3 std =&gt; 6/sqrt(12)

6-b)
====

For *X* ∼ *E**x**p**o*(1)

*E*(*X*)=1

*σ* = 1

*P*(*μ* − *σ* &lt; *X* &lt; *μ* + *σ*)

For 1 std *P*(0 &lt; *X* &lt; 2)

plugging in to its cdf, 1 − *e*<sup>−2</sup>

For 2 std *P*(0 &lt; *X* &lt; 3) its 1 − *e*<sup>−3</sup>

For 3 std *P*(0 &lt; *X* &lt; 4) its 1 − *e*<sup>−4</sup>

6-c)
====

For *X* ∼ *E**x**p**o*(1/2)

*E*(*X*)=2

*σ* = 2

For 1 std *P*(0 &lt; *X* &lt; 4) its 1 − *e*<sup>−2</sup>

For 2 std *P*(0 &lt; *X* &lt; 6) its 1 − *e*<sup>−3</sup>

For 3 std *P*(0 &lt; *X* &lt; 8) its 1 − *e*<sup>−4</sup>

Same as above, since lambdas cancel.

This is true for any expo.

7-a)
====

F is increasing, right cont and converges to 0 and 1 for -infinity, +infinity (ie 0 and 1)

its pdf is

<https://www.wolframalpha.com/input/?i=derivative+(2%2Fpi)*sin%5E-1(sqrt(x)>)

for 0 &lt; *x* &lt; 1

7-b)
====

its positive and integrates to 1

8-a)
====

<https://www.wolframalpha.com/input/?i=integral+12x%5E2(1-x)>

for 0 &lt; *x* &lt; 1

8-b)
====

<https://www.wolframalpha.com/input/?i=integral+12x%5E2(1-x)+from+0+to+1%2F2>

8-c)
====

Mean

<https://www.wolframalpha.com/input/?i=integral+12x%5E3(1-x)+from+0+to+1>

which is 0.6

E(X^2)

<https://www.wolframalpha.com/input/?i=integral+12x%5E4(1-x)+from+0+to+1>

which is 0.4

So 0.4-(0.6)^2=0.04

9)
==

1st quadrant in

<https://www.wolframalpha.com/input/?i=integral+1%2F(pi*(1%2Bx%5E2)>)

10-a)
=====

1/8 is the pdf

and (2-0)+(7-3)= 2+4=6 answer is 6/8

10-b)
=====

P(U&lt;=x | U is in (3,7))

is

P(U&lt;=x,3<U<7)/P(3<U<7)=((x-3)/8)/(4/8) = (x-3)/4


#11-a)

If U~(a,b)

E(U)=(a+b)/2 => 0 Var(U)=((b-a)^2)/2 =&gt; ((1--1)^2)/2=2

*E*(*U*<sup>4</sup>)=1/2∫<sub>−1</sub><sup>1</sup>*U*<sup>4</sup> = 1/10(1 − −1)=1/5

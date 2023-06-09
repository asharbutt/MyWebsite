---
layout: default
title: Independence
parent: Basics
grand_parent: Probability Theory
mathjax: true
permalink: /docs/Probability Theory/Basics/Independence/
nav_order: 4
---
## Independence
When a random variable X is measurable with respect to some $$\sigma$$-algebra G, we say that X is G-measurable, and the information contained within G is sufficient to be able to estimate X. The other case is when the information in G is not sufficient to determine the value of X - we say X is independent of G. 

A formal definition in terms of random variables is given through:
<div class="code-example" markdown="1">
  Let ($$\Omega, \digamma$$, P) be a probability space. Two random variables X and Y in $$\digamma$$ are said to be independent if:

  P(X$$\cap$$Y) =  P(X)P(Y)

  In simpler terms, knowing the outcome of one random variable will not affect the outcome of the other random variable. Furthermore, independence of random variables also implies independence of functions of those random variables i.e if X and Y are independent, then so are Sin(X) and $$e^Y$$
</div>

When two random variables are independent, then:

$$Cov(X,Y) = 0 and \rho = 0$$

However, the reverse is not true; the two values being 0 does not imply independence. 

Thinking in terms of the $$\sigma-algebras$$ two random variables generate - if two random variables are independent, then the $$\sigma algebras$$ generated by them, $$\sigma(X) and \sigma(Y)$$ are also independent, meaning the information in both subsets is not enough to determine the information in the other. 

---
layout: post
category: MathConcepts
---

A [**stochastic differential equation** (**SDE**)](https://en.wikipedia.org/wiki/Stochastic_differential_equation) is a [differential equation](https://en.wikipedia.org/wiki/Differential_equation) in which one or more of the terms is a [stochastic process](https://en.wikipedia.org/wiki/Stochastic_process), resulting in a solution which is also a stochastic process. 

SDEs can be viewed as a generalization of the [dynamical systems theory](https://en.wikipedia.org/wiki/Dynamical_systems_theory) to models with noise. 

There are standard techniques for transforming higher-order equations into several coupled first-order equations by introducing new unknowns. Therefore, the following is the most general class of SDEs:
$$
\begin{align}
\frac{d x(t)}{d t}=F(x(t))+\sum_{\alpha=1}^{n} g_{\alpha}(x(t)) \xi^{\alpha}(t)
\end{align}
$$
where $$ x \in X $$ is the position in the system in its phase (or state) space, $$ X $$, assumed to be a differentiable manifold, the $$ F \in T X $$ is a flow vector field representing deterministic law of evolution, and $$ g_{\alpha} \in T X $$ is a set of vector fields that define the coupling of the system to Gaussian white noise, $$ \xi^{\alpha} $$ 


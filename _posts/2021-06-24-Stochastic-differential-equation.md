---
layout: post
category: MathConcepts
---

A [**stochastic differential equation** (**SDE**)](https://en.wikipedia.org/wiki/Stochastic_differential_equation) is a [differential equation](https://en.wikipedia.org/wiki/Differential_equation) in which one or more of the terms is a [stochastic process](https://en.wikipedia.org/wiki/Stochastic_process), resulting in a solution which is also a stochastic process. 

SDEs can be viewed as a generalization of the [dynamical systems theory](https://en.wikipedia.org/wiki/Dynamical_systems_theory) to models with noise. 

There are standard techniques for transforming higher-order equations into several coupled first-order equations by introducing new unknowns. Therefore, the following is the most general class of SDEs:
$$
\frac{d x(t)}{d t}=F(x(t))+\sum_{\alpha=1}^{n} g_{\alpha}(x(t)) \xi^{\alpha}(t)
$$
where ![x\in X](https://wikimedia.org/api/rest_v1/media/math/render/svg/3e580967f68f36743e894aa7944f032dda6ea01d) is the position in the system in its phase (or state) space, ![X](https://wikimedia.org/api/rest_v1/media/math/render/svg/68baa052181f707c662844a465bfeeb135e82bab), assumed to be a differentiable manifold, the ![{\displaystyle F\in TX}](https://wikimedia.org/api/rest_v1/media/math/render/svg/6c8359090df5abfb85eb57e55d9af2f377fa7185) is a flow vector field representing deterministic law of evolution, and ![{\displaystyle g_{\alpha }\in TX}](https://wikimedia.org/api/rest_v1/media/math/render/svg/022cf3860f5ecf798ad774f611e8f3f3a44ea7cb) is a set of vector fields that define the coupling of the system to Gaussian white noise, ![{\displaystyle \xi ^{\alpha }}](https://wikimedia.org/api/rest_v1/media/math/render/svg/476f5f4c77556e4eb428fc0e45e6b23c411a76ad). 


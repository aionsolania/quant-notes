## Probability Space

Let $(\Omega, \mathcal{F}, \mathbb{P})$ be a probability space,
where $\Omega$ is the sample space, $\mathcal{F}$ is a sigma-algebra
on $\Omega$, and $\mathbb{P}$ is a probability measure.

All random variables are assumed measurable with respect to
$\mathcal{F}$.

---

## Random Variables

A random variable $X$ is a measurable function
$X : \Omega \rightarrow \mathbb{R}$.

Unless stated otherwise, random variables are assumed to
admit finite first and second moments.

---

## Expectation

The expectation of a random variable $X$ is defined as

$$
\mathbb{E}[X] = \int_{\Omega} X(\omega)\, d\mathbb{P}(\omega)
$$

whenever the integral exists.

---

## Independence

Two random variables $X$ and $Y$ are independent if their
generated sigma-algebras are independent under $\mathbb{P}$.

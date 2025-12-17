## Vector Spaces

Let $V$ be a vector space over a field $\mathbb{F}$.
All vector spaces are assumed finite-dimensional unless
explicitly stated otherwise.

---

## Linear Maps

A linear map $T : V \rightarrow W$ satisfies

$$
T(\alpha x + \beta y) = \alpha T(x) + \beta T(y)
$$

for all $x, y \in V$ and scalars $\alpha, \beta \in \mathbb{F}$.

---

## Inner Product Spaces

An inner product on $V$ is a map
$\langle \cdot, \cdot \rangle : V \times V \rightarrow \mathbb{F}$
satisfying linearity, symmetry, and positive-definiteness.

The induced norm is defined as

$$
\|x\| = \sqrt{\langle x, x \rangle}.
$$

---

## Conditioning

The conditioning of a linear operator governs the sensitivity
of solutions to perturbations in input data.

Poor conditioning amplifies numerical error.


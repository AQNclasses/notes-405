# Induction Review

Steps in inductive proof:

1. Prove base case
2. Assume that what you are trying to prove for all $n$ is true for (all or some) $k < n$.

Let $S(n)$ be a logical statement, indexed by an integer $n$.

If $S(0)$ holds, and $S(k) \to S(k+1)$, then $S(n)$ is true for all integers
$n$.

Example to try on your own:

$$
\sum_{i=1}^n i = \frac{n(n+1)}{2}
$$

# Probability

## Permutations

*Permutations* are a measure of the total number of possible arrangements (subsets) in a collecction of items (set) where the **order does matter**. The phrase **order does matter** in a probabilistic context simply means that different arrangements of the same values in a given subset are each counted as an independent subset. For example, if given the set {A, B, C}, and we are asked to determine how many possible permutations we could create by random selecting two values, where **order does matter**, we would get the following *permutations*:

$$
\begin{equation}
    \text{(A, B), (B, A), (B, C), (C, B), (A, C), (C, A)}
\end{equation}
$$

When calculating *permutations*, different arrangements (ordering) of the same values (i.e., outcomes) are each counted as individual subsets because **order does matter**. *Permutations* are mathematically defined as follows:

$$
\begin{equation}
    P(n,k) = \dfrac{n!}{(n-k)!}
\end{equation}
$$

where,

$$
\begin{align}
    n &= \text{the total number of items of the set} \\
    k &= \text{the number of items in each subset}
\end{align}
$$

In the formula above (i.e., P(n,k)), it would be the same as saying *if given `n` items, how many ways could you select `k` items, where the order is important*? It is also common to reference the formula as $nPk$, which is often simplified verbally to *permutations of n given k*. In summary, *permutations* are a measure of the number of combinations of subsets given a set of values where **order does matter** (i.e., different arrangements (i.e., ordering) of the same values are each counted as independent subsets).

## Combinations

*Combinations* are a meaasure of the total number of possible arrangements (subsets) in a collection of items (set) where the **order does not matter**. The phrase **order does not matter** in a probabilistic context simply means that different arrangements of the same values in a given subset **are not** counted as independent subsets. For example, if given the same set {A, B, C} that we used in the above example of *permutations*, and we were asked to determine how many possible combinations we could create by randomly selecting two values, where **order does not matter**, we would get the following:

$$
\begin{align}
    \text{(A, B), (B, C), (C, A)}
\end{align}
$$

When calculating *combinations*, different arrangements (ordering) of the same values (i.e., outcomes) are **combined** and counted as a singular set because **order does not matter**. *Combinations* are mathematically defined as follows:

$$
\begin{equation}
    C(n,k) = \dfrac{n!}{k!(n-k)!}
\end{equation}
$$

where,

$$
\begin{align}
    n &= \text{the total number of items of the set} \\
    k &= \text{the number of items in each subset}
\end{align}
$$

In the formula above (i.e., C(n,k)), it would be the same as saying *if given `n` items, how many ways could you select `k` items, where the order is not important*? It is also common to reference the formula as $nCk$, which is often simplified verbally to *combinations of n given k*. In summary, if you compare the outcomes of these *combinations* to the outcomes of the *permutations* in the above section, you can see that in combinations ${A, B}$ and ${B, A}$, ${B, C}$ and ${C, B}$, and ${C, A}$ and ${A, C}$ are simply different arrangements of the same subsets of values. Because **order does not matter** when calculating *combinations*, these subsets containing the exact same values with different arrangments (ordering) are redundant, and therefore counted as a singular subset.

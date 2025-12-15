We use $\mathbb{Z} :=\{..., -3, -2, -1, 0, 1, 2, 3, ...\}$ for **integers**.
We use $\mathbb{N} := \{1, 2, 3, ... \}$ for **natural numbers**.
We use $\mathbb{N}_0 := \{0, 1, 2, ...\}$ for **non-negative integers**.
We use $\mathbb{Z} \setminus \mathbb{N}_0 := \{-1, -2, -3, ...\}$ for **negative integers**.
# Remark 1.1 - Axiom of induction
Let $K \subseteq \mathbb{N}_{0}$ such that
1. $0 \in K$ and  ^c72b60
2. if $k \in K$, then $k + 1 \in K$. ^2cca05

Then $K = \mathbb{N}_0$. ^febc05
# Theorem 1.2 - Principle of Induction
Let $n_0 \in \mathbb{Z}$ and let $S \subseteq \mathbb{Z}$ such that
1. $n_0 \in S$ and  ^539fba
2. if $n \in S$ for some integer $n >= n_0$, then $n + 1 \in S$. ^522fa6

Then $n \in S, \forall n \ge n_0$.

> [!important] Proof
> Let $K := \{ k \in \mathbb{N}_0 : n_0 + k \in S\} \subseteq \mathbb{N}$.
> Then $0 \in K$, by [[^539fba|1.2.1]].
> Next let $k \in K$. Then $n_0 + k \in S$, and so $n_0+k+1 \in S$ by [[#^522fa6|1.2.2]], that is $k+1 \in K$.
> Hence $K$ satisfies [[#^c72b60|1.1.1]] and [[#^2cca05|1.1.2]] of the [[I. Induction#Remark 1.1 - Axiom of induction|Axiom of Induction]]. Thus $K = \mathbb{N}_0$. 
> Therefore $n_0 + k \in S, \forall k \in \mathbb{N}_0$ or equivalently $n \in S, \forall n \ge n_0$.
# Remark 1.3
We call 
1. the **Base Case** and
2. the **Induction Step**

where the assumption is that $n \in S$ for some $n \ge n_0$ is called **Induction Hypothesis**.
# Example 1.4
## (1) 
We claim that $$ \sum_{i=1}^n i = \frac{n(n+1)}{2}, \forall n \in \mathbb{Z}$$
Let $S$ be all those integers $n \ge 1$ for which the statement holds. As the base case we show that $1 \in S$.
Let $n = 1$. Then $\sum_{i=1}^1 i = \frac{1(1+1)}{2} = 1$.
Thus $1 \in S$.
As the induction hypothesis we assume $n \in S$ for some $n \ge 1$. As the induction step we wish to know that $n + 1 \in S$, that is 
$$ 
\sum_{i=1}^n i = \frac{(n+1)(n+2)}{2}

\sum_{i=1}^n i = \frac{(n+1)(n+2)}{2}
$$

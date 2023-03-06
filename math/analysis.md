---
description: This is Notes for MATH 522
---

# Analysis Notes

## Prelimenary

**Definiton (Open set):** Let $$X$$ be a metric space and $$U \subset X$$. A point $$x \in U$$ is called interior in $$U$$ if there exists $$r>0$$ such that $$B(x, r) \subset U$$. The set $$U \subset X$$ is called open if every point $$x \in U$$ is interior.

**Definition (Closed set):** A set $$A \subset X$$ is called closed if its complement $$A^{\complement}=X \backslash A$$ is open. If $$A \subset X$$ is an arbitrary set, then $$\bar{A}$$ denotes the intersection of all closed sets containing $$A$$.

**Definition (Accumulation point):** Let $$A \subset X$$. A point $$x \in X$$ is called an accumulation point of $$A$$ if for every $$r>0$$, there exists $$y \in B_r(x) \cap A$$ with $$y \neq x$$.

**Lemma :** Let $$X$$ be a metric space and $$A \subset X$$. Then $$\bar{A}$$ is equal to the union of $$A$$ and the set of accumulation points of $$A$$.

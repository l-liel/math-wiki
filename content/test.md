---
aliases:
  - IVT
  - Bolzano's Theorem
title: Test Page
---
# Intermediate Value Theorem# Fundamental Theorem of Calculus

> [!abstract] Theorem
> Let $f$ be a continuous real-valued function defined on a closed interval $[a, b]$. If $F$ is defined for all $x \in [a, b]$ by:
> $$F(x) = \int_{a}^{x} f(t) \, dt$$
> then $F$ is continuous on $[a, b]$ and differentiable on $(a, b)$, and $F'(x) = f(x)$.

Related: [[Definition: Continuous Function]], [[Lemma: Mean Value Theorem]]

> [!abstract] Theorem (Heine-Borel Theorem)
> A subset $K \subseteq \mathbb{R}^n$ is closed and bounded if and only if it is compact.

> [!info] Definition (Open Cover)
> A collection of open sets $\{U_\alpha\}_{\alpha \in A}$ is an **open cover** of $K$ if $K \subseteq \bigcup_{\alpha \in A} U_\alpha$.

> [!proof] Proof (Forward Direction)
> Assume $K$ is compact. Consider the open cover $\{B(x, 1)\}_{x \in K}$...
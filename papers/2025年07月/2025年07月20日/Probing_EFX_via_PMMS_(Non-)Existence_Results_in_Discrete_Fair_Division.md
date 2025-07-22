# 通过 PMMS 探查 EFX：离散公平分配中的非存在性结果

发布时间：2025年07月20日

`其他` `资源分配` `公平分配`

> Probing EFX via PMMS: (Non-)Existence Results in Discrete Fair Division

# 摘要

> 本文研究了不可分割物品的公平分配问题，聚焦于EFX问题及其严格更强的变体PMMS问题。我们发现，在一个包含三个代理的实例中，当两个代理具有单调估值，另一个代理具有加性估值时，尽管已知EFX分配存在，但PMMS分配并不存在，这表明了EFX与PMMS之间的明确区分。我们进一步证明了EFX和PMMS分配在三个重要特例中的存在性：对于个性化二值估值，当$a_i$可被$b_i$整除时，PMMS分配存在；对于二值MMS可行估值，PMMS分配存在且无需假设估值单调性，因此适用于家务和混合资源分配。此外，我们还证明了在对需求估值的设置下，PMMS分配同样存在。我们的研究不仅具有理论意义，还提供了多项式时间算法以支持这些存在性结果，具有重要的实践价值。

> We study the fair division of indivisible items and provide new insights into the EFX problem, which is widely regarded as the central open question in fair division, and the PMMS problem, a strictly stronger variant of EFX. Our first result constructs a three-agent instance with two monotone valuations and one additive valuation in which no PMMS allocation exists. Since EFX allocations are known to exist under these assumptions, this establishes a formal separation between EFX and PMMS.
  We prove existence of fair allocations for three important special cases. We show that EFX allocations exist for personalized bivalued valuations, where for each agent $i$ there exist values $a_i > b_i$ such that agent $i$ assigns value $v_i(\{g\}) \in \{a_i, b_i\}$ to each good $g$. We establish an analogous existence result for PMMS allocations when $a_i$ is divisible by $b_i$. We also prove that PMMS allocations exist for binary-valued MMS-feasible valuations, where each bundle $S$ has value $v_i(S) \in \{0, 1\}$. Notably, this result holds even without assuming monotonicity of valuations and thus applies to the fair division of chores and mixed manna. Finally, we study a class of valuations called pair-demand valuations, which extend the well-studied unit-demand valuations to the case where each agent derives value from at most two items, and we show that PMMS allocations exist in this setting. Our proofs are constructive, and we provide polynomial-time algorithms for all three existence results.

[Arxiv](https://arxiv.org/abs/2507.14957)
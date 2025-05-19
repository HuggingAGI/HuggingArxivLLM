# MPS-Prover: 引领逐步定理证明新高度，基于多视角搜索与数据整理

发布时间：2025年05月16日

`LLM应用

理由：这篇论文主要探讨了如何将大型语言模型（LLMs）应用于自动定理证明（ATP）领域，提出了改进现有模型的策略和机制。虽然涉及模型的优化和创新，但其核心在于将LLMs应用到特定任务中，属于应用层面的研究。因此，归类为LLM应用。` `人工智能` `形式逻辑`

> MPS-Prover: Advancing Stepwise Theorem Proving by Multi-Perspective Search and Data Curation

# 摘要

> 形式语言中的自动定理证明（ATP）一直是人工智能领域的一大难题，它需要严谨的逻辑推理和在广袤的搜索空间中探索。虽然大型语言模型（LLMs）表现亮眼，但现有逐步证明器常因搜索引导偏差导致效率低下和证明策略欠佳。本文推出Multi-Perspective Search Prover（MPS-Prover），一款突破这些局限的新型逐步ATP系统。

MPS-Prover两大创新亮点：
1. 高效后训练数据整理策略：去除约40%冗余训练数据，性能不受影响
2. 多视角树搜索机制：融合学习型批评模型与精巧启发式规则，实现策略多样化，避免低效困境，增强搜索稳健性

实证研究表明，MPS-Prover在miniF2F和ProofNet等高难度基准测试中表现超越70亿参数模型，证明生成更短、更丰富。这不仅彰显了其高效性，更为基于LLM的形式推理能力开辟了新境界，为开发更强大的定理证明器提供了坚实框架和全面分析。

> Automated Theorem Proving (ATP) in formal languages remains a formidable challenge in AI, demanding rigorous logical deduction and navigating vast search spaces. While large language models (LLMs) have shown promising performance, existing stepwise provers often suffer from biased search guidance, leading to inefficiencies and suboptimal proof strategies. This paper introduces the Multi-Perspective Search Prover (MPS-Prover), a novel stepwise ATP system designed to overcome these limitations. MPS-Prover incorporates two key innovations: a highly effective post-training data curation strategy that prunes approximately 40% of redundant training data without sacrificing performance, and a multi-perspective tree search mechanism. This search integrates a learned critic model with strategically designed heuristic rules to diversify tactic selection, prevent getting trapped in unproductive states, and enhance search robustness. Extensive evaluations demonstrate that MPS-Prover achieves state-of-the-art performance on multiple challenging benchmarks, including miniF2F and ProofNet, outperforming prior 7B parameter models. Furthermore, our analyses reveal that MPS-Prover generates significantly shorter and more diverse proofs compared to existing stepwise and whole-proof methods, highlighting its efficiency and efficacy. Our work advances the capabilities of LLM-based formal reasoning and offers a robust framework and a comprehensive analysis for developing more powerful theorem provers.

[Arxiv](https://arxiv.org/abs/2505.10962)
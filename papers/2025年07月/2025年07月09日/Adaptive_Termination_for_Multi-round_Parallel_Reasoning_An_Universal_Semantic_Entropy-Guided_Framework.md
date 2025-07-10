# 面向多轮并行推理的自适应终止：通用语义熵引导框架

发布时间：2025年07月09日

`LLM理论` `人工智能` `通用人工智能`

> Adaptive Termination for Multi-round Parallel Reasoning: An Universal Semantic Entropy-Guided Framework

# 摘要

> 近期，大型语言模型（LLMs）的突破加速了人工通用智能的进程，其中推理扩展（inference-time scaling）成为关键的技术方向。当前，推理扩展主要分为两类：串行推理通过迭代扩展思维链逐步生成结果，而并行推理则在同一时间生成多个解决方案。然而，这两种方法各有局限：串行扩展常依赖于任意设置的token预算来终止推理，导致效率低下或过早截断；并行扩展则面临各分支缺乏协调的问题，且需侵入式微调才能有效运行。为应对这些挑战，我们提出了一种灵活的测试时协作推理框架，旨在融合串行和并行推理的互补优势。实现这一目标的关键在于开发一个高效且精准的内在质量度量，用于评估协作推理过程中模型的响应，从而实现推理过程的动态控制和早期终止。为此，我们引入了语义熵（SE），它通过量化并行模型响应的语义多样性，成为衡量推理质量的可靠指标，因其与准确性的强负相关关系而尤为突出。

> Recent advances in large language models (LLMs) have accelerated progress toward artificial general intelligence, with inference-time scaling emerging as a key technique. Contemporary approaches leverage either sequential reasoning (iteratively extending chains of thought) or parallel reasoning (generating multiple solutions simultaneously) to scale inference. However, both paradigms face fundamental limitations: sequential scaling typically relies on arbitrary token budgets for termination, leading to inefficiency or premature cutoff; while parallel scaling often lacks coordination among parallel branches and requires intrusive fine-tuning to perform effectively. In light of these challenges, we aim to design a flexible test-time collaborative inference framework that exploits the complementary strengths of both sequential and parallel reasoning paradigms. Towards this goal, the core challenge lies in developing an efficient and accurate intrinsic quality metric to assess model responses during collaborative inference, enabling dynamic control and early termination of the reasoning trace. To address this challenge, we introduce semantic entropy (SE), which quantifies the semantic diversity of parallel model responses and serves as a robust indicator of reasoning quality due to its strong negative correlation with accuracy...

[Arxiv](https://arxiv.org/abs/2507.06829)
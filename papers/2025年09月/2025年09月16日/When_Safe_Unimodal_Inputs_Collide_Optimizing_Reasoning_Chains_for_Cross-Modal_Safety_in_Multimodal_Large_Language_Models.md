# 当安全单模态输入冲突时：优化多模态大型语言模型跨模态安全的推理链

发布时间：2025年09月16日

`LLM应用` `基础理论`

> When Safe Unimodal Inputs Collide: Optimizing Reasoning Chains for Cross-Modal Safety in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）存在隐式推理风险：无害的单模态输入可能协同组合成危险的多模态数据，进而生成有害输出。我们认为，这一脆弱性源于MLLMs难以通过长链推理维持安全对齐。为应对这一问题，我们构建了“安全语义但不安全解释”（SSUI）数据集——这是首个针对此类跨模态挑战、专门设计可解释推理路径的数据集。同时，基于SSUI数据集，我们设计了一种新颖的训练框架——安全感知推理路径优化（SRPO），旨在将MLLM的内部推理过程与人类安全价值观对齐。实验结果显示，经SRPO训练的模型在关键安全基准（包括我们提出的推理路径基准RSBench）上均达到了最先进水平，性能显著优于开源及顶级商业MLLMs。

> Multimodal Large Language Models (MLLMs) are susceptible to the implicit reasoning risk, wherein innocuous unimodal inputs synergistically assemble into risky multimodal data that produce harmful outputs. We attribute this vulnerability to the difficulty of MLLMs maintaining safety alignment through long-chain reasoning. To address this issue, we introduce Safe-Semantics-but-Unsafe-Interpretation (SSUI), the first dataset featuring interpretable reasoning paths tailored for such a cross-modal challenge. A novel training framework, Safety-aware Reasoning Path Optimization (SRPO), is also designed based on the SSUI dataset to align the MLLM's internal reasoning process with human safety values. Experimental results show that our SRPO-trained models achieve state-of-the-art results on key safety benchmarks, including the proposed Reasoning Path Benchmark (RSBench), significantly outperforming both open-source and top-tier commercial MLLMs.

[Arxiv](https://arxiv.org/abs/2509.12060)
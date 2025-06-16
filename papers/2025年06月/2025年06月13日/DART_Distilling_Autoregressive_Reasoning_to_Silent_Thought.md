# DART：自回归推理蒸馏为无声思考的方法

发布时间：2025年06月13日

`LLM理论` `人工智能` `大型语言模型`

> DART: Distilling Autoregressive Reasoning to Silent Thought

# 摘要

> 链式思维推理（Chain-of-Thought, CoT）极大地推动了大型语言模型（LLMs）在处理复杂任务方面的能力提升。然而，其自回归推理特性带来了显著的计算开销，限制了其在对延迟敏感的应用场景中的应用。为了解决这一难题，我们提出了	extbf{DART}（	extbf{D}istilling 	extbf{A}utoregressive 	extbf{R}easoning to Silent 	extbf{T}hought），一个创新的自蒸馏框架，能够将LLMs的自回归推理转换为非自回归的静默思维（ST），从而实现推理效率的突破。具体而言，DART框架设计了两条独特的训练路径：一条用于传统的链式推理（CoT），另一条则通过少量静默思维令牌（ST）直接生成答案。其中，ST路径配备了轻量级的推理演化模块（REM），能够使其隐藏状态与CoT路径实现高效对齐，从而确保静默思维令牌能够演变为富含信息的语义嵌入。在推理阶段，系统仅激活ST路径，通过动态演化的静默思维令牌直接输出最终答案，显著降低了计算开销。通过广泛的实验验证，DART不仅能够达到现有基线的推理性能，更实现了显著的效率提升，为高效推理提供了一个极具潜力的解决方案。

> Chain-of-Thought (CoT) reasoning has significantly advanced Large Language Models (LLMs) in solving complex tasks. However, its autoregressive paradigm leads to significant computational overhead, hindering its deployment in latency-sensitive applications. To address this, we propose \textbf{DART} (\textbf{D}istilling \textbf{A}utoregressive \textbf{R}easoning to Silent \textbf{T}hought), a self-distillation framework that enables LLMs to replace autoregressive CoT with non-autoregressive Silent Thought (ST). Specifically, DART introduces two training pathways: the CoT pathway for traditional reasoning and the ST pathway for generating answers directly from a few ST tokens. The ST pathway utilizes a lightweight Reasoning Evolvement Module (REM) to align its hidden states with the CoT pathway, enabling the ST tokens to evolve into informative embeddings. During inference, only the ST pathway is activated, leveraging evolving ST tokens to deliver the answer directly. Extensive experimental results demonstrate that DART achieves comparable reasoning performance to existing baselines while offering significant efficiency gains, serving as a feasible alternative for efficient reasoning.

[Arxiv](https://arxiv.org/abs/2506.11752)
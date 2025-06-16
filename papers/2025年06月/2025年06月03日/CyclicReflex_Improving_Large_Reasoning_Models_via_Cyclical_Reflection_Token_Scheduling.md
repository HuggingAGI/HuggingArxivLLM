# 循环反射：利用循环式反射标记调度优化大型推理模型

发布时间：2025年06月03日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）推理过程中的反思标记使用策略，提出了一种优化解码策略的方法，属于模型理论层面的研究。` `人工智能` `算法优化`

> CyclicReflex: Improving Large Reasoning Models via Cyclical Reflection Token Scheduling

# 摘要

> 大型推理模型（LRMs）如OpenAI的o1和DeepSeek-R1，通过测试时缩放实现多步骤推理，从而有效解决复杂问题。在生成最终答案前，这一推理过程通常由特殊转折标记或文本片段引导，促使模型进行自我反思评估。我们将这些过渡标记和反思提示统称为“反思标记”（例如，“等等”、“但是”、“或者”）。在本研究中，我们将反思标记视为一种“资源”，并引入资源分配问题，旨在通过自适应调节反思标记的频率和位置，提升LRMs在测试时的计算性能。通过实证分析，我们发现，无论是过度使用还是使用不足的反思标记（分别称为过反思和欠反思）都会对模型性能产生负面影响。为了更好地理解和管理这一权衡，我们将反思标记的使用与优化中的学习率调度进行类比。基于这一见解，我们提出了一种称为循环反思标记调度（CyclicReflex）的解码策略，该策略利用位置相关的三角波形动态调节反思标记的对数概率。在MATH500、AIME2024/2025和AMC2023等数据集上的实验表明，CyclicReflex在不同规模（1.5B-8B）的模型上均能持续提升性能，优于标准解码和更近期的方法如TIP（思想切换惩罚）和S1。代码可在GitHub仓库https://github.com/OPTML-Group/CyclicReflex获取。

> Large reasoning models (LRMs), such as OpenAI's o1 and DeepSeek-R1, harness test-time scaling to perform multi-step reasoning for complex problem-solving. This reasoning process, executed before producing final answers, is often guided by special juncture tokens or textual segments that prompt self-evaluative reflection. We refer to these transition markers and reflective cues as "reflection tokens" (e.g., "wait", "but", "alternatively"). In this work, we treat reflection tokens as a "resource" and introduce the problem of resource allocation, aimed at improving the test-time compute performance of LRMs by adaptively regulating the frequency and placement of reflection tokens. Through empirical analysis, we show that both excessive and insufficient use of reflection tokens, referred to as over-reflection and under-reflection, can degrade model performance. To better understand and manage this trade-off, we draw an analogy between reflection token usage and learning rate scheduling in optimization. Building on this insight, we propose cyclical reflection token scheduling (termed CyclicReflex), a decoding strategy that dynamically modulates reflection token logits using a position-dependent triangular waveform. Experiments on MATH500, AIME2024/2025, and AMC2023 demonstrate that CyclicReflex consistently improves performance across model sizes (1.5B-8B), outperforming standard decoding and more recent approaches such as TIP (thought switching penalty) and S1. Codes are available at https://github.com/OPTML-Group/CyclicReflex.

[Arxiv](https://arxiv.org/abs/2506.11077)
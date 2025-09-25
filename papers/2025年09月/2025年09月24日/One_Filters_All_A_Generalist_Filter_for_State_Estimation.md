# # 一滤全通：状态估计的通用型滤波器

发布时间：2025年09月24日

`LLM应用` `基础理论`

> One Filters All: A Generalist Filter for State Estimation

# 摘要

> 估计动态系统的隐藏状态（即最优滤波）是科学与工程领域长期面临的难题。本文提出一种通用滤波框架	extbf{LLM-Filter}，它通过将含噪观测与文本原型嵌入，借助大型语言模型（LLMs）实现状态估计。在经典动态系统的多组实验中，我们发现：首先，预训练LLMs蕴含的推理知识能显著提升状态估计性能；通过与冻结的LLM实现恰当的模态对齐，LLM-Filter性能超越了当前最先进的基于学习的方法。其次，我们精心设计了提示结构——System-as-Prompt（SaP），融入任务指令以帮助LLM理解估计任务。在这些提示引导下，LLM-Filter展现出优异的泛化能力，即便在变化甚至全新的环境中也能精准完成滤波任务。我们还观察到LLM-Filter存在缩放律特性：模型规模越大、训练时间越长，精度就越高。这些发现让LLM-Filter有望成为滤波领域的基础模型。

> Estimating hidden states in dynamical systems, also known as optimal filtering, is a long-standing problem in various fields of science and engineering. In this paper, we introduce a general filtering framework, \textbf{LLM-Filter}, which leverages large language models (LLMs) for state estimation by embedding noisy observations with text prototypes. In various experiments for classical dynamical systems, we find that first, state estimation can significantly benefit from the reasoning knowledge embedded in pre-trained LLMs. By achieving proper modality alignment with the frozen LLM, LLM-Filter outperforms the state-of-the-art learning-based approaches. Second, we carefully design the prompt structure, System-as-Prompt (SaP), incorporating task instructions that enable the LLM to understand the estimation tasks. Guided by these prompts, LLM-Filter exhibits exceptional generalization, capable of performing filtering tasks accurately in changed or even unseen environments. We further observe a scaling-law behavior in LLM-Filter, where accuracy improves with larger model sizes and longer training times. These findings make LLM-Filter a promising foundation model of filtering.

[Arxiv](https://arxiv.org/abs/2509.20051)
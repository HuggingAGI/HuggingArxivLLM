# 利用行列式点过程提升大型语言模型的多样性

发布时间：2025年09月04日

`LLM应用` `基础理论`

> Enhancing Diversity in Large Language Models via Determinantal Point Processes

# 摘要

> 监督微调与强化学习是大型语言模型（LLMs）后训练的两大主流方法。虽然它们能有效提升模型在下游任务中的表现，却常以牺牲输出多样性为代价，最终生成的回答往往局限于固定模式。现有增强多样性的手段尚存不足：要么仅在推理阶段生效，要么局限于词汇层面的差异。为此，我们提出一种基于行列式点过程（DPPs）的新型训练方法DQO，实现对LLMs生成质量与语义多样性的联合优化。该方法首先为每个提示词采样并嵌入一组回答，随后通过基于核函数的相似度矩阵的行列式计算多样性——即这些回答嵌入所张成的体积。在指令遵循、文本摘要、故事生成及推理等任务上的实验结果显示，我们的方法能在不降低模型质量的同时，大幅提升语义多样性。

> Supervised fine-tuning and reinforcement learning are two popular methods for post-training large language models (LLMs). While improving the model's performance on downstream tasks, they often reduce the model's output diversity, leading to narrow, canonical responses. Existing methods to enhance diversity are limited, either by operating at inference time or by focusing on lexical differences. We propose a novel training method named DQO based on determinantal point processes (DPPs) to jointly optimize LLMs for quality and semantic diversity. Our approach samples and embeds a group of responses for each prompt, then uses the determinant of a kernel-based similarity matrix to measure diversity as the volume spanned by the embeddings of these responses. Experiments across instruction-following, summarization, story generation, and reasoning tasks demonstrate that our method substantially improves semantic diversity without sacrificing model quality.

[Arxiv](https://arxiv.org/abs/2509.04784)
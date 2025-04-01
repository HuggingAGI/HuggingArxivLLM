# 大型推理模型的高效推理方法综述

发布时间：2025年03月29日

`LLM应用` `人工智能` `模型优化`

> Efficient Inference for Large Reasoning Models: A Survey

# 摘要

> 大型推理模型（LRMs）通过学习推理能力显著提升了大型语言模型（LLMs）的推理能力，在复杂任务解决中表现出色。然而，其深思熟虑的推理过程导致了在token使用、内存消耗和推理时间上的低效。因此，本调查综述了专门针对LRMs设计的高效推理方法，重点在于缓解token低效问题同时保持推理质量。

首先，我们介绍了一个分类法，将近期方法分为两大类：(a) 显式紧凑的思维链（CoT），在保持显式推理结构的同时减少token数量；(b) 隐式潜在的CoT，将推理步骤编码在隐藏表示中而非显式token中。同时，我们讨论了它们的优缺点。然后，我们从性能和效率方面对现有方法进行实证分析。此外，我们提出了该领域的一些开放挑战，包括以人类为中心的可控推理、推理的可解释性与效率之间的权衡、确保高效推理的安全性，以及高效推理的更广泛应用。另外，我们强调了通过模型合并、新架构和代理路由器等技术提升LRMs推理效率的关键见解。

我们希望这项工作能作为一个有价值的指南，帮助研究人员克服这一充满活力的领域中的挑战ootnote{https://github.com/yueliu1999/Awesome-Efficient-Inference-for-LRMs}。

> Large Reasoning Models (LRMs) significantly improve the reasoning ability of Large Language Models (LLMs) by learning to reason, exhibiting promising performance in complex task-solving. However, their deliberative reasoning process leads to inefficiencies in token usage, memory consumption, and inference time. Thus, this survey provides a review of efficient inference methods designed specifically for LRMs, focusing on mitigating token inefficiency while preserving the reasoning quality. First, we introduce a taxonomy to group the recent methods into two main categories: (a) explicit compact Chain-of-Thought (CoT), which reduces tokens while keeping the explicit reasoning structure, and (b) implicit latent CoT, which encodes reasoning steps within hidden representations instead of explicit tokens. Meanwhile, we discuss their strengths and weaknesses. Then, we conduct empirical analyses on existing methods from performance and efficiency aspects. Besides, we present open challenges in this field, including human-centric controllable reasoning, trade-off between interpretability and efficiency of reasoning, ensuring safety of efficient reasoning, and broader applications of efficient reasoning. In addition, we highlight key insights for enhancing LRMs' inference efficiency via techniques such as model merging, new architectures, and agent routers. We hope this work serves as a valuable guide, helping researchers overcome challenges in this vibrant field\footnote{https://github.com/yueliu1999/Awesome-Efficient-Inference-for-LRMs}.

[Arxiv](https://arxiv.org/abs/2503.23077)
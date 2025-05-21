# InfiFPO: 基于偏好优化的大型语言模型隐式模型融合方法

发布时间：2025年05月19日

`LLM理论`

> InfiFPO: Implicit Model Fusion via Preference Optimization in Large Language Models

# 摘要

> # 模型融合
模型融合通过轻量级训练方法，将多个具有不同优势的大型语言模型（LLMs）整合成一个更强大的综合性模型。现有研究主要集中在监督微调（SFT）方面，而对提升大模型性能至关重要的偏好对齐（PA）研究却相对较少。目前在PA阶段的少数融合方法，如WRPO，通过仅利用来源模型的响应输出而丢弃其概率信息来简化过程。

为解决这一局限性，我们提出了InfiFPO，一种用于隐式模型融合的偏好优化方法。InfiFPO在直接偏好优化（DPO）中用一个多源概率综合的融合源模型替换参考模型，从而规避了之前工作中复杂的词汇对齐挑战，同时保留了概率信息。通过引入概率裁剪和最大-margin融合策略，InfiFPO使主模型能够对齐人类偏好，同时有效提炼来源模型的知识。

在11个广泛使用的基准测试中的综合实验表明，InfiFPO在模型融合和偏好优化方面始终优于现有方法。当使用Phi-4作为主模型时，其在11个基准测试中的平均性能从79.95提升到83.33，显著增强了其在数学、编码和推理任务中的能力。


> Model fusion combines multiple Large Language Models (LLMs) with different strengths into a more powerful, integrated model through lightweight training methods. Existing works on model fusion focus primarily on supervised fine-tuning (SFT), leaving preference alignment (PA) --a critical phase for enhancing LLM performance--largely unexplored. The current few fusion methods on PA phase, like WRPO, simplify the process by utilizing only response outputs from source models while discarding their probability information. To address this limitation, we propose InfiFPO, a preference optimization method for implicit model fusion. InfiFPO replaces the reference model in Direct Preference Optimization (DPO) with a fused source model that synthesizes multi-source probabilities at the sequence level, circumventing complex vocabulary alignment challenges in previous works and meanwhile maintaining the probability information. By introducing probability clipping and max-margin fusion strategies, InfiFPO enables the pivot model to align with human preferences while effectively distilling knowledge from source models. Comprehensive experiments on 11 widely-used benchmarks demonstrate that InfiFPO consistently outperforms existing model fusion and preference optimization methods. When using Phi-4 as the pivot model, InfiFPO improve its average performance from 79.95 to 83.33 on 11 benchmarks, significantly improving its capabilities in mathematics, coding, and reasoning tasks.

[Arxiv](https://arxiv.org/abs/2505.13878)
# SaLoRA: 安全对齐的低秩适应

发布时间：2025年01月03日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）的参数高效微调（PEFT）方法，特别是LoRA微调对模型安全对齐的影响，并提出了一种新的方法（SaLoRA）来保持模型的安全对齐。论文的核心内容涉及LLMs的理论和微调方法，属于对LLMs的理论研究和改进，因此分类为LLM理论。` `模型安全`

> SaLoRA: Safety-Alignment Preserved Low-Rank Adaptation

# 摘要

> 随着大型语言模型（LLMs）的持续进步和个性化模型需求的增长，参数高效微调（PEFT）方法（如LoRA）因其高效降低计算成本而变得不可或缺。然而，近期研究指出，LoRA微调可能损害LLMs的安全对齐，给模型所有者带来重大风险。本文首先通过分析微调前后安全对齐相关特征的变化，探究其潜在机制。随后，我们提出了一种基于安全数据计算的固定安全模块，以及低秩适应中可训练参数的特定任务初始化方法，称为安全对齐保持的低秩适应（SaLoRA）。与以往LoRA方法不同，SaLoRA能在不破坏原始对齐的情况下，对LLMs进行精准修改。实验表明，SaLoRA在多种微调任务中，各项评估指标均优于现有适配器方法。

> As advancements in large language models (LLMs) continue and the demand for personalized models increases, parameter-efficient fine-tuning (PEFT) methods (e.g., LoRA) will become essential due to their efficiency in reducing computation costs. However, recent studies have raised alarming concerns that LoRA fine-tuning could potentially compromise the safety alignment in LLMs, posing significant risks for the model owner. In this paper, we first investigate the underlying mechanism by analyzing the changes in safety alignment related features before and after fine-tuning. Then, we propose a fixed safety module calculated by safety data and a task-specific initialization for trainable parameters in low-rank adaptations, termed Safety-alignment preserved Low-Rank Adaptation (SaLoRA). Unlike previous LoRA methods and their variants, SaLoRA enables targeted modifications to LLMs without disrupting their original alignments. Our experiments show that SaLoRA outperforms various adapters-based approaches across various evaluation metrics in different fine-tuning tasks.

[Arxiv](https://arxiv.org/abs/2501.01765)
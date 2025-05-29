# LoKI：大型语言模型的低损伤知识植入术

发布时间：2025年05月28日

`LLM理论`

> LoKI: Low-damage Knowledge Implanting of Large Language Models

# 摘要

> 微调能够将预训练模型适应特定任务，但同时也存在灾难性遗忘（CF）的风险，即预训练中关键知识被覆盖。当前针对大型语言模型（LLMs）的参数高效微调（PEFT）方法虽然高效，但往往牺牲了模型的通用能力。为了在通用PEFT框架中解决CF问题，我们提出了一种基于对知识在Transformer架构中存储机制理解的PEFT技术——	extbf{Lo}w-damage 	extbf{K}nowledge 	extbf{I}mplanting (	extbf{LoKI})。在两个实际场景中，LoKI在特定任务上的表现可与全量微调和基于LoRA的方法相媲美，甚至超越它们，同时显著保留了模型的通用能力。我们的工作将对LLM知识存储的机制性理解与实际微调目标相结合，在任务专业化和通用能力保留之间实现了当前最优的平衡。我们的实现作为即用代码公开可用ootnote{https://github.com/Nexround/LoKI}。

> Fine-tuning adapts pretrained models for specific tasks but poses the risk of catastrophic forgetting (CF), where critical knowledge from pre-training is overwritten. Current Parameter-Efficient Fine-Tuning (PEFT) methods for Large Language Models (LLMs), while efficient, often sacrifice general capabilities. To address the issue of CF in a general-purpose PEFT framework, we propose \textbf{Lo}w-damage \textbf{K}nowledge \textbf{I}mplanting (\textbf{LoKI}), a PEFT technique that is based on a mechanistic understanding of how knowledge is stored in transformer architectures. In two real-world scenarios, LoKI demonstrates task-specific performance that is comparable to or even surpasses that of full fine-tuning and LoRA-based methods across various model types, while significantly better preserving general capabilities. Our work connects mechanistic insights into LLM knowledge storage with practical fine-tuning objectives, achieving state-of-the-art trade-offs between task specialization and the preservation of general capabilities. Our implementation is publicly available as ready-to-use code\footnote{https://github.com/Nexround/LoKI}.

[Arxiv](https://arxiv.org/abs/2505.22120)
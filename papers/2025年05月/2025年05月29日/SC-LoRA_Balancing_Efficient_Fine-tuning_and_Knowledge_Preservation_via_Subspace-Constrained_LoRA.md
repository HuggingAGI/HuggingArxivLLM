# SC-LoRA：通过子空间约束的LoRA实现高效微调与知识保留的平衡

发布时间：2025年05月29日

`LLM理论` `模型微调`

> SC-LoRA: Balancing Efficient Fine-tuning and Knowledge Preservation via Subspace-Constrained LoRA

# 摘要

> 参数高效微调（PEFT）方法，尤其是低秩适应（LoRA），是高效定制大型语言模型（LLMs）的重要工具。然而，传统的LoRA方法存在收敛速度慢和知识遗忘的问题。近期研究通过设计LoRA初始化方法，提升了微调效率或保留了预训练LLM的知识。但这些方法无法同时解决这两个问题。因此，我们提出了子空间约束LoRA（SC-LoRA），一种新型的LoRA初始化框架，旨在平衡高效微调和知识保留之间的 trade-off。通过在低秩子空间中约束可训练的LoRA适配器输出，使得微调数据的上下文信息得到最大程度的保留，而保留知识的上下文信息得到最小程度的保持，从而实现平衡。这种约束使得可训练权重主要关注微调数据的主要特征，同时避免损害保留的知识特征。我们对方法进行了理论分析，并在各种下游任务上进行了广泛实验，包括安全性和世界知识的保留测试。实验结果表明，SC-LoRA在实现卓越微调性能的同时，显著减少了知识遗忘，超越了现有的LoRA初始化方法。

> Parameter-Efficient Fine-Tuning (PEFT) methods, particularly Low-Rank Adaptation (LoRA), are indispensable for efficiently customizing Large Language Models (LLMs). However, vanilla LoRA suffers from slow convergence speed and knowledge forgetting problems. Recent studies have leveraged the power of designed LoRA initialization, to enhance the fine-tuning efficiency, or to preserve knowledge in the pre-trained LLM. However, none of these works can address the two cases at the same time. To this end, we introduce Subspace-Constrained LoRA (SC-LoRA), a novel LoRA initialization framework engineered to navigate the trade-off between efficient fine-tuning and knowledge preservation. We achieve this by constraining the output of trainable LoRA adapters in a low-rank subspace, where the context information of fine-tuning data is most preserved while the context information of preserved knowledge is least retained, in a balanced way. Such constraint enables the trainable weights to primarily focus on the main features of fine-tuning data while avoiding damaging the preserved knowledge features. We provide theoretical analysis on our method, and conduct extensive experiments including safety preservation and world knowledge preservation, on various downstream tasks. In our experiments, SC-LoRA succeeds in delivering superior fine-tuning performance while markedly diminishing knowledge forgetting, surpassing contemporary LoRA initialization methods.

[Arxiv](https://arxiv.org/abs/2505.23724)
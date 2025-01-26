# 如何在保持LLM通用能力的同时完成领域调优：自适应分层与元素级正则化

发布时间：2025年01月23日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在微调过程中出现的灾难性遗忘问题，并提出了一种新的方法来计算模型参数的元素级重要性，以保留通用知识。该研究涉及LLMs的理论层面，特别是模型微调和参数优化策略，属于对LLMs内部机制和理论框架的探讨，因此应归类为LLM理论。` `机器学习`

> How to Complete Domain Tuning while Keeping General Ability in LLM: Adaptive Layer-wise and Element-wise Regularization

# 摘要

> 大型语言模型（LLMs）具备强大的通用语言能力，但在特定领域任务上微调时，常出现灾难性遗忘问题，即模型会覆盖或丢失预训练阶段的关键知识，这大大限制了LLMs的广泛应用。为解决这一难题，我们提出了一种新方法，用于计算模型参数的元素级重要性，确保在微调过程中保留通用知识。该方法采用双目标优化策略：一是通过正则化损失保留对通用知识至关重要的参数；二是通过交叉熵损失适应特定领域任务。此外，我们还引入了分层系数，动态平衡不同层的贡献，优化双目标。在科学、医学和物理任务上，基于GPT-J和LLaMA-3的实验表明，该方法在提升模型适应性的同时，有效缓解了灾难性遗忘。与现有方法相比，我们的方案速度提升约20倍，存储需求仅为其10%-15%，展现了显著的实用效率。代码将开源发布。

> Large Language Models (LLMs) exhibit strong general-purpose language capabilities. However, fine-tuning these models on domain-specific tasks often leads to catastrophic forgetting, where the model overwrites or loses essential knowledge acquired during pretraining. This phenomenon significantly limits the broader applicability of LLMs. To address this challenge, we propose a novel approach to compute the element-wise importance of model parameters crucial for preserving general knowledge during fine-tuning. Our method utilizes a dual-objective optimization strategy: (1) regularization loss to retain the parameter crucial for general knowledge; (2) cross-entropy loss to adapt to domain-specific tasks. Additionally, we introduce layer-wise coefficients to account for the varying contributions of different layers, dynamically balancing the dual-objective optimization. Extensive experiments on scientific, medical, and physical tasks using GPT-J and LLaMA-3 demonstrate that our approach mitigates catastrophic forgetting while enhancing model adaptability. Compared to previous methods, our solution is approximately 20 times faster and requires only 10%-15% of the storage, highlighting the practical efficiency. The code will be released.

[Arxiv](https://arxiv.org/abs/2501.13669)
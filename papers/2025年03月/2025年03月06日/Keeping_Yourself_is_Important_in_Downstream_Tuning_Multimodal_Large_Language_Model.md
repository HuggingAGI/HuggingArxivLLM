# 保持自身特色在多模态大型语言模型下游微调中至关重要——探索模型调优的新思路

发布时间：2025年03月06日

`LLM应用` `多模态模型` `模型调优`

> Keeping Yourself is Important in Downstream Tuning Multimodal Large Language Model

# 摘要

> 多模态大型语言模型（MLLMs）通过整合视觉与语言推理能力，能够有效处理图像描述和视觉问答等复杂任务。尽管MLLMs展现了卓越的多功能性，但在特殊应用场景下的性能表现似乎存在局限。在对MLLMs进行下游任务调优时，我们面临两大核心挑战：任务专家专精化，即预训练数据集与目标数据集之间的分布差异限制了目标性能；以及开放世界稳定化，其中灾难性遗忘导致模型丢失通用知识。在本研究中，我们系统性地回顾了MLLM调优方法的最新进展，并将其分类为三种范式：（I）选择性调优，（II）附加性调优，以及（III）重新参数化调优。此外，我们对这些调优策略在 popular MLLM 架构和多样化下游任务中的表现进行了基准测试，以建立标准化的评估分析和系统的调优原则。最后，我们指出了该领域目前存在的若干开放性挑战，并提出了未来的研究方向。为了促进这一快速发展的领域中的持续进步，我们提供了一个公共存储库，持续跟踪相关进展：https://github.com/WenkeHuang/Awesome-MLLM-Tuning。


> Multi-modal Large Language Models (MLLMs) integrate visual and linguistic reasoning to address complex tasks such as image captioning and visual question answering. While MLLMs demonstrate remarkable versatility, MLLMs appears limited performance on special applications. But tuning MLLMs for downstream tasks encounters two key challenges: Task-Expert Specialization, where distribution shifts between pre-training and target datasets constrain target performance, and Open-World Stabilization, where catastrophic forgetting erases the model general knowledge. In this work, we systematically review recent advancements in MLLM tuning methodologies, classifying them into three paradigms: (I) Selective Tuning, (II) Additive Tuning, and (III) Reparameterization Tuning. Furthermore, we benchmark these tuning strategies across popular MLLM architectures and diverse downstream tasks to establish standardized evaluation analysis and systematic tuning principles. Finally, we highlight several open challenges in this domain and propose future research directions. To facilitate ongoing progress in this rapidly evolving field, we provide a public repository that continuously tracks developments: https://github.com/WenkeHuang/Awesome-MLLM-Tuning.

[Arxiv](https://arxiv.org/abs/2503.04543)
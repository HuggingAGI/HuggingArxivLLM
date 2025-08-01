# Med-R$^3$: 利用渐进式强化学习提升大型语言模型的医学检索增强推理能力

发布时间：2025年07月31日

`RAG` `知识图谱`

> Med-R$^3$: Enhancing Medical Retrieval-Augmented Reasoning of LLMs via Progressive Reinforcement Learning

# 摘要

> 在医疗领域，有效检索外部知识并进行严谨逻辑推理至关重要。现有研究虽具备潜力，但主要关注于孤立提升模型的检索或推理能力，对两者的联合优化关注较少，导致两者协调性有限。此外，现有方法严重依赖监督微调（SFT），可能导致模型记忆现有问题解决路径，从而限制其在新型问题情境下的泛化能力。另外，尽管一些研究尝试通过强化学习提升通用领域中的检索增强推理，但其奖励函数设计未能充分满足医疗领域的特定需求。为解决这些问题，我们提出了**Med-R$^3$**——一个基于渐进式强化学习驱动的**Med**ical **R**etrieval-augmented **R**easoning框架。首先，我们在框架中开发模型对医疗问题进行逻辑推理的能力。随后，在此基础上，我们自适应优化检索能力，使其在整个推理过程中更好地与知识语料库和外部信息利用特性相匹配。最后，我们对模型的检索与推理协调进行联合优化。大量实验表明，**Med-R$^3$**能够实现最先进的性能。具体而言，LLaMA3.1-8B-Instruct + Med-R$^3$在与闭源GPT-4o-mini相当的参数规模下，性能超出3.93%；而增强Med-R$^3$的Qwen2.5-14B则获得了更为显著的13.53%提升。

> In medical scenarios, effectively retrieving external knowledge and leveraging it for rigorous logical reasoning is of significant importance. Despite their potential, existing work has predominantly focused on enhancing either retrieval or reasoning capabilities of the models in isolation, with little attention given to their joint optimization, which leads to limited coordination between the two processes. Additionally, current methods rely heavily on supervised fine-tuning (SFT), which can cause models to memorize existing problem-solving pathways, thereby restricting their generalization ability when confronted with novel problem contexts. Furthermore, while some studies have explored to improve retrieval-augmented reasoning in general domains via reinforcement learning, their reward function designs do not adequately capture the specific demands of the medical domain. To address these challenges, we introduce **Med-R$^3$**, a **Med**ical **R**etrieval-augmented **R**easoning framework driven by progressive **R**einforcement learning. In this framework, we first develop the model's ability to perform logical reasoning over medical problems. Subsequently, on the basis of this foundation, we adaptively optimize the retrieval capability to better align with the characteristics of knowledge corpus and external information utilization throughout the reasoning process. Finally, we conduct joint optimization of the model's retrieval and reasoning coordination. Extensive experiments indicate that **Med-R$^3$** could achieve state-of-the-art performances, with LLaMA3.1-8B-Instruct + Med-R$^3$ surpassing closed-sourced GPT-4o-mini by 3.93\% at a comparable parameter scale, while Qwen2.5-14B augmented with Med-R$^3$ shows a more substantial gain of 13.53\%.

[Arxiv](https://arxiv.org/abs/2507.23541)
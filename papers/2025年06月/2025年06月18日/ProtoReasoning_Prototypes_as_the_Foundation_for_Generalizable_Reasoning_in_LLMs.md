# ProtoReasoning：原型作为LLMs中可泛化推理的基础

发布时间：2025年06月18日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的跨领域泛化能力，提出了推理原型的概念，并通过ProtoReasoning框架来增强模型的推理能力。其核心贡献在于理解模型的工作机制和提升推理能力，属于理论层面的探讨。`

> ProtoReasoning: Prototypes as the Foundation for Generalizable Reasoning in LLMs

# 摘要

> # 近期进展  
近期，通过长链式推理（Long CoT）训练的大型推理模型（LRMs）展现出了卓越的跨领域泛化能力。然而，支撑这种迁移能力的内在机制仍未被充分理解。我们假设，跨领域泛化能力源于共享的抽象推理原型——这些基本的推理模式能够捕捉不同领域问题的本质。这些原型通过简化表征的细微差别，揭示了看似截然不同的任务实际上建立在共享的推理结构之上。  

基于这一假设，我们提出了ProtoReasoning框架，该框架通过利用可扩展且可验证的原型表征（如用于逻辑推理的Prolog和用于规划的PDDL）来增强大型语言模型的推理能力。ProtoReasoning具有以下特点：  
(1) 自动化原型构建管道，能够将问题转化为对应的原型表征；  
(2) 综合验证系统，通过Prolog/PDDL解释器提供可靠的反馈；  
(3) 在保证正确性的前提下，能够通过原型空间任意合成问题，展现出良好的可扩展性。  

大量实验证明，ProtoReasoning在逻辑推理（Enigmata-Eval）任务上比基线模型提升了4.7%，在规划任务上提升了6.3%，在通用推理（MMLU）任务上提升了4.0%，在数学（AIME24）任务上提升了1.0%。值得注意的是，我们的消融研究证实，与仅基于自然语言表征的训练相比，基于原型空间的学习在结构相似的问题上也表现出更强的泛化能力，这验证了我们的假设：推理原型是大型语言模型实现通用推理能力的基础。


> Recent advances in Large Reasoning Models (LRMs) trained with Long Chain-of-Thought (Long CoT) reasoning have demonstrated remarkable cross-domain generalization capabilities. However, the underlying mechanisms supporting such transfer remain poorly understood. We hypothesize that cross-domain generalization arises from shared abstract reasoning prototypes -- fundamental reasoning patterns that capture the essence of problems across domains. These prototypes minimize the nuances of the representation, revealing that seemingly diverse tasks are grounded in shared reasoning structures.Based on this hypothesis, we propose ProtoReasoning, a framework that enhances the reasoning ability of LLMs by leveraging scalable and verifiable prototypical representations (Prolog for logical reasoning, PDDL for planning).ProtoReasoning features: (1) an automated prototype construction pipeline that transforms problems into corresponding prototype representations; (2) a comprehensive verification system providing reliable feedback through Prolog/PDDL interpreters; (3) the scalability to synthesize problems arbitrarily within prototype space while ensuring correctness. Extensive experiments show that ProtoReasoning achieves 4.7% improvement over baseline models on logical reasoning (Enigmata-Eval), 6.3% improvement on planning tasks, 4.0% improvement on general reasoning (MMLU) and 1.0% on mathematics (AIME24). Significantly, our ablation studies confirm that learning in prototype space also demonstrates enhanced generalization to structurally similar problems compared to training solely on natural language representations, validating our hypothesis that reasoning prototypes serve as the foundation for generalizable reasoning in large language models.

[Arxiv](https://arxiv.org/abs/2506.15211)
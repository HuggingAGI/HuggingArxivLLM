# 实现灵活高效的多模型融合，构建大规模知识聚合能力

发布时间：2025年05月28日

`LLM理论

理由：这篇论文探讨了如何改进大型语言模型（LLMs）的集成方法，提出了一种新的自适应选择和聚合框架，属于对LLM本身的理论研究和优化。` `人工智能` `模型构建`

> Enabling Flexible Multi-LLM Integration for Scalable Knowledge Aggregation

# 摘要

> 大型语言模型（LLMs）虽然潜力巨大，但通过传统微调持续改进仍具挑战，尤其在整合其他专业LLMs能力时。目前流行的集成方法和权重融合不仅需要大量内存，还难以适应动态变化的数据环境。近期研究尝试将多个LLMs的知识迁移到单一目标模型中，但这些方法仍面临任务间干扰和性能下降的问题，这主要源于候选选择和训练流水线的灵活性不足。为解决这些问题，我们提出了一种自适应选择和聚合来自多样化LLMs知识的框架，用于构建更强大的单一模型，同时避免集成方法的高内存开销和权重融合的僵化。具体而言，我们设计了一个自适应选择网络，能够根据LLMs的得分识别出最相关的源模型，从而有效减少知识干扰。我们还提出了一种动态加权融合策略，充分考虑候选LLMs的内在优势，并结合反馈驱动的损失函数，防止选择器过度依赖单一来源子集。实验结果表明，我们的方法不仅实现了更稳定和可扩展的知识聚合过程，还与现有方法相比，将知识干扰减少了高达50%。代码可在https://github.com/ZLKong/LLM_Integration获取

> Large language models (LLMs) have shown remarkable promise but remain challenging to continually improve through traditional finetuning, particularly when integrating capabilities from other specialized LLMs. Popular methods like ensemble and weight merging require substantial memory and struggle to adapt to changing data environments. Recent efforts have transferred knowledge from multiple LLMs into a single target model; however, they suffer from interference and degraded performance among tasks, largely due to limited flexibility in candidate selection and training pipelines. To address these issues, we propose a framework that adaptively selects and aggregates knowledge from diverse LLMs to build a single, stronger model, avoiding the high memory overhead of ensemble and inflexible weight merging. Specifically, we design an adaptive selection network that identifies the most relevant source LLMs based on their scores, thereby reducing knowledge interference. We further propose a dynamic weighted fusion strategy that accounts for the inherent strengths of candidate LLMs, along with a feedback-driven loss function that prevents the selector from converging on a single subset of sources. Experimental results demonstrate that our method can enable a more stable and scalable knowledge aggregation process while reducing knowledge interference by up to 50% compared to existing approaches. Code is avaliable at https://github.com/ZLKong/LLM_Integration

[Arxiv](https://arxiv.org/abs/2505.23844)
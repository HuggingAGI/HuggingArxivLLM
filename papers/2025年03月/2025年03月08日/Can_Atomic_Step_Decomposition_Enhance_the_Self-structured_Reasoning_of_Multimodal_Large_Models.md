# 原子步骤分解能否助力多模态大模型实现更高效的自我结构化推理？

发布时间：2025年03月08日

`LLM应用

理由：这篇论文讨论了如何将大型语言模型应用于多模态数学推理问题，并提出了一种新的方法来提升模型的推理能力。虽然涉及了一些理论上的改进，但核心是将模型应用于特定任务，因此归类为LLM应用。` `人工智能` `数学教育`

> Can Atomic Step Decomposition Enhance the Self-structured Reasoning of Multimodal Large Models?

# 摘要

> 本文提出了一种创新方法，通过将“慢思考”能力融入多模态大型语言模型（MLLMs），有效解决了多模态数学推理这一难题。我们的核心理念是动态结合不同层次的推理能力，以应对不同复杂程度的问题。为此，我们提出了一种名为自我结构化思维链（SCoT）的方法，它由最小的语义原子步骤组成。与现有依赖结构化模板或自由形式范式的方法不同，我们的方法不仅可以为各种复杂任务生成认知性的思维链结构，还可以有效缓解过度思考的现象。为了将结构化推理能力引入视觉理解模型，我们进一步设计了一种名为AtomThink的新框架，该框架包含四个关键模块：(i) 数据引擎，用于生成高质量多模态推理路径；(ii) 带有序列化推理数据的监督微调过程；(iii) 基于策略的多轮推理方法；以及 (iv) 用于评估单步利用率的原子能力指标。实验结果表明，AtomThink方法显著提升了基线MLLMs的性能，在MathVista和MathVerse数据集上平均准确率提升了超过10%。与现有最先进的结构化思维链方法相比，我们的方法不仅实现了更高的准确率，还将数据利用率提升了5倍，并将推理效率提升了85.3%。我们的代码现已公开，可在GitHub上获取。

> In this paper, we address the challenging task of multimodal mathematical reasoning by incorporating the ability of "slow thinking" into multimodal large language models (MLLMs). Our core idea is that different levels of reasoning abilities can be combined dynamically to tackle questions with different complexity. To this end, we propose a paradigm of Self-structured Chain of Thought (SCoT), which is composed of minimal semantic atomic steps. Different from existing methods that rely on structured templates or free-form paradigms, our method can not only generate cognitive CoT structures for various complex tasks but also mitigates the phenomenon of overthinking. To introduce structured reasoning capabilities into visual understanding models, we further design a novel AtomThink framework with four key modules, including (i) a data engine to generate high-quality multimodal reasoning paths; (ii) a supervised fine-tuning process with serialized inference data; (iii) a policy-guided multi-turn inference method; and (iv) an atomic capability metric to evaluate the single step utilization rate. We conduct extensive experiments to show that the proposed AtomThink significantly improves the performance of baseline MLLMs, achieving more than 10\% average accuracy gains on MathVista and MathVerse. Compared to state-of-the-art structured CoT approaches, our method not only achieves higher accuracy but also improves data utilization by 5 times and boosts inference efficiency by 85.3\%. Our code is now public available in https://github.com/Quinn777/AtomThink.

[Arxiv](https://arxiv.org/abs/2503.06252)
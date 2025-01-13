# 利用概念激活向量驾驭大型语言模型

发布时间：2025年01月10日

`LLM应用

**理由**：这篇论文主要讨论的是如何通过一种轻量级的模型控制框架（GCAV）来精确控制大型语言模型（LLMs）的生成输出，涉及毒性减少、情感控制、语言风格和主题控制等方面。这属于对LLMs在实际应用中的控制和优化，因此归类为LLM应用。` `人工智能`

> Controlling Large Language Models Through Concept Activation Vectors

# 摘要

> 随着大型语言模型（LLMs）在各领域的广泛应用，控制其生成输出的能力变得至关重要。这种控制不仅涉及将LLMs的输出与人类价值观和伦理原则对齐，还包括为个体用户定制特定主题或风格的LLMs。现有的控制生成方法要么需要大量计算资源和反复试验，要么只能提供粗粒度的控制。本文提出了一种轻量级的模型控制框架——基于概念激活向量的生成（GCAV），它能在无需大量资源微调的情况下实现精确控制。具体而言，GCAV首先为要控制的特定概念（如毒性）训练一个概念激活向量。在推理过程中，GCAV通过从激活层中移除毒性概念向量来引导LLMs的概念向量。实验表明，GCAV在毒性减少、情感控制、语言风格和主题控制等方面均达到了最先进的性能，并允许对引导层和引导幅度进行精细调整。

> As large language models (LLMs) are widely deployed across various domains, the ability to control their generated outputs has become more critical. This control involves aligning LLMs outputs with human values and ethical principles or customizing LLMs on specific topics or styles for individual users. Existing controlled generation methods either require significant computational resources and extensive trial-and-error or provide coarse-grained control. In this paper, we propose Generation with Concept Activation Vector (GCAV), a lightweight model control framework that ensures accurate control without requiring resource-extensive fine-tuning. Specifically, GCAV first trains a concept activation vector for specified concepts to be controlled, such as toxicity. During inference, GCAV steers the concept vector in LLMs, for example, by removing the toxicity concept vector from the activation layers. Control experiments from different perspectives, including toxicity reduction, sentiment control, linguistic style, and topic control, demonstrate that our framework achieves state-of-the-art performance with granular control, allowing for fine-grained adjustments of both the steering layers and the steering magnitudes for individual samples.

[Arxiv](https://arxiv.org/abs/2501.05764)
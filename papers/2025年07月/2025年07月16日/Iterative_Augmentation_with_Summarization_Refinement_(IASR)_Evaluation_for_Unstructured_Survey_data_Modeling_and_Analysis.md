# 迭代增强与摘要优化 (IASR) 评估方法在无结构调查数据分析建模中的应用

发布时间：2025年07月16日

`LLM应用` `文本数据增强`

> Iterative Augmentation with Summarization Refinement (IASR) Evaluation for Unstructured Survey data Modeling and Analysis

# 摘要

> 文本数据增强是解决自然语言处理（NLP）中数据稀疏性问题的常用策略，尤其在资源有限的场景下，样本量的不足会严重影响语义建模效果。虽然数据增强可以提升输入多样性和下游可解释性，但现有技术往往缺乏机制来保证大规模或迭代生成过程中语义的一致性，导致冗余和不稳定性。本研究提出了一种基于大型语言模型（LLM）的文本增强评估框架，包含两个核心组件：（1）可扩展性分析，用于衡量增强规模扩大时的语义一致性；（2）迭代增强结合摘要优化（IASR），用于评估递归式改写循环中的语义漂移。通过在前沿LLM上的实证研究表明，GPT-3.5 Turbo在语义保真度、多样性和生成效率间实现了最佳平衡。将其应用于实际的主题建模任务中，结合BERTopic与GPT增强的少量样本标注方法，实验结果表明主题粒度提升了400%，完全消除了主题重叠现象。这些发现验证了所提出的框架在实际NLP流水线中对基于LLM的增强方法进行结构化评估的实用性。


> Text data augmentation is a widely used strategy for mitigating data sparsity in natural language processing (NLP), particularly in low-resource settings where limited samples hinder effective semantic modeling. While augmentation can improve input diversity and downstream interpretability, existing techniques often lack mechanisms to ensure semantic preservation during large-scale or iterative generation, leading to redundancy and instability. This work introduces a principled evaluation framework for large language model (LLM) based text augmentation, comprising two components: (1) Scalability Analysis, which measures semantic consistency as augmentation volume increases, and (2) Iterative Augmentation with Summarization Refinement (IASR), which evaluates semantic drift across recursive paraphrasing cycles. Empirical evaluations across state-of-the-art LLMs show that GPT-3.5 Turbo achieved the best balance of semantic fidelity, diversity, and generation efficiency. Applied to a real-world topic modeling task using BERTopic with GPT-enhanced few-shot labeling, the proposed approach results in a 400% increase in topic granularity and complete elimination of topic overlaps. These findings validated the utility of the proposed frameworks for structured evaluation of LLM-based augmentation in practical NLP pipelines.

[Arxiv](https://arxiv.org/abs/2507.12126)
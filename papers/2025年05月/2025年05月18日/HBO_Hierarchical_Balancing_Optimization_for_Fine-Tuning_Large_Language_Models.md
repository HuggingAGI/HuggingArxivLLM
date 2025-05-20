# HBO：用于大型语言模型微调的分层平衡优化

发布时间：2025年05月18日

`LLM理论

摘要讨论了在微调大型语言模型时处理数据不平衡和异质性的问题，并提出了一种名为分层平衡优化（HBO）的新方法。该方法通过双层优化策略，全局和局部参与者协同工作，优化数据使用策略。这属于模型训练和优化的理论层面，因此归类为LLM理论。` `数据处理`

> HBO: Hierarchical Balancing Optimization for Fine-Tuning Large Language Models

# 摘要

> 在微调大型语言模型时，如何处理数据不平衡和异质性是一个棘手的问题。现有方法虽然能在数据集之间平衡问题，却忽视了单个数据集内部的不平衡和异质性，这大大限制了它们的实际效果。为此，我们提出了一种名为分层平衡优化（HBO）的新方法，让LLMs在微调过程中既能全局调整数据分配，又能局部优化每个数据集内的数据使用。HBO采用双层优化策略，包含两个关键角色：全局参与者负责平衡不同数据子集的采样，而局部参与者则根据任务难度优化每个子集内的数据使用。这些参与者通过基于LLM训练状态的奖励函数进行引导，实时衡量学习进展和性能提升。我们在多语言和多任务设置下的九个多样化任务中，对三个LLM模型进行了全面评估。结果显示，HBO不仅显著优于现有方法，还在多个场景中实现了更高的准确性。深入分析表明，HBO的全局和局部参与者在微调过程中均发挥了重要作用，有效调整了数据使用策略。HBO为解决LLM微调中的数据不平衡和异质性问题提供了一站式解决方案，显著提升了跨多样化数据集的训练效果。


> Fine-tuning large language models (LLMs) on a mixture of diverse datasets poses challenges due to data imbalance and heterogeneity. Existing methods often address these issues across datasets (globally) but overlook the imbalance and heterogeneity within individual datasets (locally), which limits their effectiveness. We introduce Hierarchical Balancing Optimization (HBO), a novel method that enables LLMs to autonomously adjust data allocation during fine-tuning both across datasets (globally) and within each individual dataset (locally). HBO employs a bilevel optimization strategy with two types of actors: a Global Actor, which balances data sampling across different subsets of the training mixture, and several Local Actors, which optimizes data usage within each subset based on difficulty levels. These actors are guided by reward functions derived from the LLM's training state, which measure learning progress and relative performance improvement. We evaluate HBO on three LLM backbones across nine diverse tasks in multilingual and multitask setups. Results show that HBO consistently outperforms existing baselines, achieving significant accuracy gains. Our in-depth analysis further demonstrates that both the global actor and local actors of HBO effectively adjust data usage during fine-tuning. HBO provides a comprehensive solution to the challenges of data imbalance and heterogeneity in LLM fine-tuning, enabling more effective training across diverse datasets.

[Arxiv](https://arxiv.org/abs/2505.12300)
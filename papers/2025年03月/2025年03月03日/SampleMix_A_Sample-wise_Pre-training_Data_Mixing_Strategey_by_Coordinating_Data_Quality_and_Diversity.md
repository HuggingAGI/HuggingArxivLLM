# SampleMix：兼顾数据质量和多样性的样本级预训练数据混合策略

发布时间：2025年03月03日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）的训练数据混合方法，提出了一种自底向上的样本级数据混合方法，以优化预训练数据的多样性和质量。该研究属于模型训练策略的改进，因此归类为LLM理论。` `数据科学` `人工智能`

> SampleMix: A Sample-wise Pre-training Data Mixing Strategey by Coordinating Data Quality and Diversity

# 摘要

> 现有的大型语言模型（LLMs）数据混合方法通常采用自上而下的基于领域策略，首先确定领域权重，然后在每个领域内进行均匀采样。然而，这些方法忽视了跨领域重叠与共性，无法控制全局数据多样性。此外，领域内均匀采样忽略了样本特性，可能影响数据分布。为解决这些问题，我们提出了一种自底向上的样本级数据混合方法。该方法通过评估样本质量和多样性，进行跨域全局采样，动态确定最优领域分布。实验表明，SampleMix在多个任务中超越现有方法，且仅需1.4到2.1倍训练步骤即可达到基线性能，展现了其优化预训练数据的潜力。

> Existing pretraining data mixing methods for large language models (LLMs) typically follow a domain-wise methodology, a top-down process that first determines domain weights and then performs uniform data sampling across each domain. However, these approaches neglect significant inter-domain overlaps and commonalities, failing to control the global diversity of the constructed training dataset. Further, uniform sampling within domains ignores fine-grained sample-specific features, potentially leading to suboptimal data distribution. To address these shortcomings, we propose a novel sample-wise data mixture approach based on a bottom-up paradigm. This method performs global cross-domain sampling by systematically evaluating the quality and diversity of each sample, thereby dynamically determining the optimal domain distribution. Comprehensive experiments across multiple downstream tasks and perplexity assessments demonstrate that SampleMix surpasses existing domain-based methods. Meanwhile, SampleMix requires 1.4x to 2.1x training steps to achieves the baselines' performance, highlighting the substantial potential of SampleMix to optimize pre-training data.

[Arxiv](https://arxiv.org/abs/2503.01506)
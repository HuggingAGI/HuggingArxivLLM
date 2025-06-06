# 少中见真知：高效多模态推理中的高价值数据选择

发布时间：2025年06月05日

`LLM应用` `人工智能` `数据科学`

> Truth in the Few: High-Value Data Selection for Efficient Multi-Modal Reasoning

# 摘要

> 多模态大型语言模型（MLLMs）在强化学习驱动的复杂推理任务中取得了显著进展，但传统观点认为，提升多模态推理能力需要大量训练数据，这不仅导致数据冗余，还带来了高昂的计算成本。然而，我们发现，较小的高价值数据集可能在多模态推理任务中表现出色。通过深入研究，我们发现：有意义的多模态推理仅由训练样本中一小部分关键样本（即认知样本）触发，而大多数样本的贡献微乎其微。基于这一发现，我们提出了一种名为推理激活潜力（RAP）的新数据选择范式。该方法通过两个互补的估计器来识别认知样本：1) 因果差异估计器（CDE）基于潜在结果模型原理，通过比较多模态与纯文本输入的输出，剔除过度依赖语言先验的样本；2) 注意力置信估计器（ACE）利用token级自注意力机制，在推理中间阶段丢弃那些由无关但被过度强调的token主导的样本。此外，我们引入了一个难度感知替换模块（DRM），用认知挑战性更高的实例替换简单的实例，从而确保多模态推理的复杂性。实验结果表明，仅使用9.3%的训练数据，我们的RAP方法即可实现更优性能，同时将计算成本降低43%以上。我们的代码可在https://github.com/Leo-ssl/RAP获取。

> While multi-modal large language models (MLLMs) have made significant progress in complex reasoning tasks via reinforcement learning, it is commonly believed that extensive training data is necessary for improving multi-modal reasoning ability, inevitably leading to data redundancy and substantial computational costs. However, can smaller high-value datasets match or outperform full corpora for multi-modal reasoning in MLLMs? In this work, we challenge this assumption through a key observation: meaningful multi-modal reasoning is triggered by only a sparse subset of training samples, termed cognitive samples, whereas the majority contribute marginally. Building on this insight, we propose a novel data selection paradigm termed Reasoning Activation Potential (RAP), which identifies cognitive samples by estimating each sample's potential to stimulate genuine multi-modal reasoning by two complementary estimators: 1) Causal Discrepancy Estimator (CDE) based on the potential outcome model principle, eliminates samples that overly rely on language priors by comparing outputs between multi-modal and text-only inputs; 2) Attention Confidence Estimator (ACE), which exploits token-level self-attention to discard samples dominated by irrelevant but over-emphasized tokens in intermediate reasoning stages. Moreover, we introduce a Difficulty-aware Replacement Module (DRM) to substitute trivial instances with cognitively challenging ones, thereby ensuring complexity for robust multi-modal reasoning. Experiments on six datasets show that our RAP method consistently achieves superior performance using only 9.3% of the training data, while reducing computational costs by over 43%. Our code is available at https://github.com/Leo-ssl/RAP.

[Arxiv](https://arxiv.org/abs/2506.04755)
# 模型内置奖励机制：轻量级隐藏状态奖励模型，提升 LLM 最佳 N 采样效果

发布时间：2025年05月18日

`LLM应用

这篇论文专注于优化奖励模型，提出了一种高效的方法来提升大型语言模型的应用性能，属于LLM应用类别。` `NLP`

> Reward Inside the Model: A Lightweight Hidden-State Reward Model for LLM's Best-of-N sampling

# 摘要

> 奖励模型是释放大型语言模型 (LLMs) 推理潜力的关键，其中最佳的N选1投票方法已显示出显著优势。然而，现有奖励模型计算成本高、参数繁冗，限制了实际应用。为此，我们提出了高效线性隐藏状态奖励 (ELHSR) 模型——一种参数高效的创新方案，充分挖掘LLM隐藏状态中的丰富信息。ELHSR仅需基线模型0.005%的参数量和少量训练样本，便在各项评估中显著优于传统方法。相比传统模型，ELHSR实现了数量级的效率提升，每个样本计算时间与FLOPs大幅减少。值得注意的是，ELHSR即使仅基于logits训练，依然表现出稳健性能，使其能够扩展应用于部分闭源LLMs。此外，ELHSR还可与传统奖励模型结合，进一步提升性能。

> High-quality reward models are crucial for unlocking the reasoning potential of large language models (LLMs), with best-of-N voting demonstrating significant performance gains. However, current reward models, which typically operate on the textual output of LLMs, are computationally expensive and parameter-heavy, limiting their real-world applications. We introduce the Efficient Linear Hidden State Reward (ELHSR) model - a novel, highly parameter-efficient approach that leverages the rich information embedded in LLM hidden states to address these issues. ELHSR systematically outperform baselines with less than 0.005% of the parameters of baselines, requiring only a few samples for training. ELHSR also achieves orders-of-magnitude efficiency improvement with significantly less time and fewer FLOPs per sample than baseline reward models. Moreover, ELHSR exhibits robust performance even when trained only on logits, extending its applicability to some closed-source LLMs. In addition, ELHSR can also be combined with traditional reward models to achieve additional performance gains.

[Arxiv](https://arxiv.org/abs/2505.12225)
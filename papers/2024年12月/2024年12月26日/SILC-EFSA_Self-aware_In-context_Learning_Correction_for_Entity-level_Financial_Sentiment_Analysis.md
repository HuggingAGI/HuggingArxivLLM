# SILC-EFSA: 自感知上下文学习校正，助力实体级金融情感分析

发布时间：2024年12月26日

`LLM应用

**理由**：该论文主要关注的是在金融领域的情感分析任务中应用大模型（LLM）进行微调和优化，属于LLM在实际任务中的应用场景。虽然涉及了数据集构建和模型优化，但其核心是利用LLM进行情感分析，因此归类为“LLM应用”。` `情感分析`

> SILC-EFSA: Self-aware In-context Learning Correction for Entity-level Financial Sentiment Analysis

# 摘要

> 近年来，金融领域的细粒度情感分析备受关注，但实体级数据集的稀缺性仍是主要挑战。为此，我们构建了迄今为止最大的中英文金融实体级情感分析数据集，并在此基础上提出了一种新颖的两阶段情感分析方法——自我感知的上下文学习校正（SILC）。第一阶段通过微调基础大模型生成任务相关的伪标签数据；第二阶段则利用基于GNN的示例检索器训练校正模型，结合伪标签数据进行优化。这一策略使我们在新数据集上取得了领先性能，推动了金融情感分析的发展。通过案例研究，我们展示了该方法在加密货币市场监控中的实际应用价值。数据集和代码已开源：https://github.com/NLP-Bin/SILC-EFSA。

> In recent years, fine-grained sentiment analysis in finance has gained significant attention, but the scarcity of entity-level datasets remains a key challenge. To address this, we have constructed the largest English and Chinese financial entity-level sentiment analysis datasets to date. Building on this foundation, we propose a novel two-stage sentiment analysis approach called Self-aware In-context Learning Correction (SILC). The first stage involves fine-tuning a base large language model to generate pseudo-labeled data specific to our task. In the second stage, we train a correction model using a GNN-based example retriever, which is informed by the pseudo-labeled data. This two-stage strategy has allowed us to achieve state-of-the-art performance on the newly constructed datasets, advancing the field of financial sentiment analysis. In a case study, we demonstrate the enhanced practical utility of our data and methods in monitoring the cryptocurrency market. Our datasets and code are available at https://github.com/NLP-Bin/SILC-EFSA.

[Arxiv](https://arxiv.org/abs/2412.19140)
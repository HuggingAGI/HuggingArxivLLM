# MARAGE：可迁移多模型对抗攻击，用于增强生成的数据提取

发布时间：2025年02月04日

`RAG` `信息安全`

> MARAGE: Transferable Multi-Model Adversarial Attack for Retrieval-Augmented Generation Data Extraction

# 摘要

> 检索增强生成（RAG）通过将大型语言模型（LLMs）的输出与外部知识相结合，有效缓解了幻觉现象。然而，在构建外部数据存储时使用私有资源和数据，可能会导致提取攻击风险，即攻击者试图窃取私有数据库中的数据。现有的RAG提取攻击通常依赖手动编写的提示，这限制了其有效性。本文提出了一种名为MARAGE的框架，用于优化对抗字符串，当将其附加到目标RAG系统的用户查询时，会导致输出中包含RAG检索数据的逐字内容。MARAGE采用了一种连续优化方案，同时结合多个不同架构模型的梯度，以增强优化字符串向未见过的模型的可迁移性。此外，我们提出了一种强调目标RAG数据初始令牌的策略，进一步提高了攻击的泛化能力。实验结果表明，MARAGE在多个LLMs和RAG数据集上始终优于手动和基于优化的基线，同时保持了对之前未见过的模型的鲁棒可迁移性。此外，我们通过探查任务揭示了MARAGE为何比基线更有效，并分析了我们的方法对模型内部状态的影响。

> Retrieval-Augmented Generation (RAG) offers a solution to mitigate hallucinations in Large Language Models (LLMs) by grounding their outputs to knowledge retrieved from external sources. The use of private resources and data in constructing these external data stores can expose them to risks of extraction attacks, in which attackers attempt to steal data from these private databases. Existing RAG extraction attacks often rely on manually crafted prompts, which limit their effectiveness. In this paper, we introduce a framework called MARAGE for optimizing an adversarial string that, when appended to user queries submitted to a target RAG system, causes outputs containing the retrieved RAG data verbatim. MARAGE leverages a continuous optimization scheme that integrates gradients from multiple models with different architectures simultaneously to enhance the transferability of the optimized string to unseen models. Additionally, we propose a strategy that emphasizes the initial tokens in the target RAG data, further improving the attack's generalizability. Evaluations show that MARAGE consistently outperforms both manual and optimization-based baselines across multiple LLMs and RAG datasets, while maintaining robust transferability to previously unseen models. Moreover, we conduct probing tasks to shed light on the reasons why MARAGE is more effective compared to the baselines and to analyze the impact of our approach on the model's internal state.

[Arxiv](https://arxiv.org/abs/2502.04360)
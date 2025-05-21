# 奖励驱动的推理模型

发布时间：2025年05月20日

`Agent` `机器学习`

> Reward Reasoning Model

# 摘要

> 奖励模型在引导大型语言模型生成符合人类预期的输出中至关重要。然而，如何有效利用测试时计算来提升奖励模型的性能仍是一个开放性挑战。本研究引入了奖励推理模型（RRMs），专为在生成最终奖励前执行深思熟虑的推理过程而设计。通过链式思维推理，RRMs能够在适当情况下利用额外的测试时计算处理复杂查询，其中合适的奖励并非显而易见。为了开发RRMs，我们实现了一个强化学习框架，培养自我演化的奖励推理能力，无需依赖显式的推理轨迹作为训练数据。实验结果表明，RRMs在不同领域的奖励建模基准测试中表现出色。值得注意的是，RRMs能够自适应地利用测试时计算进一步提高奖励准确性。预训练的奖励推理模型可在https://huggingface.co/Reward-Reasoning获取。

> Reward models play a critical role in guiding large language models toward outputs that align with human expectations. However, an open challenge remains in effectively utilizing test-time compute to enhance reward model performance. In this work, we introduce Reward Reasoning Models (RRMs), which are specifically designed to execute a deliberate reasoning process before generating final rewards. Through chain-of-thought reasoning, RRMs leverage additional test-time compute for complex queries where appropriate rewards are not immediately apparent. To develop RRMs, we implement a reinforcement learning framework that fosters self-evolved reward reasoning capabilities without requiring explicit reasoning traces as training data. Experimental results demonstrate that RRMs achieve superior performance on reward modeling benchmarks across diverse domains. Notably, we show that RRMs can adaptively exploit test-time compute to further improve reward accuracy. The pretrained reward reasoning models are available at https://huggingface.co/Reward-Reasoning.

[Arxiv](https://arxiv.org/abs/2505.14674)
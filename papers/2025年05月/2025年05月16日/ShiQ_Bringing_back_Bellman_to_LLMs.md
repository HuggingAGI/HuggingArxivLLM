# ShiQ：让贝尔曼回归LLMs的世界

发布时间：2025年05月16日

`LLM理论` `人工智能`

> ShiQ: Bringing back Bellman to LLMs

# 摘要

> 强化学习（RL）在预训练大型语言模型（LLMs）微调中通常被形式化为直接的策略优化问题。这种方法因其能有效提升预训练LLM的表现而备受青睐。然而，尽管Q学习方法在非LLM的RL任务中取得了巨大成功，但在LLM社区中却鲜少受到关注。特别是，Q学习的采样效率和离线学习能力在计算成本高昂的LLM采样中尤为珍贵。然而，直接将Q学习风格的更新应用到模型的logits上是无效的，因为这忽略了LLMs的特殊性。我们从贝尔曼方程推导出理论支持的损失函数，以将Q学习方法适应于LLMs。通过调整RL文献中的见解，我们确保了logits能够可靠地估计Q值。随后，我们构建了ShiQ（Shifted-Q）算法，支持离线策略、逐token的学习，同时保持了实现的简便性。我们在合成数据和真实世界基准测试（如UltraFeedback和BFCL-V3）上评估了ShiQ，证明了其在单轮和多轮LLM设置中的有效性。

> The fine-tuning of pre-trained large language models (LLMs) using reinforcement learning (RL) is generally formulated as direct policy optimization. This approach was naturally favored as it efficiently improves a pretrained LLM, seen as an initial policy. Another RL paradigm, Q-learning methods, has received far less attention in the LLM community while demonstrating major success in various non-LLM RL tasks. In particular, Q-learning effectiveness comes from its sample efficiency and ability to learn offline, which is particularly valuable given the high computational cost of sampling with LLMs. However, naively applying a Q-learning-style update to the model's logits is ineffective due to the specificity of LLMs. Our core contribution is to derive theoretically grounded loss functions from Bellman equations to adapt Q-learning methods to LLMs. To do so, we carefully adapt insights from the RL literature to account for LLM-specific characteristics, ensuring that the logits become reliable Q-value estimates. We then use this loss to build a practical algorithm, ShiQ for Shifted-Q, that supports off-policy, token-wise learning while remaining simple to implement. Finally, we evaluate ShiQ on both synthetic data and real-world benchmarks, e.g., UltraFeedback and BFCL-V3, demonstrating its effectiveness in both single-turn and multi-turn LLM settings

[Arxiv](https://arxiv.org/abs/2505.11081)
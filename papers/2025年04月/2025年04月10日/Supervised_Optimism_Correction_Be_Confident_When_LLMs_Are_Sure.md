# # 监督乐观校正：LLMs确信时，保持自信

发布时间：2025年04月10日

`LLM理论` `模型推理`

> Supervised Optimism Correction: Be Confident When LLMs Are Sure

# 摘要

> 本研究在 token 级马尔可夫决策过程中，揭示了监督微调与离线强化学习之间创新的理论关联，证明大型语言模型确实学习了一种隐式的 Q 函数用于推理。通过这一理论视角，我们发现广泛应用的束搜索方法存在不可接受的过度乐观问题，这源于对非最优步骤的 Q 值估计过高，导致推理错误被不可避免地放大。为解决这一问题，我们提出了监督乐观校正（Supervised Optimism Correction, SOC），在监督微调过程中引入一种简单而有效的辅助损失函数，用于优化 token 级 Q 值估计。具体而言，该辅助损失通过隐式值正则化增强了模型对专家演示响应的信心，从而抑制了对监督不足响应的过度乐观。我们在数学推理基准测试（包括 GSM8K、MATH 和 GAOKAO）上的广泛实验表明，所提出的 SOC 方法结合束搜索在一系列开源模型中表现优异。

> In this work, we establish a novel theoretical connection between supervised fine-tuning and offline reinforcement learning under the token-level Markov decision process, revealing that large language models indeed learn an implicit $Q$-function for inference. Through this theoretical lens, we demonstrate that the widely used beam search method suffers from unacceptable over-optimism, where inference errors are inevitably amplified due to inflated $Q$-value estimations of suboptimal steps. To address this limitation, we propose Supervised Optimism Correction(SOC), which introduces a simple yet effective auxiliary loss for token-level $Q$-value estimations during supervised fine-tuning. Specifically, the auxiliary loss employs implicit value regularization to boost model confidence in expert-demonstrated responses, thereby suppressing over-optimism toward insufficiently supervised responses. Extensive experiments on mathematical reasoning benchmarks, including GSM8K, MATH, and GAOKAO, showcase the superiority of the proposed SOC with beam search across a series of open-source models.

[Arxiv](https://arxiv.org/abs/2504.07527)
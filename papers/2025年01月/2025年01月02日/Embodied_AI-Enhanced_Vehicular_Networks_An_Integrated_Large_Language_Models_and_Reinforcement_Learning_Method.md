# # 具身AI增强的车辆网络：融合大型语言模型与强化学习的新方法

发布时间：2025年01月02日

`LLM应用

理由：该论文探讨了在车联网环境中使用大型语言模型（LLMs）进行语义信息提取，并结合深度强化学习（DRL）进行决策优化。这属于将LLM应用于特定领域（车联网）的实际问题解决，因此归类为“LLM应用”。` `车联网` `自动驾驶`

> Embodied AI-Enhanced Vehicular Networks: An Integrated Large Language Models and Reinforcement Learning Method

# 摘要

> 本文探讨了在具身AI增强的车联网中，通过结合大型语言模型（LLMs）进行语义信息提取和深度强化学习（DRL）进行决策的自适应传输策略。该框架旨在通过引入韦伯-费希纳定律作为优化指标，平衡带宽利用率和体验质量（QoE），从而提升数据传输效率和决策准确性。具体来说，我们使用大型语言和视觉助手（LLAVA）模型从车辆捕获的原始图像中提取关键语义信息，将传输数据量减少90%以上，同时保留车辆通信和决策所需的核心内容。在动态车联网环境中，我们采用基于广义优势估计的近端策略优化（GAE-PPO）方法，确保在不确定性下的决策稳定性。仿真结果显示，LLAVA的注意力图能够精准聚焦相关图像区域，提升语义表示的准确性。此外，与DDPG相比，我们的传输策略将QoE提升了高达36%，并且与纯PPO相比，通过减少47%的步骤加速了收敛。进一步分析表明，调整语义符号长度在传输质量和带宽之间实现了有效权衡，当车辆数量从4辆增加到8辆时，QoE提升了高达61.4%。

> This paper investigates adaptive transmission strategies in embodied AI-enhanced vehicular networks by integrating large language models (LLMs) for semantic information extraction and deep reinforcement learning (DRL) for decision-making. The proposed framework aims to optimize both data transmission efficiency and decision accuracy by formulating an optimization problem that incorporates the Weber-Fechner law, serving as a metric for balancing bandwidth utilization and quality of experience (QoE). Specifically, we employ the large language and vision assistant (LLAVA) model to extract critical semantic information from raw image data captured by embodied AI agents (i.e., vehicles), reducing transmission data size by approximately more than 90\% while retaining essential content for vehicular communication and decision-making. In the dynamic vehicular environment, we employ a generalized advantage estimation-based proximal policy optimization (GAE-PPO) method to stabilize decision-making under uncertainty. Simulation results show that attention maps from LLAVA highlight the model's focus on relevant image regions, enhancing semantic representation accuracy. Additionally, our proposed transmission strategy improves QoE by up to 36\% compared to DDPG and accelerates convergence by reducing required steps by up to 47\% compared to pure PPO. Further analysis indicates that adapting semantic symbol length provides an effective trade-off between transmission quality and bandwidth, achieving up to a 61.4\% improvement in QoE when scaling from 4 to 8 vehicles.

[Arxiv](https://arxiv.org/abs/2501.01141)
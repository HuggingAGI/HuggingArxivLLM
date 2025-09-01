# ReST-RL：借助优化自训练与解码实现大型语言模型（LLMs）的准确代码推理

发布时间：2025年08月27日

`强化学习` `基础理论`

> ReST-RL: Achieving Accurate Code Reasoning of LLMs with Optimized Self-Training and Decoding

# 摘要

> 在提高大型语言模型（LLMs）推理准确性方面，代表性强化学习（RL）方法GRPO因奖励方差过小而效果不佳，而基于过程奖励模型（PRMs）的验证方法则在训练数据获取和验证有效性上存在难题。针对这些问题，本文提出ReST-RL——一种统一的LLM强化学习范式，它将改进的GRPO算法与价值模型（VM）辅助的精心设计的测试时解码方法相结合，显著提升了LLM的代码推理能力。作为策略强化的第一阶段，ReST-GRPO采用优化的ReST算法筛选并整合高价值训练数据，增加GRPO采样的奖励方差，进而提升训练的有效性与效率。在LLM策略的基础推理能力得到增强后，我们进一步提出VM-MCTS测试时解码优化方法：通过蒙特卡洛树搜索（MCTS）无需标注即可收集准确的价值目标，以此训练VM；解码时，借助适配的MCTS算法部署VM，提供精确的过程信号与验证分数，助力LLM策略实现高推理准确性。我们通过大量编码问题实验验证了该强化学习范式的有效性。结果显示，在不同级别的知名编码基准（如APPS、BigCodeBench和HumanEval）上，该方法显著优于其他强化训练基线（如朴素GRPO、ReST-DPO）及解码与验证基线（如PRM-BoN、ORM-MCTS），展现出增强LLM策略推理能力的强大潜力。项目代码可访问https://github.com/THUDM/ReST-RL获取。

> With respect to improving the reasoning accuracy of LLMs, the representative reinforcement learning (RL) method GRPO faces failure due to insignificant reward variance, while verification methods based on process reward models (PRMs) suffer from difficulties with training data acquisition and verification effectiveness. To tackle these problems, this paper introduces ReST-RL, a unified LLM RL paradigm that significantly improves LLM's code reasoning ability by combining an improved GRPO algorithm with a meticulously designed test time decoding method assisted by a value model (VM). As the first stage of policy reinforcement, ReST-GRPO adopts an optimized ReST algorithm to filter and assemble high-value training data, increasing the reward variance of GRPO sampling, thus improving the effectiveness and efficiency of training. After the basic reasoning ability of LLM policy has been improved, we further propose a test time decoding optimization method called VM-MCTS. Through Monte-Carlo Tree Search (MCTS), we collect accurate value targets with no annotation required, on which VM training is based. When decoding, the VM is deployed by an adapted MCTS algorithm to provide precise process signals as well as verification scores, assisting the LLM policy to achieve high reasoning accuracy. We validate the effectiveness of the proposed RL paradigm through extensive experiments on coding problems. Upon comparison, our approach significantly outperforms other reinforcement training baselines (e.g., naive GRPO and ReST-DPO), as well as decoding and verification baselines (e.g., PRM-BoN and ORM-MCTS) on well-known coding benchmarks of various levels (e.g., APPS, BigCodeBench, and HumanEval), indicating its power to strengthen the reasoning ability of LLM policies. Codes for our project can be found at https://github.com/THUDM/ReST-RL.

[Arxiv](https://arxiv.org/abs/2508.19576)
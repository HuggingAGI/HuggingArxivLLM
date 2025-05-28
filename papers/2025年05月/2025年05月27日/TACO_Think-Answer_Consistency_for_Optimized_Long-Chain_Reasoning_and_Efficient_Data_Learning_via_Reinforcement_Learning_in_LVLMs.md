# TACO：通过强化学习在大语言模型中实现思考-答案一致性的长链推理与高效数据学习

发布时间：2025年05月27日

`LLM应用` `计算机视觉`

> TACO: Think-Answer Consistency for Optimized Long-Chain Reasoning and Efficient Data Learning via Reinforcement Learning in LVLMs

# 摘要

> DeepSeek R1为大型语言模型的复杂推理带来了显著提升。尽管近期方法尝试在多模态场景中复现R1的推理能力，但它们仍存在诸多限制，包括推理与答案的不一致性、长链推理中的模型不稳定性和崩溃现象，以及数据学习效率低下的问题。为解决这些挑战，我们提出了一种全新的强化学习算法TACO，专注于视觉推理。基于广义强化策略优化（GRPO），TACO引入了思考-答案一致性机制，将推理与答案一致性紧密结合，确保答案源于深思熟虑。我们还提出了回溯重采样策略，该策略能够自适应地剔除存在问题的样本并将其重新引入采样池，从而实现稳定长链推理并为未来学习创造机会。此外，TACO采用了自适应学习计划，专注于中等难度的样本，以优化数据效率。进一步地，我们提出了测试时间分辨率缩放方案，以应对推理过程中因分辨率变化导致的性能下降问题，同时平衡计算开销。在针对REC和VQA任务的内部和外部基准测试中，大量实验表明，对LVLMs进行微调可带来显著的性能提升。


> DeepSeek R1 has significantly advanced complex reasoning for large language models (LLMs). While recent methods have attempted to replicate R1's reasoning capabilities in multimodal settings, they face limitations, including inconsistencies between reasoning and final answers, model instability and crashes during long-chain exploration, and low data learning efficiency. To address these challenges, we propose TACO, a novel reinforcement learning algorithm for visual reasoning. Building on Generalized Reinforcement Policy Optimization (GRPO), TACO introduces Think-Answer Consistency, which tightly couples reasoning with answer consistency to ensure answers are grounded in thoughtful reasoning. We also introduce the Rollback Resample Strategy, which adaptively removes problematic samples and reintroduces them to the sampler, enabling stable long-chain exploration and future learning opportunities. Additionally, TACO employs an adaptive learning schedule that focuses on moderate difficulty samples to optimize data efficiency. Furthermore, we propose the Test-Time-Resolution-Scaling scheme to address performance degradation due to varying resolutions during reasoning while balancing computational overhead. Extensive experiments on in-distribution and out-of-distribution benchmarks for REC and VQA tasks show that fine-tuning LVLMs leads to significant performance improvements.

[Arxiv](https://arxiv.org/abs/2505.20777)
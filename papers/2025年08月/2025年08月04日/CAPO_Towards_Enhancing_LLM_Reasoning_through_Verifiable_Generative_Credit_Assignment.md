# # CAPO：通过可验证的生成式信用分配迈向提升大型语言模型推理
CAPO：通过可验证的生成式信用分配迈向提升大型语言模型推理能力

发布时间：2025年08月04日

`LLM应用` `智能对话系统`

> CAPO: Towards Enhancing LLM Reasoning through Verifiable Generative Credit Assignment

# 摘要

> 强化学习结合可验证奖励（RLVR）通过基于规则的反馈提升了大型语言模型（LLMs）的推理能力，有效缓解了奖励欺骗问题。然而，现有方法将整个回应视为单一动作，给予相同奖励，导致粗粒度反馈，阻碍了模型识别成功或失败的关键步骤，影响了学习效率。PPO等方法通过价值估计分配功劳，但受限于采样，信号常不准确。而过程奖励模型虽能逐步评估，却需高质量标签且耗时。为解决这些问题，我们提出了简单高效的功劳分配策略优化（CAPO）。CAPO利用现成的通用LLM作为生成过程奖励模型（LLM-as-GenPRM），一次性生成逐步反馈，提供可验证的标记级奖励，优化原本相同规则奖励的标记。这实现了更精细的功劳分配。此外，我们采用与反馈数量成比例的投票机制，提升CAPO的准确性和鲁棒性。实验表明，CAPO在多个基准测试中表现优于现有方法。

> Reinforcement Learning with Verifiable Rewards (RLVR) has improved the reasoning abilities of Large Language Models (LLMs) by using rule-based binary feedback, helping to mitigate reward hacking. However, current RLVR methods typically treat whole responses as single actions, assigning the same reward to every token. This coarse-grained feedback hampers precise credit assignment, making it hard for models to identify which reasoning steps lead to success or failure, and often results in suboptimal policies and inefficient learning. Methods like PPO provide credit assignment through value estimation, but often yield inaccurate and unverifiable signals due to limited sampling. On the other hand, methods using Process Reward Models can provide step-by-step judgments for each reasoning step, but they require high-quality process supervision labels and are time-consuming when applied in online reinforcement learning (RL). To overcome these limitations, we introduce a simple but efficient method Credit Assignment Policy Optimization (CAPO). Given a reasoning response rollout from the policy model, CAPO directly leverages an off-the-shelf, general-purpose LLM as a Generative Process Reward Model (LLM-as-GenPRM) to generate all step-wise critique by one pass, thereby providing verifiable token-level rewards to refine the tokens that were originally assigned identical rule-based rewards. This enables more fine-grained credit assignment in an effective way. Furthermore, to enhance the accuracy and robustness of CAPO, we employ voting mechanisms that scale with the number of generated critiques. Extensive experiments using different backbones like Llama and Qwen models and in different sizes show that CAPO consistently outperforms supervised learning-based and RL-based fine-tuning methods across six challenging mathematical benchmarks and three out-of-domain benchmarks.

[Arxiv](https://arxiv.org/abs/2508.02298)
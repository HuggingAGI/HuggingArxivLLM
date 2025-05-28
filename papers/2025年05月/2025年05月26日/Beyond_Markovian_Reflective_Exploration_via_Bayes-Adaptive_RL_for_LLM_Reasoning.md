# 超越马尔可夫：大语言模型推理中的反思式探索与贝叶斯自适应强化学习

发布时间：2025年05月26日

`Agent` `人工智能` `机器学习`

> Beyond Markovian: Reflective Exploration via Bayes-Adaptive RL for LLM Reasoning

# 摘要

> 强化学习（RL）训练的大型语言模型（LLMs）展现出强大的推理能力，并涌现出反射性行为，如回溯和错误修正。然而，传统的马尔可夫强化学习将探索限制在训练阶段，仅通过当前状态依赖历史上下文，难以解释反射推理的涌现及其在测试时的优势。为解决这一问题，我们从贝叶斯自适应强化学习框架重新审视了反射探索，该框架通过在马尔可夫决策过程的后验分布下优化预期回报，自然激励了奖励开发与信息探索。我们的算法BARL指导LLM根据结果动态切换策略，为模型的反射探索提供了理论依据。实验结果显示，BARL在测试时优于传统方法，实现了更高的效率和更有效的探索。代码已开源：https://github.com/shenao-zhang/BARL。

> Large Language Models (LLMs) trained via Reinforcement Learning (RL) have exhibited strong reasoning capabilities and emergent reflective behaviors, such as backtracking and error correction. However, conventional Markovian RL confines exploration to the training phase to learn an optimal deterministic policy and depends on the history contexts only through the current state. Therefore, it remains unclear whether reflective reasoning will emerge during Markovian RL training, or why they are beneficial at test time. To remedy this, we recast reflective exploration within the Bayes-Adaptive RL framework, which explicitly optimizes the expected return under a posterior distribution over Markov decision processes. This Bayesian formulation inherently incentivizes both reward-maximizing exploitation and information-gathering exploration via belief updates. Our resulting algorithm, BARL, instructs the LLM to stitch and switch strategies based on the observed outcomes, offering principled guidance on when and how the model should reflectively explore. Empirical results on both synthetic and mathematical reasoning tasks demonstrate that BARL outperforms standard Markovian RL approaches at test time, achieving superior token efficiency with improved exploration effectiveness. Our code is available at https://github.com/shenao-zhang/BARL.

[Arxiv](https://arxiv.org/abs/2505.20561)
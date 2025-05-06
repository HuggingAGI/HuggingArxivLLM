# # 摘要
大型语言模型（LLMs）的最新进展使其能够通过奖励学习执行多种任务。这篇综述论文全面概述了奖励学习在LLMs后训练和测试时扩展中的应用。我们讨论了这一快速发展的领域中各种方法、挑战和未来方向。

发布时间：2025年05月05日

`LLM理论` `人工智能`

> Sailing AI by the Stars: A Survey of Learning from Rewards in Post-Training and Test-Time Scaling of Large Language Models

# 摘要

> 大型语言模型的发展正经历从预训练扩展向后训练及测试时的扩展转变。这一过程中，一个统一的核心范式逐渐浮现：通过奖励信号引导LLM行为的“从奖励中学习”方法。这一范式已成为强化学习（如RLHF、DPO和GRPO）、基于奖励的解码以及事后修正等技术的核心。尤为重要的是，它推动了LLMs从被动学习静态数据向主动学习动态反馈的转变，使模型具备了对齐偏好和深度推理能力。本次调查全面概述了这一范式，从训练、推理到后推理阶段，对各类策略进行了分类和深入分析。同时，我们探讨了奖励模型的基准及其主要应用场景，并指出了当前面临的挑战及未来研究方向。相关论文集合已整理在GitHub仓库：https://github.com/bobxwu/learning-from-rewards-llm-papers。

> Recent developments in Large Language Models (LLMs) have shifted from pre-training scaling to post-training and test-time scaling. Across these developments, a key unified paradigm has arisen: Learning from Rewards, where reward signals act as the guiding stars to steer LLM behavior. It has underpinned a wide range of prevalent techniques, such as reinforcement learning (in RLHF, DPO, and GRPO), reward-guided decoding, and post-hoc correction. Crucially, this paradigm enables the transition from passive learning from static data to active learning from dynamic feedback. This endows LLMs with aligned preferences and deep reasoning capabilities. In this survey, we present a comprehensive overview of the paradigm of learning from rewards. We categorize and analyze the strategies under this paradigm across training, inference, and post-inference stages. We further discuss the benchmarks for reward models and the primary applications. Finally we highlight the challenges and future directions. We maintain a paper collection at https://github.com/bobxwu/learning-from-rewards-llm-papers.

[Arxiv](https://arxiv.org/abs/2505.02686)
# GHPO：为稳定高效的大语言模型强化学习提供自适应指导

发布时间：2025年07月16日

`LLM理论` `人工智能`

> GHPO: Adaptive Guidance for Stable and Efficient LLM Reinforcement Learning

# 摘要

> 可验证奖励的强化学习（RLVR）作为一种新兴的强大范式，正在推动大型语言模型（LLMs）在复杂推理任务领域的自我改进。然而，现有的基于策略的强化学习方法常常面临训练不稳定和效率低下的问题。这主要是因为模型能力与任务难度的不匹配，导致训练数据的复杂性超出了模型的当前能力范围，进而引发奖励信号稀疏和学习停滞。这一问题在资源效率更高的小型LLMs中尤为突出。为了解决这一难题，我们提出了引导式混合策略优化（GHPO），一种新型的难度感知强化学习框架。GHPO通过自适应提示优化动态调整任务难度，提供针对性指导。这种方法巧妙地平衡了直接模仿学习（针对当前模型能力范围之外的问题）和基于探索的强化学习（针对更易处理的任务），从而构建了一个平滑且优化的学习课程。实验结果表明，GHPO在六个具有挑战性的数学基准测试中平均性能提升了约5%，并始终优于强大的基于策略的强化学习和课程学习基线。进一步分析证实，我们的框架显著提升了训练稳定性和最终推理性能，为开发强大且鲁棒的推理模型提供了一种可扩展且高效的解决方案。

> Reinforcement Learning with Verifiable Rewards (RLVR) has recently emerged as a powerful paradigm for facilitating the self-improvement of large language models (LLMs), particularly in the domain of complex reasoning tasks. However, prevailing on-policy RL methods often contend with significant training instability and inefficiency. This is primarily due to a capacity-difficulty mismatch, where the complexity of training data frequently outpaces the model's current capabilities, leading to critically sparse reward signals and stalled learning progress. This challenge is particularly acute for smaller, more resource-efficient LLMs. To overcome this, we introduce the Guided Hybrid Policy Optimization (GHPO), a novel difficulty-aware reinforcement learning framework. GHPO dynamically calibrates task difficulty by employing adaptive prompt refinement to provide targeted guidance. This unique approach adaptively balances direct imitation learning for problems currently beyond the model's reach with exploration-based reinforcement learning for more manageable tasks, effectively creating a smooth and optimized learning curriculum. Extensive experiments demonstrate that GHPO achieves an average performance gain of approximately 5% across six challenging mathematics benchmarks, consistently outperforming strong on-policy reinforcement learning and curriculum learning baselines. Further analysis confirms that our framework significantly enhances both training stability and final reasoning performance, thus offering a scalable and efficient solution for developing powerful and robust reasoning models.

[Arxiv](https://arxiv.org/abs/2507.10628)
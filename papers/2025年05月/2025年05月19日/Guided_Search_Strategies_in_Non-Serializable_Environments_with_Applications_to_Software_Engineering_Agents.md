# 不可串行环境中的引导搜索策略及其在软件工程代理中的应用

发布时间：2025年05月19日

`Agent` `智能体软件工程` `软件工程`

> Guided Search Strategies in Non-Serializable Environments with Applications to Software Engineering Agents

# 摘要

> 大型语言模型（LLMs）在数学推理和智能体软件工程等复杂多步骤任务中表现卓越。然而，它们在多次解决方案尝试中常难以保持一致性能。为缩小平均与最佳性能差距，引导式测试时间搜索通过探索多路径识别最优解。然而，如MCTS等有效搜索技术常不适合非串行化的强化学习环境，例如Docker容器，其中状态保存与恢复困难。我们研究了两种适用于此类环境的互补策略：一步前瞻与轨迹选择，均由基于学习的动作-价值函数估计器引导。在智能体软件工程的关键测试平台SWE-bench Verified上，这些方法使微调后的Qwen-72B模型成功率翻倍至40.8%，成为开放权重模型的新标杆。此外，这些技术亦可迁移至如GPT-4o等先进闭源模型，同样显著提升性能。

> Large language models (LLMs) have recently achieved remarkable results in complex multi-step tasks, such as mathematical reasoning and agentic software engineering. However, they often struggle to maintain consistent performance across multiple solution attempts. One effective approach to narrow the gap between average-case and best-case performance is guided test-time search, which explores multiple solution paths to identify the most promising one. Unfortunately, effective search techniques (e.g. MCTS) are often unsuitable for non-serializable RL environments, such as Docker containers, where intermediate environment states cannot be easily saved and restored. We investigate two complementary search strategies applicable to such environments: 1-step lookahead and trajectory selection, both guided by a learned action-value function estimator. On the SWE-bench Verified benchmark, a key testbed for agentic software engineering, we find these methods to double the average success rate of a fine-tuned Qwen-72B model, achieving 40.8%, the new state-of-the-art for open-weights models. Additionally, we show that these techniques are transferable to more advanced closed models, yielding similar improvements with GPT-4o.

[Arxiv](https://arxiv.org/abs/2505.13652)
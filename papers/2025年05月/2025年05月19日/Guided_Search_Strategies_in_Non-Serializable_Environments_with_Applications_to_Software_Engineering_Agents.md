# # 有指导的搜索策略在不可序列化环境中的应用——软件工程代理的研究

发布时间：2025年05月19日

`LLM应用` `智能体软件工程`

> Guided Search Strategies in Non-Serializable Environments with Applications to Software Engineering Agents

# 摘要

> 大型语言模型（LLMs）在数学推理和智能体软件工程等复杂多步骤任务中表现出色，但往往难以在多次尝试中保持稳定性能。为缩小平均与最佳性能差距，我们采用引导式测试时间搜索方法，通过探索多路径寻找最优解。然而，传统搜索技术（如MCTS）难以在非序列化强化学习环境（如Docker容器）中应用，因其无法轻松保存和恢复中间状态。针对这一挑战，我们提出两种互补策略：1步展望与轨迹选择，均由学习的动作值函数估计器引导。在智能体软件工程的关键测试平台SWE-bench Verified上，这些方法使Qwen-72B模型的平均成功率翻倍至40.8%，成为开放权重模型的新标杆。此外，这些技术同样适用于更先进的闭源模型如GPT-4o，带来相似性能提升。

> Large language models (LLMs) have recently achieved remarkable results in complex multi-step tasks, such as mathematical reasoning and agentic software engineering. However, they often struggle to maintain consistent performance across multiple solution attempts. One effective approach to narrow the gap between average-case and best-case performance is guided test-time search, which explores multiple solution paths to identify the most promising one. Unfortunately, effective search techniques (e.g. MCTS) are often unsuitable for non-serializable RL environments, such as Docker containers, where intermediate environment states cannot be easily saved and restored. We investigate two complementary search strategies applicable to such environments: 1-step lookahead and trajectory selection, both guided by a learned action-value function estimator. On the SWE-bench Verified benchmark, a key testbed for agentic software engineering, we find these methods to double the average success rate of a fine-tuned Qwen-72B model, achieving 40.8%, the new state-of-the-art for open-weights models. Additionally, we show that these techniques are transferable to more advanced closed models, yielding similar improvements with GPT-4o.

[Arxiv](https://arxiv.org/abs/2505.13652)
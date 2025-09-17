# Tool-R1：面向智能体工具使用的样本高效强化学习

发布时间：2025年09月16日

`强化学习` `基础理论`

> Tool-R1: Sample-Efficient Reinforcement Learning for Agentic Tool Use

# 摘要

> 大型语言模型（LLMs）虽已展现出强大的语言理解与推理能力，但在处理需要最新知识、精确操作或专业工具使用的现实任务时仍存在局限。为此，我们提出Tool-R1——一个强化学习框架，它通过生成可执行Python代码，让LLMs能够实现通用、组合式且多步骤的工具调用。Tool-R1支持集成用户自定义工具和标准库，并通过跨步骤变量共享构建连贯的工作流。我们设计了基于结果的奖励函数，结合LLM的答案判断与代码执行成功情况，指导策略优化。为提升训练效率，我们维护动态样本队列以缓存和重用高质量轨迹，从而减少昂贵的在线采样开销。在GAIA基准测试中，Tool-R1显著提升了准确性和鲁棒性，相较强基线模型实现约10%的性能增益，在复杂多步骤任务上的改进更为明显。这些结果充分彰显了Tool-R1在现实应用中实现可靠高效工具增强推理的潜力。我们的代码将在https://github.com/YBYBZhang/Tool-R1上开源。

> Large language models (LLMs) have demonstrated strong capabilities in language understanding and reasoning, yet they remain limited when tackling real-world tasks that require up-to-date knowledge, precise operations, or specialized tool use. To address this, we propose Tool-R1, a reinforcement learning framework that enables LLMs to perform general, compositional, and multi-step tool use by generating executable Python code. Tool-R1 supports integration of user-defined tools and standard libraries, with variable sharing across steps to construct coherent workflows. An outcome-based reward function, combining LLM-based answer judgment and code execution success, guides policy optimization. To improve training efficiency, we maintain a dynamic sample queue to cache and reuse high-quality trajectories, reducing the overhead of costly online sampling. Experiments on the GAIA benchmark show that Tool-R1 substantially improves both accuracy and robustness, achieving about 10\% gain over strong baselines, with larger improvements on complex multi-step tasks. These results highlight the potential of Tool-R1 for enabling reliable and efficient tool-augmented reasoning in real-world applications. Our code will be available at https://github.com/YBYBZhang/Tool-R1.

[Arxiv](https://arxiv.org/abs/2509.12867)
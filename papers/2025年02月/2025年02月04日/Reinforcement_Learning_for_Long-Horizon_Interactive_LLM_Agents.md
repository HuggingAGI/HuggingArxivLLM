# 长时程交互式LLM智能体的强化学习

发布时间：2025年02月04日

`Agent

理由：这篇论文主要讨论了交互式数字代理（IDAs）在复杂环境中的训练和优化，特别是通过强化学习（RL）方法来提高代理在多步交互任务中的表现。论文的核心内容围绕如何训练和改进代理的行为，使其能够在有状态、多领域、多应用的环境中更好地执行任务。因此，这篇论文应归类为Agent。` `人机交互`

> Reinforcement Learning for Long-Horizon Interactive LLM Agents

# 摘要

> # 摘要
交互式数字代理（IDAs）通过调用有状态数字环境的API来响应用户请求并执行任务。尽管基于指令调优的大型语言模型（LLMs）的IDAs能够在多步交互中对接口调用的反馈做出反应，但它们并未在各自的数字环境中进行过训练。此前的方法在复杂基准测试（如AppWorld）中仅能完成不到一半的任务。我们提出了一种强化学习（RL）方法，直接在目标环境中训练IDAs。我们将这一训练过程形式化为部分可观测的马尔可夫决策过程，并开发了LOOP——一种数据与内存高效的近端策略优化变体。LOOP无需价值网络，且内存中仅保留一份底层LLM的副本，使其实现简单且内存效率与微调单个LLM相当。在AppWorld环境中，使用LOOP训练的320亿参数代理比更大的OpenAI o1代理高出9个百分点（相对15%）。据我们所知，这是首次将RL应用于通过直接API调用与有状态、多领域、多应用环境交互的IDAs。我们的分析揭示了RL在这一领域的有效性，表明代理学会了查阅API文档、避免无根据的假设、减少虚构内容，并能够从挫折中恢复。

> Interactive digital agents (IDAs) leverage APIs of stateful digital environments to perform tasks in response to user requests. While IDAs powered by instruction-tuned large language models (LLMs) can react to feedback from interface invocations in multi-step exchanges, they have not been trained in their respective digital environments. Prior methods accomplish less than half of tasks in sophisticated benchmarks such as AppWorld. We present a reinforcement learning (RL) approach that trains IDAs directly in their target environments. We formalize this training as a partially observable Markov decision process and derive LOOP, a data- and memory-efficient variant of proximal policy optimization. LOOP uses no value network and maintains exactly one copy of the underlying LLM in memory, making its implementation straightforward and as memory-efficient as fine-tuning a single LLM. A 32-billion-parameter agent trained with LOOP in the AppWorld environment outperforms the much larger OpenAI o1 agent by 9 percentage points (15% relative). To our knowledge, this is the first reported application of RL to IDAs that interact with a stateful, multi-domain, multi-app environment via direct API calls. Our analysis sheds light on the effectiveness of RL in this area, showing that the agent learns to consult the API documentation, avoid unwarranted assumptions, minimize confabulation, and recover from setbacks.

[Arxiv](https://arxiv.org/abs/2502.01600)
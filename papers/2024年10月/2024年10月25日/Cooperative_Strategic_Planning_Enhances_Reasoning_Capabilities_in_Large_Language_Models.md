# 合作战略规划提升大型语言模型的推理能力

发布时间：2024年10月25日

`Agent` `多智能体`

> Cooperative Strategic Planning Enhances Reasoning Capabilities in Large Language Models

# 摘要

> 增强大型语言模型（LLMs）的推理能力对其解决复杂多步骤问题至关重要。多智能体框架在提升LLMs推理能力上潜力巨大。但LLM智能体间缺乏有效合作，这尤其影响了多步骤推理任务的性能。本文提出一种新颖的合作多智能体推理框架（CoPlanner），通过分离推理步骤并给不同智能体分配不同职责。CoPlanner由两个LLM智能体构成：规划智能体和推理智能体。规划智能体提供高层战略提示，推理智能体遵循提示推断答案。通过在交互式推理过程中用近端策略优化（PPO）训练规划智能体的策略，基于LLaMA-3-8B的CoPlanner在LogiQA上的表现比之前最佳方法高9.94%，在BBH上高3.09%。我们的结果表明，规划智能体的引导以及智能体间的有效合作助力CoPlanner在解决多步骤推理问题时表现卓越。

> Enhancing the reasoning capabilities of large language models (LLMs) is crucial for enabling them to tackle complex, multi-step problems. Multi-agent frameworks have shown great potential in enhancing LLMs' reasoning capabilities. However, the lack of effective cooperation between LLM agents hinders their performance, especially for multi-step reasoning tasks. This paper proposes a novel cooperative multi-agent reasoning framework (CoPlanner) by separating reasoning steps and assigning distinct duties to different agents. CoPlanner consists of two LLM agents: a planning agent and a reasoning agent. The planning agent provides high-level strategic hints, while the reasoning agent follows these hints and infers answers. By training the planning agent's policy through the interactive reasoning process via Proximal Policy Optimization (PPO), the LLaMA-3-8B-based CoPlanner outperforms the previous best method by 9.94\% on LogiQA and 3.09\% on BBH. Our results demonstrate that the guidance from the planning agent and the effective cooperation between the agents contribute to the superior performance of CoPlanner in tackling multi-step reasoning problems.

[Arxiv](https://arxiv.org/abs/2410.20007)
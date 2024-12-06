# MISR：对前沿模型中的工具性自我推理进行测量

发布时间：2024年12月05日

`Agent` `语言模型` `人工智能`

> MISR: Measuring Instrumental Self-Reasoning in Frontier Models

# 摘要

> 我们提出一系列任务，以评估大型语言模型（LLM）代理的工具性自我推理能力。工具性自我推理能力能提升适应性并实现自我修正，不过也可能带来重大风险，比如达成欺骗性对齐。此前的工作仅在非代理情境或有限领域中评估了自我推理。在本文里，我们针对广泛场景中的代理任务，提出了对工具性自我推理能力的评估，涵盖自我修改、知识寻求和不透明的自我推理。我们对使用最先进的LLM构建的代理进行了评估，包括商业和开源系统。我们发现工具性自我推理能力仅在最强大的前沿模型中显现，且高度依赖于上下文。没有模型能通过我们评估的最难版本，所以我们的评估可用于衡量未来模型中工具性自我推理能力的增长。我们在 https://github.com/kaifronsdal/Self-Reasoning-Evals 开源了我们的评估。

> We propose a suite of tasks to evaluate the instrumental self-reasoning ability of large language model (LLM) agents. Instrumental self-reasoning ability could improve adaptability and enable self-modification, but it could also pose significant risks, such as enabling deceptive alignment. Prior work has only evaluated self-reasoning in non-agentic settings or in limited domains. In this paper, we propose evaluations for instrumental self-reasoning ability in agentic tasks in a wide range of scenarios, including self-modification, knowledge seeking, and opaque self-reasoning. We evaluate agents built using state-of-the-art LLMs, including commercial and open source systems. We find that instrumental self-reasoning ability emerges only in the most capable frontier models and that it is highly context-dependent. No model passes the the most difficult versions of our evaluations, hence our evaluation can be used to measure increases in instrumental self-reasoning ability in future models. We open-source our evaluations at https://github.com/kaifronsdal/Self-Reasoning-Evals.

[Arxiv](https://arxiv.org/abs/2412.03904)
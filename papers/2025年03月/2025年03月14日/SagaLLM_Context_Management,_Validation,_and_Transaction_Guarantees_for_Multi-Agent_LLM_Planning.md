# # SagaLLM：针对多智能体 LLM 规划的上下文管理、验证及事务保证

发布时间：2025年03月14日

`Agent` `人工智能` `自动化`

> SagaLLM: Context Management, Validation, and Transaction Guarantees for Multi-Agent LLM Planning

# 摘要

> 近期，基于LLM的代理框架在任务委托和工作流程编排方面表现优异，但保持上下文感知和规划一致性仍面临挑战。本文提出SagaLLM，一个结构化的多代理框架，旨在解决当前LLM方法的四大局限：自我验证不足、上下文变窄、缺乏事务属性以及代理间协调不力。通过引入专门的上下文管理代理和验证协议，SagaLLM在复杂规划过程中全程保留关键约束和状态信息，确保即使在中断情况下也能实现稳健且一致的决策。我们通过REALM基准中的精选问题评估了SagaLLM，重点关注挑战上下文保留和自适应推理的顺序及反应式规划场景。实验结果显示，尽管Claude 3.7、DeepSeek R1、GPT-4o和GPT-o1等先进LLM展现出卓越的推理能力，但在复杂规划任务中维持全局约束意识方面仍存在困难，尤其是在应对意外变化时。而SagaLLM的分布式认知架构在规划一致性、约束执行和适应中断方面展现出显著优势。

> Recent LLM-based agent frameworks have demonstrated impressive capabilities in task delegation and workflow orchestration, but face significant challenges in maintaining context awareness and ensuring planning consistency. This paper presents SagaLLM, a structured multi-agent framework that addresses four fundamental limitations in current LLM approaches: inadequate self-validation, context narrowing, lacking transaction properties, and insufficient inter-agent coordination. By implementing specialized context management agents and validation protocols, SagaLLM preserves critical constraints and state information throughout complex planning processes, enabling robust and consistent decision-making even during disruptions. We evaluate our approach using selected problems from the REALM benchmark, focusing on sequential and reactive planning scenarios that challenge both context retention and adaptive reasoning. Our experiments with state-of-the-art LLMs, Claude 3.7, DeepSeek R1, GPT-4o, and GPT-o1, demonstrate that while these models exhibit impressive reasoning capabilities, they struggle with maintaining global constraint awareness during complex planning tasks, particularly when adapting to unexpected changes. In contrast, the distributed cognitive architecture of SagaLLM shows significant improvements in planning consistency, constraint enforcement, and adaptation to disruptions in various scenarios.

[Arxiv](https://arxiv.org/abs/2503.11951)
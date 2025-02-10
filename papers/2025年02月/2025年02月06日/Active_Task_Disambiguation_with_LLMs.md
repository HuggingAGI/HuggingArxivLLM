# # Active Task Disambiguation with LLMs
LLMs助力主动任务消歧。

发布时间：2025年02月06日

`LLM应用

理由：这篇论文探讨了大型语言模型在处理任务模糊性方面的能力，并提出了一种主动任务消除模糊性方法，属于LLM的应用层面研究。` `任务管理` `人工智能`

> Active Task Disambiguation with LLMs

# 摘要

> 尽管大型语言模型（LLMs）在各类基准测试中表现卓越，但其在处理现实交互中常见的模糊性问题方面的能力仍有待深入探索。为此，我们提出了任务模糊性的正式定义，并通过贝叶斯实验设计的视角重新审视了任务消除模糊性问题。通过提出澄清问题，LLM智能体能够逐步获取更多任务细节，缩小可行解决方案的范围，从而降低生成不理想输出的可能性。然而，生成有效澄清问题需要LLM智能体具备元认知推理能力，而这可能是当前LLMs尚未完全掌握的技能。我们提出的主动任务消除模糊性方法，使LLM智能体能够生成最大化信息增益的针对性问题。这种方法实质上将推理负担从对解决方案空间的隐式推理转移到了显式推理。实证结果表明，相较于仅在问题空间内进行推理的方法，这种问题选择策略能够实现更高效的任务消除模糊性效果。

> Despite the impressive performance of large language models (LLMs) across various benchmarks, their ability to address ambiguously specified problems--frequent in real-world interactions--remains underexplored. To address this gap, we introduce a formal definition of task ambiguity and frame the problem of task disambiguation through the lens of Bayesian Experimental Design. By posing clarifying questions, LLM agents can acquire additional task specifications, progressively narrowing the space of viable solutions and reducing the risk of generating unsatisfactory outputs. Yet, generating effective clarifying questions requires LLM agents to engage in a form of meta-cognitive reasoning, an ability LLMs may presently lack. Our proposed approach of active task disambiguation enables LLM agents to generate targeted questions maximizing the information gain. Effectively, this approach shifts the load from implicit to explicit reasoning about the space of viable solutions. Empirical results demonstrate that this form of question selection leads to more effective task disambiguation in comparison to approaches relying on reasoning solely within the space of questions.

[Arxiv](https://arxiv.org/abs/2502.04485)
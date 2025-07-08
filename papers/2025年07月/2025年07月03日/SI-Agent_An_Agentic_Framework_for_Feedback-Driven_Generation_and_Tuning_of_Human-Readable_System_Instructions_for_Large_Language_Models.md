# # SI-Agent：面向大型语言模型的智能反馈式系统指令生成与调优框架

发布时间：2025年07月03日

`Agent` `人工智能` `计算机科学`

> SI-Agent: An Agentic Framework for Feedback-Driven Generation and Tuning of Human-Readable System Instructions for Large Language Models

# 摘要

> 系统指令（SIs）是指导大型语言模型（LLMs）的核心要素，但手动设计不仅耗时费力，效果也常不尽如人意。现有的自动化方法多生成难以理解的“软提示”，以牺牲可解释性为代价。本文提出SI-Agent，一种创新的智能体框架，通过反馈驱动的循环，自动创建并持续优化可读的系统指令。SI-Agent由三个协作智能体组成：指导者、指令执行者（目标LLM）以及反馈/奖励评估者，后者不仅评估任务表现，还可选评估SI的可读性。该框架采用迭代优化流程，利用反馈信息指导改进策略，如基于LLM的编辑或进化算法。本文详细介绍了框架架构、智能体角色及迭代优化机制，并与现有方法进行对比。实验结果证实了SI-Agent的有效性，其在任务表现、可读性及效率等关键指标上均表现优异。研究发现，SI-Agent生成的系统指令不仅有效且易于理解，在性能与可解释性之间实现了优于传统方法的平衡。这项研究不仅推动了LLM定制的民主化，还为提升模型透明度提供了新思路。当然，计算成本和反馈可靠性等挑战仍需进一步探索。

> System Instructions (SIs), or system prompts, are pivotal for guiding Large Language Models (LLMs) but manual crafting is resource-intensive and often suboptimal. Existing automated methods frequently generate non-human-readable "soft prompts," sacrificing interpretability. This paper introduces SI-Agent, a novel agentic framework designed to automatically generate and iteratively refine human-readable SIs through a feedback-driven loop. SI-Agent employs three collaborating agents: an Instructor Agent, an Instruction Follower Agent (target LLM), and a Feedback/Reward Agent evaluating task performance and optionally SI readability. The framework utilizes iterative cycles where feedback guides the Instructor's refinement strategy (e.g., LLM-based editing, evolutionary algorithms). We detail the framework's architecture, agent roles, the iterative refinement process, and contrast it with existing methods. We present experimental results validating SI-Agent's effectiveness, focusing on metrics for task performance, SI readability, and efficiency. Our findings indicate that SI-Agent generates effective, readable SIs, offering a favorable trade-off between performance and interpretability compared to baselines. Potential implications include democratizing LLM customization and enhancing model transparency. Challenges related to computational cost and feedback reliability are acknowledged.

[Arxiv](https://arxiv.org/abs/2507.03223)
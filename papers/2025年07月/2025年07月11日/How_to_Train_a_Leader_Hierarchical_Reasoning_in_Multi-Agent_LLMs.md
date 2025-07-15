# 训练领导者的方法：多智能体LLM中的层级推理

发布时间：2025年07月11日

`Agent` `人工智能` `机器人学`

> How to Train a Leader: Hierarchical Reasoning in Multi-Agent LLMs

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中表现优异，但结合多个模型的互补优势往往能进一步提升性能。尽管多智能体框架可以通过利用多个LLMs来提高解决方案质量，但现有方法在训练和推理阶段的计算开销通常都很高。在本研究中，我们提出了一种分层多智能体框架，通过仅训练一个领导者LLM来协调一支未经训练的同伴智能体团队，从而解决这些挑战。为此，我们提出了多智能体引导的领导者策略优化方法MLPO，这是一种无需辅助价值网络或显式智能体反馈的新型训练方式，领导者通过该方法可以评估和综合智能体的响应。使用MLPO训练的领导者不仅在与智能体团队进行推理时表现出色，即使在没有团队的单智能体部署中也能获得更好的性能。在Big-Bench Hard (BBH)、MATH和MMLU上的实验证明，我们的框架在性能上显著优于单智能体和多智能体基线。实验结果凸显了在多智能体LLM系统中，通过训练一个灵活的领导者来实现协作推理的有效性和高效性。


> Large Language Models (LLMs) have achieved strong performance on a wide range of complex reasoning tasks, yet further gains are often possible by leveraging the complementary strengths of multiple models. While multi-agent frameworks can improve solution quality by leveraging multiple LLMs, existing methods are often computationally expensive, both at training and inference time. In this work, we introduce a hierarchical multi-agent framework that addresses these challenges by training only a single leader LLM to coordinate a team of untrained peer agents. To this end, we propose Multi-agent guided Leader Policy \textbf{O}ptimization (MLPO), a novel approach which trains the leader to evaluate and synthesize agent responses without auxiliary value networks or explicit agent feedback. Leaders trained with MLPO exhibit improved performance not only when interacting with the agent team at inference time, but also enjoy improved performance when deployed in single-agent settings without the team. Empirical results on Big-Bench Hard (BBH), MATH, and MMLU demonstrate that our framework achieves substantial performance improvements over both single-agent and multi-agent baselines. Our results highlight the effectiveness and efficiency of training a single, flexible leader for collaborative reasoning in multi-agent LLM systems.

[Arxiv](https://arxiv.org/abs/2507.08960)
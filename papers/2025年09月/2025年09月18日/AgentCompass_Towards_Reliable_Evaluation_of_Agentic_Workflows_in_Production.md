# AgentCompass：迈向生产环境下智能体工作流的可靠评估

发布时间：2025年09月18日

`Agent` `工业与制造`

> AgentCompass: Towards Reliable Evaluation of Agentic Workflows in Production

# 摘要

> 随着大型语言模型（LLMs）在自动化复杂多智能体工作流中的应用日益广泛，组织面临的风险也不断攀升——错误、涌现行为及系统性故障等问题，都是当前评估方法难以捕捉的。为此，我们提出AgentCompass——首个专为智能体工作流部署后监控与调试设计的评估框架。AgentCompass通过结构化的多阶段分析流程模拟专家调试逻辑，具体包括：错误识别与分类、主题聚类、定量评分及策略总结。该框架还配备了情景记忆与语义记忆双系统，能跨多次执行实现持续学习，进一步提升了性能。通过与设计合作伙伴的协作，我们在真实部署场景中验证了其实际价值，并在公开的TRAIL基准测试中证明了其有效性。实验表明，AgentCompass不仅在关键指标上达到了最先进水平，还能发现人类标注中遗漏的关键问题，充分彰显了其作为生产环境中智能体系统可靠监控与优化工具的核心价值——既强大又贴近开发者需求。

> With the growing adoption of Large Language Models (LLMs) in automating complex, multi-agent workflows, organizations face mounting risks from errors, emergent behaviors, and systemic failures that current evaluation methods fail to capture. We present AgentCompass, the first evaluation framework designed specifically for post-deployment monitoring and debugging of agentic workflows. AgentCompass models the reasoning process of expert debuggers through a structured, multi-stage analytical pipeline: error identification and categorization, thematic clustering, quantitative scoring, and strategic summarization. The framework is further enhanced with a dual memory system-episodic and semantic-that enables continual learning across executions. Through collaborations with design partners, we demonstrate the framework's practical utility on real-world deployments, before establishing its efficacy against the publicly available TRAIL benchmark. AgentCompass achieves state-of-the-art results on key metrics, while uncovering critical issues missed in human annotations, underscoring its role as a robust, developer-centric tool for reliable monitoring and improvement of agentic systems in production.

[Arxiv](https://arxiv.org/abs/2509.14647)
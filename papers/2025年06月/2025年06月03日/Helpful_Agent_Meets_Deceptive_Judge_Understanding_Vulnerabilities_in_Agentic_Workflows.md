# # 帮助型智能体与欺骗性裁判：理解智能体工作流中的漏洞
善意的智能体与欺骗性的裁判相遇：探索智能体工作流中的潜在风险

发布时间：2025年06月03日

`Agent` `人工智能` `人机交互`

> Helpful Agent Meets Deceptive Judge: Understanding Vulnerabilities in Agentic Workflows

# 摘要

> 智能体工作流——多个大型语言模型 (LLM) 实例通过交互解决问题——越来越多地基于反馈机制构建，其中一个模型对另一个模型进行评估和批评。尽管基于反馈的改进机制具有潜力，但智能体工作流的稳定性取决于评估者的可靠性。然而，评估者可能会编造信息、表现出偏见或采取对抗行为——在工作流中引入关键漏洞。

在本研究中，我们对欺骗性或误导性反馈下的智能体工作流进行了系统性分析。我们引入了一个二维框架，用于从意图（从建设性到恶意）和知识（从仅参数化到检索增强系统）两个维度分析评估者的行为。借助这一分类法，我们构建了一系列评估者行为，并开发了 WAFER-QA，这是一个新的基准测试，通过基于检索的网络证据进行批评，以评估智能体工作流在事实支持的对抗性反馈下的鲁棒性。

我们发现，即使是最强大的智能体也容易受到具有说服力但存在缺陷的批评的影响——在误导性反馈的单一轮次后，它们经常改变正确答案。更进一步，我们研究了模型预测在多次交互轮次中的演变，揭示了推理模型和非推理模型之间的不同行为模式。我们的发现突显了基于反馈的工作流中的根本性漏洞，并为构建更 robust 的智能体系统提供了指导。


> Agentic workflows -- where multiple large language model (LLM) instances interact to solve tasks -- are increasingly built on feedback mechanisms, where one model evaluates and critiques another. Despite the promise of feedback-driven improvement, the stability of agentic workflows rests on the reliability of the judge. However, judges may hallucinate information, exhibit bias, or act adversarially -- introducing critical vulnerabilities into the workflow. In this work, we present a systematic analysis of agentic workflows under deceptive or misleading feedback. We introduce a two-dimensional framework for analyzing judge behavior, along axes of intent (from constructive to malicious) and knowledge (from parametric-only to retrieval-augmented systems). Using this taxonomy, we construct a suite of judge behaviors and develop WAFER-QA, a new benchmark with critiques grounded in retrieved web evidence to evaluate robustness of agentic workflows against factually supported adversarial feedback. We reveal that even strongest agents are vulnerable to persuasive yet flawed critiques -- often switching correct answers after a single round of misleading feedback. Taking a step further, we study how model predictions evolve over multiple rounds of interaction, revealing distinct behavioral patterns between reasoning and non-reasoning models. Our findings highlight fundamental vulnerabilities in feedback-based workflows and offer guidance for building more robust agentic systems.

[Arxiv](https://arxiv.org/abs/2506.03332)
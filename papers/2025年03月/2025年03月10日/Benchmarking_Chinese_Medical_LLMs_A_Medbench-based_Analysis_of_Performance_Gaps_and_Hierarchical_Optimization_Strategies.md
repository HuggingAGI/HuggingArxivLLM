# 基于Medbench的中文医疗LLMs性能差距分析及分层优化策略研究

发布时间：2025年03月10日

`LLM应用` `人工智能`

> Benchmarking Chinese Medical LLMs: A Medbench-based Analysis of Performance Gaps and Hierarchical Optimization Strategies

# 摘要

> 医疗大语言模型（LLMs）的评估与优化对其实际应用至关重要，特别是在保障准确性、安全性及伦理对齐方面。现有评估框架未能充分解析领域特定的错误模式，也未能有效应对跨模态挑战。本研究通过对MedBench平台上表现优异的10个模型进行系统性分析，提出了一种细致的错误分类法，将错误响应分为八大类：遗漏、幻觉、格式不符、因果推理不足、上下文不一致、未回答、输出错误以及医学语言生成缺陷。对10个领先模型的评估揭示了其脆弱性：尽管在医学知识召回方面达到了0.86的准确率，但在关键推理任务中却出现了96.3%的遗漏现象，而安全伦理评估则暴露出令人担忧的不一致性（在选项打乱的情况下，稳健性得分为0.79）。我们的分析进一步揭示了模型在知识边界执行和多步骤推理方面的系统性弱点。针对这些问题，我们提出了一种分层优化策略，涵盖提示工程和知识增强检索、混合神经符号架构以及因果推理框架四个层面。这项研究为开发临床稳健的LLMs提供了切实可行的发展路线图，同时通过以错误为导向的洞察重新定义了评估范式，最终推动了AI在高风险医疗环境中安全性和可靠性的提升。


> The evaluation and improvement of medical large language models (LLMs) are critical for their real-world deployment, particularly in ensuring accuracy, safety, and ethical alignment. Existing frameworks inadequately dissect domain-specific error patterns or address cross-modal challenges. This study introduces a granular error taxonomy through systematic analysis of top 10 models on MedBench, categorizing incorrect responses into eight types: Omissions, Hallucination, Format Mismatch, Causal Reasoning Deficiency, Contextual Inconsistency, Unanswered, Output Error, and Deficiency in Medical Language Generation. Evaluation of 10 leading models reveals vulnerabilities: despite achieving 0.86 accuracy in medical knowledge recall, critical reasoning tasks show 96.3% omission, while safety ethics evaluations expose alarming inconsistency (robustness score: 0.79) under option shuffled. Our analysis uncovers systemic weaknesses in knowledge boundary enforcement and multi-step reasoning. To address these, we propose a tiered optimization strategy spanning four levels, from prompt engineering and knowledge-augmented retrieval to hybrid neuro-symbolic architectures and causal reasoning frameworks. This work establishes an actionable roadmap for developing clinically robust LLMs while redefining evaluation paradigms through error-driven insights, ultimately advancing the safety and trustworthiness of AI in high-stakes medical environments.

[Arxiv](https://arxiv.org/abs/2503.07306)
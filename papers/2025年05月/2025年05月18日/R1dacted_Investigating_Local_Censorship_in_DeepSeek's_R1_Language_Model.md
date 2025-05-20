# R1dacted：探索 DeepSeek R1 语言模型中的本地审查机制

发布时间：2025年05月18日

`LLM应用` `人工智能治理` `模型伦理`

> R1dacted: Investigating Local Censorship in DeepSeek's R1 Language Model

# 摘要

> 深度求索公司近期发布了R1，一款专为推理任务优化的高性能大型语言模型。尽管R1拥有高效的训练流程，它在多个基准测试中展现出与领先推理模型（如OpenAI的o1）相当甚至更优的性能。然而，有新兴报告显示，R1拒绝回答与中国政治敏感话题相关的某些提示。虽然现有LLMs通常会实施安全措施以避免生成有害或冒犯性内容，但R1表现出了一种显著的不同——对政治敏感查询采取类似审查的行为。本文通过首先介绍一个大规模的、经过严格筛选的提示集合来研究这一现象，这些提示会被R1审查，涉及多种政治敏感话题，但不会被其他模型审查。接着，我们对R1的审查模式进行了全面分析，探讨其一致性、触发条件以及在主题、提示措辞和上下文中的变化。除了英语查询，我们还探索了其他语言的审查行为。此外，我们还研究了审查行为在从R1语言模型蒸馏出的其他模型中的可转移性。最后，我们提出了绕过或移除这种审查的技术。我们的研究发现揭示了可能的额外审查机制，这些机制可能是在训练或对齐过程中由设计选择所决定的，这引发了关于语言模型部署透明度、偏见和治理方面的担忧。

> DeepSeek recently released R1, a high-performing large language model (LLM) optimized for reasoning tasks. Despite its efficient training pipeline, R1 achieves competitive performance, even surpassing leading reasoning models like OpenAI's o1 on several benchmarks. However, emerging reports suggest that R1 refuses to answer certain prompts related to politically sensitive topics in China. While existing LLMs often implement safeguards to avoid generating harmful or offensive outputs, R1 represents a notable shift - exhibiting censorship-like behavior on politically charged queries. In this paper, we investigate this phenomenon by first introducing a large-scale set of heavily curated prompts that get censored by R1, covering a range of politically sensitive topics, but are not censored by other models. We then conduct a comprehensive analysis of R1's censorship patterns, examining their consistency, triggers, and variations across topics, prompt phrasing, and context. Beyond English-language queries, we explore censorship behavior in other languages. We also investigate the transferability of censorship to models distilled from the R1 language model. Finally, we propose techniques for bypassing or removing this censorship. Our findings reveal possible additional censorship integration likely shaped by design choices during training or alignment, raising concerns about transparency, bias, and governance in language model deployment.

[Arxiv](https://arxiv.org/abs/2505.12625)
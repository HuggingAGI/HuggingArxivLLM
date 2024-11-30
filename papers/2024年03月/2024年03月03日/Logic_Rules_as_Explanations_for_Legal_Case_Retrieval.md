# 在法律案例检索领域，逻辑规则被用作一种解释手段。进一步优化，逻辑规则在挖掘和理解相关判例中扮演着解释性工具的角色，助力提升案例检索效率与准确性。

发布时间：2024年03月03日

`Agent`

> Logic Rules as Explanations for Legal Case Retrieval

# 摘要

> 本文着力解决如何借助逻辑规则揭示法律案例检索结果背后的原因。这一问题对于需要严谨逻辑支持和可解释性结论的法律专业人士（如律师或法官）来说极为重要。尽管近期已有研究尝试构建可解释的法律案例检索模型，但大多仅侧重于提取案例中的关键句子作为解释，而缺乏逻辑准确性和真实性。为此，我们创新提出了NS-LCR（神经符号增强法律案例检索）框架，它通过学习案例层面和法规层面的逻辑规则，并明确地运用这些规则对案例匹配进行推理。经过神经符号方式整合进检索流程后，NS-LCR因融合了逻辑规则的内在逻辑与可解释性，从而拥有了内建的可靠解释能力。值得一提的是，NS-LCR是一个通用性强的框架，能无缝接入多种法律检索模型中。为了彰显其优越性，我们在现有基准上加以改进，新增了人工标注的逻辑规则，并运用LLMs设计了一种新颖的可解释性评估指标。实验结果全面展示了NS-LCR在提升检索排序性能的同时，还能为法律案例检索提供权威可靠的解释。

> In this paper, we address the issue of using logic rules to explain the results from legal case retrieval. The task is critical to legal case retrieval because the users (e.g., lawyers or judges) are highly specialized and require the system to provide logical, faithful, and interpretable explanations before making legal decisions. Recently, research efforts have been made to learn explainable legal case retrieval models. However, these methods usually select rationales (key sentences) from the legal cases as explanations, failing to provide faithful and logically correct explanations. In this paper, we propose Neural-Symbolic enhanced Legal Case Retrieval (NS-LCR), a framework that explicitly conducts reasoning on the matching of legal cases through learning case-level and law-level logic rules. The learned rules are then integrated into the retrieval process in a neuro-symbolic manner. Benefiting from the logic and interpretable nature of the logic rules, NS-LCR is equipped with built-in faithful explainability. We also show that NS-LCR is a model-agnostic framework that can be plugged in for multiple legal retrieval models. To showcase NS-LCR's superiority, we enhance existing benchmarks by adding manually annotated logic rules and introducing a novel explainability metric using Large Language Models (LLMs). Our comprehensive experiments reveal NS-LCR's effectiveness for ranking, alongside its proficiency in delivering reliable explanations for legal case retrieval.

[Arxiv](https://arxiv.org/abs/2403.01457)
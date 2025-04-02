# 大型语言模型中的医学推理：深入解析 DeepSeek R1

发布时间：2025年03月27日

`LLM应用` `医疗健康` `人工智能`

> Medical Reasoning in LLMs: An In-Depth Analysis of DeepSeek R1

# 摘要

> 将大型语言模型（如 DeepSeek R1）整合到医疗健康领域需要进行严格的评估和验证，以确保其推理能力与临床专业知识保持一致。本研究通过 100 个 MedQA 临床案例，对 DeepSeek R1 的医学推理能力与专家模式的一致性进行了评估。该模型达到了 93% 的诊断准确率，展现了系统化的临床判断能力，包括鉴别诊断、基于指南的治疗选择以及整合患者特异性因素。然而，对 7 个错误案例的分析揭示了模型仍然存在一些持续的局限性：锚定偏见、难以调和相互矛盾的数据、对替代方案探索不足、过度思考、知识盲区以及过早优先考虑确定性治疗而非中间治疗。至关重要的是，推理长度与准确性之间存在关联：较短的回复（<5,000 字符）更可靠，这表明较长的解释可能反映出不确定性或对错误的合理化。尽管 DeepSeek R1 展现了基础的临床推理能力，但反复出现的缺陷凸显了需要改进的关键领域，包括偏见缓解、知识更新以及结构化的推理框架。这些发现凸显了 LLM 通过人工推理增强医疗决策的潜力，但也强调了在实际应用中确保可靠性的必要性，包括领域特定的验证、可解释性保障以及信心指标（例如响应长度阈值）。

> Integrating large language models (LLMs) like DeepSeek R1 into healthcare requires rigorous evaluation of their reasoning alignment with clinical expertise. This study assesses DeepSeek R1's medical reasoning against expert patterns using 100 MedQA clinical cases. The model achieved 93% diagnostic accuracy, demonstrating systematic clinical judgment through differential diagnosis, guideline-based treatment selection, and integration of patient-specific factors. However, error analysis of seven incorrect cases revealed persistent limitations: anchoring bias, challenges reconciling conflicting data, insufficient exploration of alternatives, overthinking, knowledge gaps, and premature prioritization of definitive treatment over intermediate care. Crucially, reasoning length correlated with accuracy - shorter responses (<5,000 characters) were more reliable, suggesting extended explanations may signal uncertainty or rationalization of errors. While DeepSeek R1 exhibits foundational clinical reasoning capabilities, recurring flaws highlight critical areas for refinement, including bias mitigation, knowledge updates, and structured reasoning frameworks. These findings underscore LLMs' potential to augment medical decision-making through artificial reasoning but emphasize the need for domain-specific validation, interpretability safeguards, and confidence metrics (e.g., response length thresholds) to ensure reliability in real-world applications.

[Arxiv](https://arxiv.org/abs/2504.00016)
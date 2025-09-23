# # 从得分到步骤：诊断与提升LLM在循证医学计算中的性能

发布时间：2025年09月20日

`Agent` `医疗健康`

> From Scores to Steps: Diagnosing and Improving LLM Performance in Evidence-Based Medical Calculations

# 摘要

> 大型语言模型（LLMs）在医疗基准测试中表现不俗，但其执行医疗计算的能力——临床决策的关键环节——却缺乏深入研究和有效评估。现有基准测试往往仅以宽泛的数值容忍度评判最终答案，忽略了系统性推理错误，可能导致严重的临床误判。本研究以临床可信度为核心，重新构建医疗计算评估体系。首先，我们清洗并重构MedCalc-Bench数据集，提出全新分步评估流程，对公式选择、实体提取和算术计算进行独立评估。在这一细粒度框架下，GPT-4o的准确率从62.7%降至43.6%，暴露了以往评估中被掩盖的错误。其次，我们引入自动错误分析框架，为各类错误模式生成结构化归因。人类评估证实其与专家判断一致，实现了可扩展、可解释的诊断分析。最后，我们提出模块化智能体流程MedRaC，融合检索增强生成与Python代码执行能力。无需微调，MedRaC将不同LLMs的准确率从16.35%提升至53.19%。本研究揭示了当前基准测试实践的局限性，提出更贴近临床实际的方法论。通过实现透明化、可迁移的推理评估，我们离让基于LLM的系统在真实医疗场景中具备可信度更近了一步。

> Large language models (LLMs) have demonstrated promising performance on medical benchmarks; however, their ability to perform medical calculations, a crucial aspect of clinical decision-making, remains underexplored and poorly evaluated. Existing benchmarks often assess only the final answer with a wide numerical tolerance, overlooking systematic reasoning failures and potentially causing serious clinical misjudgments. In this work, we revisit medical calculation evaluation with a stronger focus on clinical trustworthiness. First, we clean and restructure the MedCalc-Bench dataset and propose a new step-by-step evaluation pipeline that independently assesses formula selection, entity extraction, and arithmetic computation. Under this granular framework, the accuracy of GPT-4o drops from 62.7% to 43.6%, revealing errors masked by prior evaluations. Second, we introduce an automatic error analysis framework that generates structured attribution for each failure mode. Human evaluation confirms its alignment with expert judgment, enabling scalable and explainable diagnostics. Finally, we propose a modular agentic pipeline, MedRaC, that combines retrieval-augmented generation and Python-based code execution. Without any fine-tuning, MedRaC improves the accuracy of different LLMs from 16.35% up to 53.19%. Our work highlights the limitations of current benchmark practices and proposes a more clinically faithful methodology. By enabling transparent and transferable reasoning evaluation, we move closer to making LLM-based systems trustworthy for real-world medical applications.

[Arxiv](https://arxiv.org/abs/2509.16584)
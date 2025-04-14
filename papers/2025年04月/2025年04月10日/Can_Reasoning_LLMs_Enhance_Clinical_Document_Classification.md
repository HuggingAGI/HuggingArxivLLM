# 推理型LLM能否助力临床文档分类效果的提升？

发布时间：2025年04月10日

`LLM应用` `临床文档分类`

> Can Reasoning LLMs Enhance Clinical Document Classification?

# 摘要

> 临床文档分类是将非结构化医学文本转化为标准化 ICD-10 诊断编码的关键，但这一过程面临复杂医学语言、隐私限制及标注数据有限等挑战。大型语言模型（LLMs）为这一任务带来了显著的准确性和效率提升。本研究评估了八种 LLM 的性能与一致性，包括四种推理型模型（Qwen QWQ、Deepseek Reasoner、GPT o3 Mini、Gemini 2.0 Flash Thinking）和四种非推理型模型（Llama 3.3、GPT 4o Mini、Gemini 2.0 Flash、Deepseek Chat），使用 MIMIC-IV 数据集对临床出院总结进行分类。通过 cTAKES 工具对临床叙述进行结构化处理后，模型在三轮实验中接受了评估，最终预测由多数投票决定。结果显示，推理型模型在准确率（71% vs 68%）和 F1 分数（67% vs 60%）上优于非推理型模型，其中 Gemini 2.0 Flash Thinking 达到了最高的准确率（75%）和 F1 分数（76%）。然而，非推理型模型在稳定性上表现更佳（一致性分别为 91% 和 84%）。不同 ICD-10 代码的表现存在差异，推理型模型在复杂病例中表现突出，但在抽象类别上表现较弱。研究结果表明准确性和一致性之间存在权衡，建议采用混合方法优化临床编码。未来的研究应探索多标签分类、领域特定的微调以及集成方法，以提升模型在实际应用中的可靠性。

> Clinical document classification is essential for converting unstructured medical texts into standardised ICD-10 diagnoses, yet it faces challenges due to complex medical language, privacy constraints, and limited annotated datasets. Large Language Models (LLMs) offer promising improvements in accuracy and efficiency for this task. This study evaluates the performance and consistency of eight LLMs; four reasoning (Qwen QWQ, Deepseek Reasoner, GPT o3 Mini, Gemini 2.0 Flash Thinking) and four non-reasoning (Llama 3.3, GPT 4o Mini, Gemini 2.0 Flash, Deepseek Chat); in classifying clinical discharge summaries using the MIMIC-IV dataset. Using cTAKES to structure clinical narratives, models were assessed across three experimental runs, with majority voting determining final predictions. Results showed that reasoning models outperformed non-reasoning models in accuracy (71% vs 68%) and F1 score (67% vs 60%), with Gemini 2.0 Flash Thinking achieving the highest accuracy (75%) and F1 score (76%). However, non-reasoning models demonstrated greater stability (91% vs 84% consistency). Performance varied across ICD-10 codes, with reasoning models excelling in complex cases but struggling with abstract categories. Findings indicate a trade-off between accuracy and consistency, suggesting that a hybrid approach could optimise clinical coding. Future research should explore multi-label classification, domain-specific fine-tuning, and ensemble methods to enhance model reliability in real-world applications.

[Arxiv](https://arxiv.org/abs/2504.08040)
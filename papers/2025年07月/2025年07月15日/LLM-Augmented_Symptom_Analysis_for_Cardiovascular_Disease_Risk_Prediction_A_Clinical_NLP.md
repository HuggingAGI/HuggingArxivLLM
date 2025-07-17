# 基于LLM增强的症状分析助力心血管疾病风险预测：临床自然语言处理技术

发布时间：2025年07月15日

`LLM应用`

> LLM-Augmented Symptom Analysis for Cardiovascular Disease Risk Prediction: A Clinical NLP

# 摘要

> 及时识别和准确评估心血管疾病（CVD）的风险对于降低全球死亡率至关重要。尽管现有的预测模型主要依赖结构化数据，但未结构化的临床笔记中包含有价值的早期指标。本研究提出了一种新颖的LLM增强型临床NLP管道，该管道采用领域适应的大型语言模型，从自由文本报告中进行症状提取、上下文推理和关联分析。我们的方法整合了心血管特定的微调、基于提示的推理以及实体感知推理。在MIMIC-III和CARDIO-NLP数据集上的评估表明，与现有方法相比，我们在精确度、召回率、F1分数和AUROC等指标上均实现了性能提升，并且具有高度的临床相关性（kappa=0.82），这一结果得到了心脏病专家的验证。我们还通过提示工程和混合规则验证解决了上下文幻觉（即生成的合理信息与提供的来源相矛盾）和时间模糊（即模型难以处理事件的时间顺序）等挑战。这项研究凸显了大型语言模型在临床决策支持系统（CDSS）中的潜力，为早期预警系统的发展和将患者叙述转化为可操作的风险评估提供了重要支持。

> Timely identification and accurate risk stratification of cardiovascular disease (CVD) remain essential for reducing global mortality. While existing prediction models primarily leverage structured data, unstructured clinical notes contain valuable early indicators. This study introduces a novel LLM-augmented clinical NLP pipeline that employs domain-adapted large language models for symptom extraction, contextual reasoning, and correlation from free-text reports. Our approach integrates cardiovascular-specific fine-tuning, prompt-based inference, and entity-aware reasoning. Evaluations on MIMIC-III and CARDIO-NLP datasets demonstrate improved performance in precision, recall, F1-score, and AUROC, with high clinical relevance (kappa = 0.82) assessed by cardiologists. Challenges such as contextual hallucination, which occurs when plausible information contracts with provided source, and temporal ambiguity, which is related with models struggling with chronological ordering of events are addressed using prompt engineering and hybrid rule-based verification. This work underscores the potential of LLMs in clinical decision support systems (CDSS), advancing early warning systems and enhancing the translation of patient narratives into actionable risk assessments.

[Arxiv](https://arxiv.org/abs/2507.11052)
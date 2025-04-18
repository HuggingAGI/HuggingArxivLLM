# 精确度 ≠ 一致性：碰撞叙述分类模型的专家对齐评估

发布时间：2025年04月17日

`LLM应用` `事故分析`

> Accuracy is Not Agreement: Expert-Aligned Evaluation of Crash Narrative Classification Models

# 摘要

> 本研究旨在揭示深度学习（DL）模型的准确性与专家在事故叙述分类中的一致性之间的关系。我们对五个DL模型——包括BERT变体、通用句子编码器（USE）和零样本分类器——进行了评估，并将其与专家标注的数据和叙述文本进行对比。研究还扩展分析了四个大型语言模型（LLMs）：GPT-4、LLaMA 3、Qwen和Claude。令人意外的是，技术准确性较高的模型往往与领域专家的一致性较低，而尽管LLMs的准确度相对较低，却表现出更高的专家一致性。为了量化和解释模型与专家的一致性，我们采用了Cohen's Kappa、主成分分析（PCA）和基于SHAP的可解释性技术。研究发现，与专家一致的模型更倾向于依赖上下文和时间语言线索，而非特定位置的关键词。这些结果表明，在安全关键的NLP应用中，仅凭准确性来评估模型是不够的。我们建议在模型评估框架中将专家一致性作为补充指标，并强调LLMs作为可解释、可扩展工具在事故分析管道中的潜力。

> This study explores the relationship between deep learning (DL) model accuracy and expert agreement in the classification of crash narratives. We evaluate five DL models -- including BERT variants, the Universal Sentence Encoder (USE), and a zero-shot classifier -- against expert-labeled data and narrative text. The analysis is further extended to four large language models (LLMs): GPT-4, LLaMA 3, Qwen, and Claude. Our results reveal a counterintuitive trend: models with higher technical accuracy often exhibit lower agreement with domain experts, whereas LLMs demonstrate greater expert alignment despite relatively lower accuracy scores. To quantify and interpret model-expert agreement, we employ Cohen's Kappa, Principal Component Analysis (PCA), and SHAP-based explainability techniques. Findings indicate that expert-aligned models tend to rely more on contextual and temporal language cues, rather than location-specific keywords. These results underscore that accuracy alone is insufficient for evaluating models in safety-critical NLP applications. We advocate for incorporating expert agreement as a complementary metric in model evaluation frameworks and highlight the promise of LLMs as interpretable, scalable tools for crash analysis pipelines.

[Arxiv](https://arxiv.org/abs/2504.13068)
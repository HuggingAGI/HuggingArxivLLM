# 眼科知识与推理的大型语言模型基准测试（BELO）

发布时间：2025年07月21日

`LLM应用` `知识图谱`

> BEnchmarking LLMs for Ophthalmology (BELO) for Ophthalmological Knowledge and Reasoning

# 摘要

> 现有眼科领域大语言模型（LLMs）评估基准范围有限且过分强调准确性。我们推出眼科领域大语言模型评估基准BELO（BEnchmarking LLMs for Ophthalmology），该基准通过13位眼科专家多轮审核，是一个标准化且全面的评估体系。BELO专注于眼科相关临床准确性和推理质量的评估。

我们采用关键词匹配和微调后的PubMedBERT模型，从BCSC、MedMCQA、MedQA、BioASQ和PubMedQA等多个医学数据集整理出眼科特异性选择题（MCQs）。该数据集经过多轮专家审核，系统性移除了重复和质量不佳的问题。10位眼科专家完善了每个MCQ正确答案的解释，并由3位资深眼科专家进一步审核。

为展示BELO的实用性，我们采用准确率、宏F1以及ROUGE-L、BERTScore、BARTScore、METEOR和AlignScore等五个文本生成指标，对OpenAI o1、o3-mini、GPT-4o、DeepSeek-R1、Llama-3-8B和Gemini 1.5 Pro等六种LLMs进行了评估。在后续的人类专家评估中，两位眼科专家对50个随机抽取的输出进行了定性审查，评估其准确性、全面性和完整性。

BELO包含900个高质量、经专家审核的问题，分别来源于五个来源：BCSC（260）、BioASQ（10）、MedMCQA（572）、MedQA（40）和PubMedQA（18）。我们建立了公开排行榜以促进透明评估和报告。重要的是，BELO数据集将作为独立的评估基准，确保未来模型的公平和可重复比较。


> Current benchmarks evaluating large language models (LLMs) in ophthalmology are limited in scope and disproportionately prioritise accuracy. We introduce BELO (BEnchmarking LLMs for Ophthalmology), a standardized and comprehensive evaluation benchmark developed through multiple rounds of expert checking by 13 ophthalmologists. BELO assesses ophthalmology-related clinical accuracy and reasoning quality. Using keyword matching and a fine-tuned PubMedBERT model, we curated ophthalmology-specific multiple-choice-questions (MCQs) from diverse medical datasets (BCSC, MedMCQA, MedQA, BioASQ, and PubMedQA). The dataset underwent multiple rounds of expert checking. Duplicate and substandard questions were systematically removed. Ten ophthalmologists refined the explanations of each MCQ's correct answer. This was further adjudicated by three senior ophthalmologists. To illustrate BELO's utility, we evaluated six LLMs (OpenAI o1, o3-mini, GPT-4o, DeepSeek-R1, Llama-3-8B, and Gemini 1.5 Pro) using accuracy, macro-F1, and five text-generation metrics (ROUGE-L, BERTScore, BARTScore, METEOR, and AlignScore). In a further evaluation involving human experts, two ophthalmologists qualitatively reviewed 50 randomly selected outputs for accuracy, comprehensiveness, and completeness. BELO consists of 900 high-quality, expert-reviewed questions aggregated from five sources: BCSC (260), BioASQ (10), MedMCQA (572), MedQA (40), and PubMedQA (18). A public leaderboard has been established to promote transparent evaluation and reporting. Importantly, the BELO dataset will remain a hold-out, evaluation-only benchmark to ensure fair and reproducible comparisons of future models.

[Arxiv](https://arxiv.org/abs/2507.15717)
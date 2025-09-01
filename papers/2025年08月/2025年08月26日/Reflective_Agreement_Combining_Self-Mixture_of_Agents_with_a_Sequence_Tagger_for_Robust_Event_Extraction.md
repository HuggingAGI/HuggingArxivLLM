# 反思一致性：结合智能体自混合与序列标注器实现鲁棒事件抽取

发布时间：2025年08月26日

`LLM应用` `基础理论`

> Reflective Agreement: Combining Self-Mixture of Agents with a Sequence Tagger for Robust Event Extraction

# 摘要

> 事件抽取（EE）旨在从非结构化文本中自动识别并提取事件的结构化信息，包括触发词、事件类型及论元。传统判别模型虽精度较高，但召回率常受限制，尤其在处理细微或罕见事件时。与之相反，基于大型语言模型（LLMs）的生成式方法虽语义灵活性和召回率更高，却面临幻觉现象与预测不一致的困扰。为应对这些挑战，我们提出基于一致性的反思推理系统（ARIS）——一种融合智能体自混合模型与判别式序列标注器的混合方法。ARIS通过结构化模型一致性、置信度过滤及LLM反思推理模块，有效解决歧义问题，提升事件预测的整体质量。我们进一步探索分解指令微调，以增强LLM对事件抽取任务的理解能力。实验结果显示，该方法在三个基准数据集上均优于当前最先进的事件抽取方法。

> Event Extraction (EE) involves automatically identifying and extracting structured information about events from unstructured text, including triggers, event types, and arguments. Traditional discriminative models demonstrate high precision but often exhibit limited recall, particularly for nuanced or infrequent events. Conversely, generative approaches leveraging Large Language Models (LLMs) provide higher semantic flexibility and recall but suffer from hallucinations and inconsistent predictions. To address these challenges, we propose Agreement-based Reflective Inference System (ARIS), a hybrid approach combining a Self Mixture of Agents with a discriminative sequence tagger. ARIS explicitly leverages structured model consensus, confidence-based filtering, and an LLM reflective inference module to reliably resolve ambiguities and enhance overall event prediction quality. We further investigate decomposed instruction fine-tuning for enhanced LLM event extraction understanding. Experiments demonstrate our approach outperforms existing state-of-the-art event extraction methods across three benchmark datasets.

[Arxiv](https://arxiv.org/abs/2508.19359)
# 借助大型语言模型进行讽刺语句标注，助力讽刺检测研究

发布时间：2025年06月01日

`LLM应用` `数据科学`

> Leveraging Large Language Models for Sarcastic Speech Annotation in Sarcasm Detection

# 摘要

> 反语通过语气和语境改变意思，但识别语音中的反语仍具挑战性，主要由于数据稀缺。现有检测系统多依赖多模态数据，在仅有语音的场景下应用受限。我们提出一种注释流水线，利用大型语言模型（LLMs）生成反语数据集。以公开的反语播客为数据源，我们采用GPT-4o和LLaMA 3进行初步注释，再通过人工验证解决分歧。通过在公开数据集上使用协作 gating 架构验证注释质量与检测性能，我们最终推出了PodSarc，一个大规模讽刺语音数据集。检测模型实现73.63%的F1分数，证明该数据集作为反语检测研究基准的潜力。

> Sarcasm fundamentally alters meaning through tone and context, yet detecting it in speech remains a challenge due to data scarcity. In addition, existing detection systems often rely on multimodal data, limiting their applicability in contexts where only speech is available. To address this, we propose an annotation pipeline that leverages large language models (LLMs) to generate a sarcasm dataset. Using a publicly available sarcasm-focused podcast, we employ GPT-4o and LLaMA 3 for initial sarcasm annotations, followed by human verification to resolve disagreements. We validate this approach by comparing annotation quality and detection performance on a publicly available sarcasm dataset using a collaborative gating architecture. Finally, we introduce PodSarc, a large-scale sarcastic speech dataset created through this pipeline. The detection model achieves a 73.63% F1 score, demonstrating the dataset's potential as a benchmark for sarcasm detection research.

[Arxiv](https://arxiv.org/abs/2506.00955)
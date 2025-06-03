# 利用大型语言模型进行讽刺语料标注，助力讽刺识别研究

发布时间：2025年06月01日

`LLM应用` `语音处理`

> Leveraging Large Language Models for Sarcastic Speech Annotation in Sarcasm Detection

# 摘要

> 反语通过语气和语境改变意思，但识别语音中的反语仍具挑战性，主要由于数据稀缺。现有检测系统多依赖多模态数据，在仅有语音的场景下应用受限。为解决这一问题，我们提出了一种基于大型语言模型（LLMs）的注释流水线，用于生成反语数据集。借助一个公开的反语播客，我们首先使用GPT-4和LLaMA 3进行反语注释，随后通过人工验证解决分歧。我们通过在公开反语数据集上使用协作门控架构验证了这种方法的注释质量和检测性能。最终，我们推出了PodSarc——一个通过该流水线创建的大型反语语音数据集。检测模型达到了73.63%的F1分数，证明了该数据集在反语检测研究中作为基准的潜力。

> Sarcasm fundamentally alters meaning through tone and context, yet detecting it in speech remains a challenge due to data scarcity. In addition, existing detection systems often rely on multimodal data, limiting their applicability in contexts where only speech is available. To address this, we propose an annotation pipeline that leverages large language models (LLMs) to generate a sarcasm dataset. Using a publicly available sarcasm-focused podcast, we employ GPT-4o and LLaMA 3 for initial sarcasm annotations, followed by human verification to resolve disagreements. We validate this approach by comparing annotation quality and detection performance on a publicly available sarcasm dataset using a collaborative gating architecture. Finally, we introduce PodSarc, a large-scale sarcastic speech dataset created through this pipeline. The detection model achieves a 73.63% F1 score, demonstrating the dataset's potential as a benchmark for sarcasm detection research.

[Arxiv](https://arxiv.org/abs/2506.00955)
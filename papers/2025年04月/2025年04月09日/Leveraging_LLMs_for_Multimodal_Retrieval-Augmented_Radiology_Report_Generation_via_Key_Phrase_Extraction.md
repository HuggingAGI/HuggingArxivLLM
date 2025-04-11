# 利用大型语言模型，通过关键词提取实现多模态检索增强的放射科报告生成

发布时间：2025年04月09日

`RAG` `医学影像分析`

> Leveraging LLMs for Multimodal Retrieval-Augmented Radiology Report Generation via Key Phrase Extraction

# 摘要

> 自动放射科报告生成（RRG）有望减轻放射科医生的工作负担，尤其是在大型语言模型（LLMs）的最新进展推动下，多模态模型的开发为胸片（CXR）报告生成提供了可能。然而，多模态大型语言模型（MLLMs）需要大量数据和巨大的计算资源来进行训练，资源消耗较高。为了解决这些问题，我们提出了一种检索增强生成的方法，结合多模态检索和LLMs生成放射科报告，同时减少幻觉并降低计算需求。我们的方法利用LLMs从放射科报告中提取关键短语，从而聚焦于重要的诊断信息。通过探索有效的训练策略，包括图像编码器结构搜索、向文本嵌入添加噪声以及增加额外的训练目标，我们结合了互补的预训练图像编码器，并在文本和语义图像嵌入之间采用对比学习。我们在MIMIC-CXR数据集上评估了我们的方法，取得了CheXbert指标的最先进结果，并在RadGraph F1指标上与MLLMs相比具有竞争力，而无需进行LLM微调。我们的方法在多视图RRG中表现出强大的泛化能力，适用于全面的临床应用。

> Automated radiology report generation (RRG) holds potential to reduce radiologists' workload, especially as recent advancements in large language models (LLMs) enable the development of multimodal models for chest X-ray (CXR) report generation. However, multimodal LLMs (MLLMs) are resource-intensive, requiring vast datasets and substantial computational cost for training. To address these challenges, we propose a retrieval-augmented generation approach that leverages multimodal retrieval and LLMs to generate radiology reports while mitigating hallucinations and reducing computational demands. Our method uses LLMs to extract key phrases from radiology reports, effectively focusing on essential diagnostic information. Through exploring effective training strategies, including image encoder structure search, adding noise to text embeddings, and additional training objectives, we combine complementary pre-trained image encoders and adopt contrastive learning between text and semantic image embeddings. We evaluate our approach on MIMIC-CXR dataset, achieving state-of-the-art results on CheXbert metrics and competitive RadGraph F1 metric alongside MLLMs, without requiring LLM fine-tuning. Our method demonstrates robust generalization for multi-view RRG, making it suitable for comprehensive clinical applications.

[Arxiv](https://arxiv.org/abs/2504.07415)
# 微调大型多模态模型以实现自动发音评估

发布时间：2025年09月19日

`LLM应用` `教育科技`

> Fine-Tuning Large Multimodal Models for Automatic Pronunciation Assessment

# 摘要

> 自动发音评估（APA）是计算机辅助语言学习（CALL）的关键环节，需要从多个粒度和维度进行综合评估。大型多模态模型（LMMs）为APA领域带来了新的可能，然而它们在细粒度评估中的实际效果尚不明朗。本研究基于Speechocean762数据集和一个私有语料库，探索了LMMs在APA任务中的微调方法。结果显示，微调后的模型性能显著优于零样本设置，在单粒度任务上与公开及商业系统相比也达到了具有竞争力的水平。该模型在单词和句子层面表现出色，但音素层面的评估仍面临挑战。我们还发现，皮尔逊相关系数（PCC）达到0.9，而斯皮尔曼等级相关系数（SCC）则维持在0.6左右，这表明SCC更能反映顺序一致性。这些发现既彰显了LMMs在APA任务中的潜力，也揭示了其局限性，同时为细粒度建模和排序感知评估指明了未来研究方向。

> Automatic Pronunciation Assessment (APA) is critical for Computer-Assisted Language Learning (CALL), requiring evaluation across multiple granularities and aspects. Large Multimodal Models (LMMs) present new opportunities for APA, but their effectiveness in fine-grained assessment remains uncertain. This work investigates fine-tuning LMMs for APA using the Speechocean762 dataset and a private corpus. Fine-tuning significantly outperforms zero-shot settings and achieves competitive results on single-granularity tasks compared to public and commercial systems. The model performs well at word and sentence levels, while phoneme-level assessment remains challenging. We also observe that the Pearson Correlation Coefficient (PCC) reaches 0.9, whereas Spearman's rank Correlation Coefficient (SCC) remains around 0.6, suggesting that SCC better reflects ordinal consistency. These findings highlight both the promise and limitations of LMMs for APA and point to future work on fine-grained modeling and rank-aware evaluation.

[Arxiv](https://arxiv.org/abs/2509.15701)
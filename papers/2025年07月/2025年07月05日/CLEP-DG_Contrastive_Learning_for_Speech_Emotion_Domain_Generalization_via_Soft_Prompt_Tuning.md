# CLEP-DG: 通过软提示调优实现语音情感领域泛化的对比学习

发布时间：2025年07月05日

`LLM应用` `情感计算` `人机交互`

> CLEP-DG: Contrastive Learning for Speech Emotion Domain Generalization via Soft Prompt Tuning

# 摘要

> 语音情感识别（SER）是情感计算和人机交互的基础，但现有模型在不同声学条件下难以实现良好泛化。尽管对比语言-音频预训练（CLAP）提供了强大的多模态对齐能力，但它缺乏专门捕捉情感线索的机制，导致在SER任务中表现不佳。为解决这一问题，我们提出了CLEP-DG框架，以增强CLAP在情感识别方面的稳健性。首先，我们对CLAP进行微调，得到CLEP，并在大规模情感语音数据集上进行适配，以更好地编码与情感相关特征。其次，我们引入了基于文本驱动的增强策略——声学上下文提示调优（ACPT），通过优化可学习的提示向量来建模多样化的声学环境，而无需额外的标注音频数据。最后，借助跨模态的迁移能力，我们在文本衍生的嵌入上训练分类器，并在推理过程中将其应用于音频编码器，从而缓解文本监督与基于音频的情感识别之间的领域偏移问题。在五个基准数据集上的实验表明，CLEP-DG优于之前的CLAP基线方法，并在监督学习和领域泛化设置下均达到了当前最优性能。

> Speech Emotion Recognition (SER) is fundamental to affective computing and human-computer interaction, yet existing models struggle to generalize across diverse acoustic conditions. While Contrastive Language-Audio Pretraining (CLAP) provides strong multimodal alignment, it lacks dedicated mechanisms for capturing emotional cues, making it suboptimal for SER. To address this, we propose CLEP-DG, a framework that enhances CLAP's robustness in emotion recognition. First, we fine-tune CLAP to obtain CLEP, adapting it on large-scale emotional speech datasets to better encode emotion-relevant features. Then, we introduce Acoustic Context Prompt Tuning (ACPT), a text-driven augmentation strategy that optimizes learnable prompt vectors to model diverse acoustic environments without additional labeled audio. Finally, leveraging cross-modal transferability, we train a classifier on text-derived embeddings and apply it to the audio encoder during inference, mitigating domain shifts between textual supervision and audio-based emotion recognition. Experiments across five benchmark datasets show that CLEP-DG outperforms prior CLAP-based approaches, achieving state-of-the-art performance in both supervised and domain generalization settings.

[Arxiv](https://arxiv.org/abs/2507.04048)
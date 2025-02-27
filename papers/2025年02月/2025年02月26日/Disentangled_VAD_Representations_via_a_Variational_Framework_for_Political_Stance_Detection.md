# # 解耦 VAD 表示的变分框架及其在政治立场检测中的应用
通过变分框架实现解耦的 VAD 表示用于政治立场检测

发布时间：2025年02月26日

`LLM应用` `政治学`

> Disentangled VAD Representations via a Variational Framework for Political Stance Detection

# 摘要

> 立场检测任务旨在对特定目标的态度进行分类。当前方法在有效整合情感信息以实现立场检测方面存在挑战，且高度细致的情感标注在立场检测中的作用尚未得到充分重视。本研究提出了一种基于变分自编码器（VAE）的新型立场检测框架，用于从社交媒体上的政治话语中解耦潜在情感特征——价值、唤醒和控制（VAD）。这种方法解决了现有方法的局限性，特别是在目标内和跨目标立场检测场景中。本研究采用先进的情感标注工具为P-STANCE数据集标注了七类情感标签。在P-STANCE和SemEval-2016等基准数据集上的评估显示，PoliStance-VAE实现了最先进的性能，超越了BERT、BERTweet和GPT-4o等模型。PoliStance-VAE不仅为立场检测提供了一种强大且可解释的解决方案，还证明了整合细致情感表示的有效性。这一框架为自然语言处理任务的进步铺平了道路，特别是在需要深入了解情感的任务中展现了巨大潜力。

> The stance detection task aims to categorise the stance regarding specified targets. Current methods face challenges in effectively integrating sentiment information for stance detection. Moreover, the role of highly granular sentiment labelling in stance detection has been largely overlooked. This study presents a novel stance detection framework utilizing a variational autoencoder (VAE) to disentangle latent emotional features-value, arousal, and dominance (VAD)-from political discourse on social media. This approach addresses limitations in current methods, particularly in in-target and cross-target stance detection scenarios. This research uses an advanced emotional annotation tool to annotate seven-class sentiment labels for P-STANCE. Evaluations on benchmark datasets, including P-STANCE and SemEval-2016, reveal that PoliStance-VAE achieves state-of-the-art performance, surpassing models like BERT, BERTweet, and GPT-4o. PoliStance-VAE offers a robust and interpretable solution for stance detection, demonstrating the effectiveness of integrating nuanced emotional representations. This framework paves the way for advancements in natural language processing tasks, particularly those requiring detailed emotional understanding.

[Arxiv](https://arxiv.org/abs/2502.19276)
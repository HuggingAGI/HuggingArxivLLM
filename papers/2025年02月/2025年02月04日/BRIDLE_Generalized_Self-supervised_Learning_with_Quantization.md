# BRIDLE: 量化驱动的广义自监督学习

发布时间：2025年02月04日

`其他

理由：这篇论文主要讨论的是自监督学习框架BRIDLE，它通过残差量化（RQ）和双向训练过程来提升音频、图像和视频的表示质量。虽然论文提到了BERT和BEATs模型，但这些内容主要是作为背景和动机，而不是论文的核心。论文的核心是提出了一种新的自监督学习框架，并展示了其在多个任务上的性能提升。因此，这篇论文更适合归类为“其他”，而不是与LLM、Agent或RAG直接相关的类别。` `音频处理` `图像处理`

> BRIDLE: Generalized Self-supervised Learning with Quantization

# 摘要

> # 摘要
自监督学习是一种强大的方法，能够从各种领域的未标记数据中学习有意义的表示，减少了对大规模标记数据集的依赖。受BERT在自然语言处理中成功捕捉深度双向上下文的启发，类似框架已扩展到音频等模态，如BEATs模型通过向量量化（VQ）将双向训练范式应用于音频信号。然而，这些框架面临挑战，尤其是依赖单一码本进行量化，难以捕捉信号的复杂多面性。此外，码本利用效率低下导致码向量未被充分利用。为解决这些问题，我们提出了BRIDLE（双向残差量化交错离散学习编码器），这是一种自监督编码器预训练框架，将残差量化（RQ）融入双向训练过程，并推广至音频、图像和视频的预训练。通过使用多个分层码本，RQ在潜在空间中实现了细粒度的离散化，提升了表示质量。BRIDLE采用编码器与分词器交错训练的方式。我们在音频理解任务中使用分类基准评估BRIDLE，取得了最先进的结果，并在图像分类和视频分类任务中展示了竞争力，下游性能相比传统VQ方法持续提升。

> Self-supervised learning has been a powerful approach for learning meaningful representations from unlabeled data across various domains, reducing the reliance on large labeled datasets. Inspired by BERT's success in capturing deep bidirectional contexts in natural language processing, similar frameworks have been adapted to other modalities such as audio, with models like BEATs extending the bidirectional training paradigm to audio signals using vector quantization (VQ). However, these frameworks face challenges, notably their dependence on a single codebook for quantization, which may not capture the complex, multifaceted nature of signals. In addition, inefficiencies in codebook utilization lead to underutilized code vectors. To address these limitations, we introduce BRIDLE (Bidirectional Residual Quantization Interleaved Discrete Learning Encoder), a self-supervised encoder pretraining framework that incorporates residual quantization (RQ) into the bidirectional training process, and is generalized for pretraining with audio, image, and video. Using multiple hierarchical codebooks, RQ enables fine-grained discretization in the latent space, enhancing representation quality. BRIDLE involves an interleaved training procedure between the encoder and tokenizer. We evaluate BRIDLE on audio understanding tasks using classification benchmarks, achieving state-of-the-art results, and demonstrate competitive performance on image classification and video classification tasks, showing consistent improvements over traditional VQ methods in downstream performance.

[Arxiv](https://arxiv.org/abs/2502.02118)
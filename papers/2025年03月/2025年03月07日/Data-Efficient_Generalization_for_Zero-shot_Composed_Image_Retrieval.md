# 数据高效泛化在零样本组合图像检索中的应用

发布时间：2025年03月07日

`其他

分类理由：这篇论文主要讨论的是零样本组合图像检索（ZS-CIR）的方法改进，结合了视觉和语言模型，但并未直接涉及大型语言模型（LLM）的应用或理论。因此，更适合归类到其他。` `图像检索` `视觉-语言模型`

> Data-Efficient Generalization for Zero-shot Composed Image Retrieval

# 摘要

> 零样本组合图像检索（ZS-CIR）的目标是通过参考图像和文本描述检索目标图像，无需依赖分布内的三元组进行训练。现有方法通常基于视觉-语言预训练范式，利用映射网络将图像嵌入转换为文本嵌入空间中的伪词令牌。然而，由于模态差异和训练与推理之间的分布偏移，这种方法容易限制网络的泛化能力。针对这一问题，我们提出了数据高效的泛化（DeG）框架，包含两个创新设计：文本补充（TS）模块和语义集（S-Set）。TS模块通过在训练过程中利用组合文本语义，增强伪词令牌的语义信息，从而有效缓解模态差异。S-Set则借助预训练视觉-语言模型（VLM）的零样本能力，缓解分布偏移问题，并通过减少大规模图像-文本数据的冗余来降低过拟合风险。在四个ZS-CIR基准上的大量实验表明，DeG框架不仅在使用更少训练数据的情况下超越了现有最优方法（SOTA），还在实际应用中大幅节省了训练和推理时间，展现出显著的优势。

> Zero-shot Composed Image Retrieval (ZS-CIR) aims to retrieve the target image based on a reference image and a text description without requiring in-distribution triplets for training. One prevalent approach follows the vision-language pretraining paradigm that employs a mapping network to transfer the image embedding to a pseudo-word token in the text embedding space. However, this approach tends to impede network generalization due to modality discrepancy and distribution shift between training and inference. To this end, we propose a Data-efficient Generalization (DeG) framework, including two novel designs, namely, Textual Supplement (TS) module and Semantic-Set (S-Set). The TS module exploits compositional textual semantics during training, enhancing the pseudo-word token with more linguistic semantics and thus mitigating the modality discrepancy effectively. The S-Set exploits the zero-shot capability of pretrained Vision-Language Models (VLMs), alleviating the distribution shift and mitigating the overfitting issue from the redundancy of the large-scale image-text data. Extensive experiments over four ZS-CIR benchmarks show that DeG outperforms the state-of-the-art (SOTA) methods with much less training data, and saves substantial training and inference time for practical usage.

[Arxiv](https://arxiv.org/abs/2503.05204)
# 提升大型视觉语言模型中多模态的对齐效果

发布时间：2025年03月25日

`LLM应用` `视觉语言任务`

> Improved Alignment of Modalities in Large Vision Language Models

# 摘要

> # 摘要
视觉语言模型的最新进展在赋予语言模型理解视觉输入的能力方面取得了显著成效。然而，要在图像描述生成、视觉问答等多样化任务中统一这些模型的对齐方法仍是一个难题。现有方法要么依赖于规模庞大的语言模型，要么需要海量数据集支持，这在现有模型的利用效率上存在明显不足。本文针对这一研究空白，提出了一种自回归视觉语言模型的训练策略，旨在统一图像描述生成和视觉问答等视觉语言任务。我们设计了四个训练阶段，用于实现视觉模型与语言模型的对齐，换句话说，赋予语言模型处理视觉输入的能力。我们还引入了不同的注意力掩码，用于优化基于 Transformer 的语言模型，提升视觉特征的质量。此外，我们还总结了几个关键发现：1) 视觉输入不应使用注意力掩码，2) 语言模型在 AI 生成数据上的收敛速度更快，3) 模型预训练过程中应加强对齐阶段的研究，4) 该模型能够轻松适应医疗数据集（如 PathVQA）上的视觉问答等下游任务。经过一个 epoch 的完整阶段训练后，该模型在 COCO 和 Flickr30k 数据集上的 CIDEr 等常见基准指标上，超越了 VILA-13B 等大型模型。尽管数据集和模型规模较小，但在同一数据集上也达到了与 GIT-2 非常接近的性能。整个训练过程采用了最佳实践，包括多 GPU 并行训练、16 位浮点数的低精度训练、更快的注意力机制（SDPA）和梯度累积，最终在 12 小时内高效完成了训练。

> Recent advancements in vision-language models have achieved remarkable results in making language models understand vision inputs. However, a unified approach to align these models across diverse tasks such as image captioning and visual question answering remains a challenge. Existing methods either require very big language models or very big datasets which is not efficient in utilizing existing models. This paper addresses this gap and devises a training strategy of auto-regressive vision-language models, to unify vision-language tasks like image-captioning and visual question answering. We propose four training stages for aligning the vision model with the language model, in other words, the language model is given an ability to process visual inputs. We also devise different attention masks for training transformer-based language models that improve the quality of visual features. Further, we introduce some findings, 1) the attention mask should not be applied on visual inputs, 2) the Language model converges faster on AI- generated data, 3) More work should be done in the alignment stage during the pre-training of the model, 4) the model can easily adapt to any downstream tasks like visual question answering on healthcare datasets like PathVQA. After training the model for one epoch for all the stages, it outperforms large models like VILA-13 billion models on common benchmarks like CIDEr scores on COCO and Flickr30k datasets and achieves very close scores to GIT-2 on the same dataset despite being a much smaller model trained on a much smaller dataset. All of the training is done using best practices available like multi- GPU parallel training, lower-precision training with 16-bit float numbers, faster attention (SDPA), and gradient accumulation, and completed the training within 12 hours.

[Arxiv](https://arxiv.org/abs/2503.19508)
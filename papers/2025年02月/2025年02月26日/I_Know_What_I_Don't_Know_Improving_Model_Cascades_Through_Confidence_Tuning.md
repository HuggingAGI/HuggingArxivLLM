# 我了解自己的知识边界：利用置信度调优优化模型级联结构

发布时间：2025年02月26日

`其他` `人工智能`

> I Know What I Don't Know: Improving Model Cascades Through Confidence Tuning

# 摘要

> 大规模机器学习模型在多种任务中表现出色，但也面临显著的计算与资源限制。为应对这些挑战，我们通常会将小型模型与大型模型结合使用，并借助路由和延迟机制将复杂任务转移。然而，现有方法未能有效平衡这些模型的能力，常导致不必要的延迟或资源浪费。在本研究中，我们提出了一种名为Gatekeeper的新损失函数，用于级联设置中小型模型的校准。我们的方法通过对小型模型进行微调，使其能够自信地处理自身擅长的任务，同时将复杂任务智能地延迟给大型模型。此外，该方法还包含一个机制，用于平衡模型性能与延迟精度，并且无需任何架构更改，即可广泛适用于各种任务和领域。我们在编码器-解码器架构上进行了全面评估，实验结果表明，我们的方法在图像分类、语言建模和视觉-语言任务中显著提升了延迟性能。

> Large-scale machine learning models deliver strong performance across a wide range of tasks but come with significant computational and resource constraints. To mitigate these challenges, local smaller models are often deployed alongside larger models, relying on routing and deferral mechanisms to offload complex tasks. However, existing approaches inadequately balance the capabilities of these models, often resulting in unnecessary deferrals or sub-optimal resource usage. In this work we introduce a novel loss function called Gatekeeper for calibrating smaller models in cascade setups. Our approach fine-tunes the smaller model to confidently handle tasks it can perform correctly while deferring complex tasks to the larger model. Moreover, it incorporates a mechanism for managing the trade-off between model performance and deferral accuracy, and is broadly applicable across various tasks and domains without any architectural changes. We evaluate our method on encoder-only, decoder-only, and encoder-decoder architectures. Experiments across image classification, language modeling, and vision-language tasks show that our approach substantially improves deferral performance.

[Arxiv](https://arxiv.org/abs/2502.19335)
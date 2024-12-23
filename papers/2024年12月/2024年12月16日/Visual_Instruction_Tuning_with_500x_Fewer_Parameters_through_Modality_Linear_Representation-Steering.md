# 通过模态线性表示引导，以少 500 倍的参数来进行视觉指令的调整

发布时间：2024年12月16日

`LLM应用` `人工智能`

> Visual Instruction Tuning with 500x Fewer Parameters through Modality Linear Representation-Steering

# 摘要

> 多模态大型语言模型（MLLMs）将视觉表示融入大型语言模型（LLMs），极大地推动了视觉任务的发展。从 LLMs 继承而来的文本模态，赋予了 MLLMs 遵循指令和上下文学习等能力。而视觉模态凭借丰富的语义内容、空间信息和基础能力，提升了下游任务的表现。这些内在模态在各类视觉任务中协同运作。我们的研究起初发现，这些模态之间存在长期的不平衡，在视觉指令调整时，文本往往主导输出结果。无论是采用全微调还是参数高效微调（PEFT）方法，这种不平衡都会出现。之后我们发现，重新平衡这些模态能够大幅减少所需的可训练参数数量，为优化视觉指令调整指明了方向。我们引入了模态线性表示引导（MoReS）来达成这一目标。MoReS 能在整个模型中有效地重新平衡内在模态，其核心思路是通过在每个模型层的视觉子空间中进行线性变换来引导视觉表示。为验证我们的解决方案，我们构建了 LLaVA Steering，这是一组集成了所提出的 MoReS 方法的模型。评估结果显示，构建的 LLaVA Steering 模型平均所需的可训练参数比 LoRA 少 500 倍，同时在三个视觉基准和八个视觉问答任务中仍能取得相当的性能。最后，我们推出了 LLaVA Steering Factory，这是一个内部开发的平台，能让研究人员利用基于组件的架构快速定制各种 MLLMs，实现最先进模型的无缝集成，并评估其内在模态的不平衡情况。

> Multimodal Large Language Models (MLLMs) have significantly advanced visual tasks by integrating visual representations into large language models (LLMs). The textual modality, inherited from LLMs, equips MLLMs with abilities like instruction following and in-context learning. In contrast, the visual modality enhances performance in downstream tasks by leveraging rich semantic content, spatial information, and grounding capabilities. These intrinsic modalities work synergistically across various visual tasks. Our research initially reveals a persistent imbalance between these modalities, with text often dominating output generation during visual instruction tuning. This imbalance occurs when using both full fine-tuning and parameter-efficient fine-tuning (PEFT) methods. We then found that re-balancing these modalities can significantly reduce the number of trainable parameters required, inspiring a direction for further optimizing visual instruction tuning. We introduce Modality Linear Representation-Steering (MoReS) to achieve the goal. MoReS effectively re-balances the intrinsic modalities throughout the model, where the key idea is to steer visual representations through linear transformations in the visual subspace across each model layer. To validate our solution, we composed LLaVA Steering, a suite of models integrated with the proposed MoReS method. Evaluation results show that the composed LLaVA Steering models require, on average, 500 times fewer trainable parameters than LoRA needs while still achieving comparable performance across three visual benchmarks and eight visual question-answering tasks. Last, we present the LLaVA Steering Factory, an in-house developed platform that enables researchers to quickly customize various MLLMs with component-based architecture for seamlessly integrating state-of-the-art models, and evaluate their intrinsic modality imbalance.

[Arxiv](https://arxiv.org/abs/2412.12359)
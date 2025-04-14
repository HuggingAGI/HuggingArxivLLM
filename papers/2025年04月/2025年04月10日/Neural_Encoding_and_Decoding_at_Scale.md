# 大规模神经编码与解码

发布时间：2025年04月10日

`其他` `神经科学` `脑科学`

> Neural Encoding and Decoding at Scale

# 摘要

> 最近研究显示，大规模多动物模型在表征神经活动与行为关系方面表现出强大能力。然而，现有方法仅专注于单向预测，无法捕捉二者的双向关系。为解决这一问题，我们提出了一种多模态多任务模型——大规模神经编码与解码系统（NEDS），并采用创新的多任务掩码策略，交替应用神经、行为、跨模态和跨模态掩码。我们在国际脑实验室（IBL）的数据集上进行预训练，该数据集包含83只动物执行相同视觉决策任务的记录。与其他模型相比，NEDS在多动物数据预训练后，再对新动物进行微调，其编码和解码性能均达到顶尖水平。更令人惊喜的是，NEDS的学习嵌入表现出涌现性质：即使没有明确训练，它们也能高度预测每个记录中的脑区。总体而言，我们的方法为构建能够无缝转换神经活动与行为的脑基础模型奠定了重要基础。

> Recent work has demonstrated that large-scale, multi-animal models are powerful tools for characterizing the relationship between neural activity and behavior. Current large-scale approaches, however, focus exclusively on either predicting neural activity from behavior (encoding) or predicting behavior from neural activity (decoding), limiting their ability to capture the bidirectional relationship between neural activity and behavior. To bridge this gap, we introduce a multimodal, multi-task model that enables simultaneous Neural Encoding and Decoding at Scale (NEDS). Central to our approach is a novel multi-task-masking strategy, which alternates between neural, behavioral, within-modality, and cross-modality masking. We pretrain our method on the International Brain Laboratory (IBL) repeated site dataset, which includes recordings from 83 animals performing the same visual decision-making task. In comparison to other large-scale models, we demonstrate that NEDS achieves state-of-the-art performance for both encoding and decoding when pretrained on multi-animal data and then fine-tuned on new animals. Surprisingly, NEDS's learned embeddings exhibit emergent properties: even without explicit training, they are highly predictive of the brain regions in each recording. Altogether, our approach is a step towards a foundation model of the brain that enables seamless translation between neural activity and behavior.

[Arxiv](https://arxiv.org/abs/2504.08201)
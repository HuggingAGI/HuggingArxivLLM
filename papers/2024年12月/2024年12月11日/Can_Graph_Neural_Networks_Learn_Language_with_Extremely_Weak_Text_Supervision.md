# 图神经网络能否在极其微弱的文本监督下学习语言？

发布时间：2024年12月11日

`LLM应用` `图神经网络` `多模态学习`

> Can Graph Neural Networks Learn Language with Extremely Weak Text Supervision?

# 摘要

> 虽然借助互联网规模的图像-文本对，通过对比语言-图像预训练（CLIP）构建视觉模型已大获成功，但利用 CLIP 流程构建可迁移的图神经网络（GNNs）却困难重重，这源于三个根本问题：标记数据和文本监督的稀缺、下游任务的不同层级以及领域间的概念差异。在本研究中，为应对这些难题，我们借助多模态提示学习，仅凭借几个带有极弱文本监督的语义标记样本，就能有效让预训练的 GNN 适配下游任务和数据。我们的新范式通过同步学习图提示与文本提示，将图直接嵌入与大型语言模型（LLMs）相同的空间。为此，我们改良了前沿的图提示方法，并率先提出了图-语言多模态提示学习方法，以挖掘预训练模型中的知识。值得一提的是，由于微调监督不足，在我们的范式中，预训练的 GNN 和 LLM 保持冻结，所以可学习参数远少于微调任何预训练模型。通过在真实世界数据集上的大量实验，我们展示了我们的范式在少样本、多任务层级和跨领域场景中的卓越性能。此外，我们构建了首个 CLIP 风格的零样本分类原型，能够在极弱的文本监督下将 GNN 推广到未曾见过的类别。

> While great success has been achieved in building vision models with Contrastive Language-Image Pre-training (CLIP) over Internet-scale image-text pairs, building transferable Graph Neural Networks (GNNs) with CLIP pipeline is challenging because of three fundamental issues: the scarcity of labeled data and text supervision, different levels of downstream tasks, and the conceptual gaps between domains. In this work, to address these issues, we leverage multi-modal prompt learning to effectively adapt pre-trained GNN to downstream tasks and data, given only a few semantically labeled samples, each with extremely weak text supervision. Our new paradigm embeds the graphs directly in the same space as the Large Language Models (LLMs) by learning both graph prompts and text prompts simultaneously. To accomplish this, we improve state-of-the-art graph prompt method, and then propose the first graph-language multi-modal prompt learning approach for exploiting the knowledge in pre-trained models. Notably, due to the insufficient supervision for fine-tuning, in our paradigm, the pre-trained GNN and the LLM are kept frozen, so the learnable parameters are much fewer than fine-tuning any pre-trained model. Through extensive experiments on real-world datasets, we demonstrate the superior performance of our paradigm in few-shot, multi-task-level, and cross-domain settings. Moreover, we build the first CLIP-style zero-shot classification prototype that can generalize GNNs to unseen classes with extremely weak text supervision.

[Arxiv](https://arxiv.org/abs/2412.08174)
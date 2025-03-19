# 视觉描述生成中微调与预训练的解耦研究：基于混合马尔可夫逻辑

发布时间：2025年03月17日

`LLM理论` `计算机视觉`

> Disentangling Fine-Tuning from Pre-Training in Visual Captioning with Hybrid Markov Logic

# 摘要

> 多模态系统在预训练大型数据集后，针对特定任务（如视觉描述生成）进行微调，但难以区分模型在微调过程中学到的知识与预训练带来的知识。本研究通过Hybrid Markov Logic Networks (HMLNs)学习概率模型，关联描述中的符号知识与图像的视觉特征。基于HMLN分布，我们量化训练样本对生成 captions 的影响。在MSCOCO数据集上，我们评估了两种推理方法，适用于不同类型的描述生成模型。结果显示，对于使用LLM的BLIP2模型，微调对其知识的影响较小，因其在视觉描述生成方面拥有更广泛的知识。

> Multimodal systems have highly complex processing pipelines and are pretrained over large datasets before being fine-tuned for specific tasks such as visual captioning. However, it becomes hard to disentangle what the model learns during the fine-tuning process from what it already knows due to its pretraining. In this work, we learn a probabilistic model using Hybrid Markov Logic Networks (HMLNs) over the training examples by relating symbolic knowledge (extracted from the caption) with visual features (extracted from the image). For a generated caption, we quantify the influence of training examples based on the HMLN distribution using probabilistic inference. We evaluate two types of inference procedures on the MSCOCO dataset for different types of captioning models. Our results show that for BLIP2 (a model that uses a LLM), the fine-tuning may have smaller influence on the knowledge the model has acquired since it may have more general knowledge to perform visual captioning as compared to models that do not use a LLM

[Arxiv](https://arxiv.org/abs/2503.13847)
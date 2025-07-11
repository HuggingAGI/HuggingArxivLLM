# CLIP 无法从自然数据中学习物体属性绑定，这是为什么？

发布时间：2025年07月10日

`LLM应用` `计算机视觉` `多模态学习`

> CLIP Won't Learn Object-Attribute Binding from Natural Data and Here is Why

# 摘要

> 对比视觉-语言模型，如CLIP，广泛应用于零-shot分类和多模态模型的视觉编码器。尽管其应用广泛，但CLIP的表示方法存在明显局限。例如，CLIP模型采用词袋表示法，无法区分图像中的物体颜色组合，如“黄色潜水艇和蓝色公交车”与“蓝色潜水艇和黄色公交车”。此前尝试通过增加训练中的硬负样本或修改模型架构来解决此问题，但收效甚微。我们认为，解决CLIP绑定问题的关键可能在于数据，这是学习算法中被认为最重要的部分。本研究通过合成数据集，系统地分析了数据属性对CLIP学习绑定能力的影响。我们发现，自然数据中的低属性密度、不完整描述以及显著性偏差（即描述者倾向于关注最显著的物体）均会对绑定性能产生负面影响。与普遍认知相反，我们发现无论是扩大批量大小（隐式增加硬负样本）还是显式创建硬负样本，都无法有效提升CLIP的绑定能力。只有当数据具备我们识别出的特定属性时，CLIP才能几乎完美地实现绑定效果。

> Contrastive vision-language models like CLIP are used for a large variety of applications, such as zero-shot classification or as vision encoder for multi-modal models. Despite their popularity, their representations show major limitations. For instance, CLIP models learn bag-of-words representations and, as a consequence, fail to distinguish whether an image is of "a yellow submarine and a blue bus" or "a blue submarine and a yellow bus". Previous attempts to fix this issue added hard negatives during training or modified the architecture, but failed to resolve the problem in its entirety. We suspect that the missing insights to solve the binding problem for CLIP are hidden in the arguably most important part of learning algorithms: the data. In this work, we fill this gap by rigorously identifying the influence of data properties on CLIP's ability to learn binding using a synthetic dataset. We find that common properties of natural data such as low attribute density, incomplete captions, and the saliency bias, a tendency of human captioners to describe the object that is "most salient" to them have a detrimental effect on binding performance. In contrast to common belief, we find that neither scaling the batch size, i.e., implicitly adding more hard negatives, nor explicitly creating hard negatives enables CLIP to learn reliable binding. Only when the data expresses our identified data properties CLIP learns almost perfect binding.

[Arxiv](https://arxiv.org/abs/2507.07985)
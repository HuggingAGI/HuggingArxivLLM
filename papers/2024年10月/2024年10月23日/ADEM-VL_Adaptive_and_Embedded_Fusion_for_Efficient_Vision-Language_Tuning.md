# ADEM-VL：高效视觉-语言调优的自适应与嵌入式融合

发布时间：2024年10月23日

`LLM应用

理由：这篇论文主要讨论了如何利用预训练的大型语言模型（LLMs）来构建高效的视觉-语言模型（VL模型），并提出了ADEM-VL方法。该方法通过减少可训练参数和优化多模态融合过程，显著提升了训练和推理速度。论文的核心在于如何将LLMs应用于视觉-语言任务（如视觉问答、图像描述等），并展示了其在具体任务上的性能提升。因此，这篇论文属于LLM应用类别。` `计算机视觉`

> ADEM-VL: Adaptive and Embedded Fusion for Efficient Vision-Language Tuning

# 摘要

> # 摘要
近年来，多模态融合的突破性进展使得视觉-语言（VL）模型在图像描述、视觉问答等任务中大放异彩。然而，构建VL模型需要大量硬件资源，其效率受限于两大瓶颈：一是语言模型与视觉特征结合的扩展输入序列增加了计算负担，二是大量可学习参数导致内存复杂度飙升。这些挑战严重限制了VL模型的广泛应用。为此，我们提出了ADEM-VL，一种基于预训练大型语言模型（LLMs）的高效视觉-语言方法。通过采用无参数交叉注意力机制进行多模态融合中的相似性测量，ADEM-VL仅需将视觉特征嵌入语言空间，大幅减少了可训练参数，显著提升了训练和推理速度。此外，我们引入了一种高效的多尺度特征生成方案，仅需一次视觉编码器前向传递即可完成特征提取。同时，我们提出了一种自适应融合机制，根据文本标记的注意力分数动态筛选视觉信息，确保融合过程聚焦于最相关的视觉特征。在视觉问答、图像描述和指令跟随等任务上的实验表明，ADEM-VL在ScienceQA数据集上的平均准确率比现有方法高出0.77%，同时显著降低了训练和推理延迟，充分证明了其优越性。代码已开源：https://github.com/Hao840/ADEM-VL。

> Recent advancements in multimodal fusion have witnessed the remarkable success of vision-language (VL) models, which excel in various multimodal applications such as image captioning and visual question answering. However, building VL models requires substantial hardware resources, where efficiency is restricted by two key factors: the extended input sequence of the language model with vision features demands more computational operations, and a large number of additional learnable parameters increase memory complexity. These challenges significantly restrict the broader applicability of such models. To bridge this gap, we propose ADEM-VL, an efficient vision-language method that tunes VL models based on pretrained large language models (LLMs) by adopting a parameter-free cross-attention mechanism for similarity measurements in multimodal fusion. This approach only requires embedding vision features into the language space, significantly reducing the number of trainable parameters and accelerating both training and inference speeds. To enhance representation learning in fusion module, we introduce an efficient multiscale feature generation scheme that requires only a single forward pass through the vision encoder. Moreover, we propose an adaptive fusion scheme that dynamically discards less relevant visual information for each text token based on its attention score. This ensures that the fusion process prioritizes the most pertinent visual features. With experiments on various tasks including visual question answering, image captioning, and instruction-following, we demonstrate that our framework outperforms existing approaches. Specifically, our method surpasses existing methods by an average accuracy of 0.77% on ScienceQA dataset, with reduced training and inference latency, demonstrating the superiority of our framework. The code is available at https://github.com/Hao840/ADEM-VL.

[Arxiv](https://arxiv.org/abs/2410.17779)
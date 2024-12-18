# ASAP：推进语义对齐有助于多模态操作的检测与定位

发布时间：2024年12月17日

`LLM应用` `多模态媒体` `图像检测`

> ASAP: Advancing Semantic Alignment Promotes Multi-Modal Manipulation Detecting and Grounding

# 摘要

> 我们推出了 ASAP 这一新框架，用于检测和定位多模态媒体操纵（DGM4）。深入探究后发现，图像与文本间精准的细粒度跨模态语义对齐，对于准确检测和定位操纵至关重要。但现有的 DGM4 方法鲜有关注跨模态对齐，这阻碍了操纵检测精度的进一步提升。为解决此问题，本工作致力于推进语义对齐学习以推动该任务。具体而言，我们借助现成的多模态大型语言模型（MLLMs）和大型语言模型（LLMs）构建成对的图像 - 文本对，尤其是针对被操纵的实例。接着，开展跨模态对齐学习以强化语义对齐。除了明确的辅助线索，我们还进一步设计了操纵引导的交叉注意力（MGCA），为增强操纵感知提供隐性引导。在训练时有基准真相可用，MGCA 促使模型更关注被操纵的组件，而弱化正常组件，增强了模型捕捉操纵的能力。在 DGM4 数据集上进行了大量实验，结果表明我们的模型能大幅超越对比方法。

> We present ASAP, a new framework for detecting and grounding multi-modal media manipulation (DGM4).Upon thorough examination, we observe that accurate fine-grained cross-modal semantic alignment between the image and text is vital for accurately manipulation detection and grounding. While existing DGM4 methods pay rare attention to the cross-modal alignment, hampering the accuracy of manipulation detecting to step further. To remedy this issue, this work targets to advance the semantic alignment learning to promote this task. Particularly, we utilize the off-the-shelf Multimodal Large-Language Models (MLLMs) and Large Language Models (LLMs) to construct paired image-text pairs, especially for the manipulated instances. Subsequently, a cross-modal alignment learning is performed to enhance the semantic alignment. Besides the explicit auxiliary clues, we further design a Manipulation-Guided Cross Attention (MGCA) to provide implicit guidance for augmenting the manipulation perceiving. With the grounding truth available during training, MGCA encourages the model to concentrate more on manipulated components while downplaying normal ones, enhancing the model's ability to capture manipulations. Extensive experiments are conducted on the DGM4 dataset, the results demonstrate that our model can surpass the comparison method with a clear margin.

[Arxiv](https://arxiv.org/abs/2412.12718)
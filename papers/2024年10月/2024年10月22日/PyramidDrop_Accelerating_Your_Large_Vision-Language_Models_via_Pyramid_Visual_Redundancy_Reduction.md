# PyramidDrop: 利用金字塔视觉冗余减少技术加速大型视觉语言模型

发布时间：2024年10月22日

`LLM应用

**理由**：这篇论文主要讨论了在大型视觉语言模型（LVLMs）中如何通过减少图像token数量来提升训练和推理效率，同时保持模型性能。这属于对大型语言模型（LLM）在实际应用中的优化和改进，因此应归类为LLM应用。` `计算机视觉`

> PyramidDrop: Accelerating Your Large Vision-Language Models via Pyramid Visual Redundancy Reduction

# 摘要

> 在大型视觉语言模型（LVLMs）中，图像作为输入承载了丰富的信息。正如“一图胜千言”所言，当前LVLMs中表示单张图像可能需要数百甚至数千个token，导致计算成本随图像分辨率呈二次方增长，严重影响训练和推理效率。以往的方法试图在LVLMs的早期层减少图像token数量，但不可避免地丢失关键信息，降低模型性能。为解决这一问题，我们通过实证研究发现，浅层中所有视觉token对LVLMs都至关重要，而深层中token冗余逐渐增加。为此，我们提出了PyramidDrop，一种视觉冗余减少策略，能在性能损失可忽略的情况下提升训练和推理效率。具体而言，我们将LVLM划分为多个阶段，并在每个阶段结束时按预定义比例丢弃部分图像token，形成金字塔状的视觉token。丢弃基于轻量级相似性计算，时间开销极低。实验表明，PyramidDrop在LLaVA-NeXT上实现了40%的训练时间加速和55%的推理FLOPs加速，且性能相当。此外，PyramidDrop还可作为即插即用的推理加速策略，无需训练，性能优于同类方法且推理成本更低。我们希望PyramidDrop的见解和方法能激发未来研究，进一步探索图像token在LVLMs中的作用。

> In large vision-language models (LVLMs), images serve as inputs that carry a wealth of information. As the idiom "A picture is worth a thousand words" implies, representing a single image in current LVLMs can require hundreds or even thousands of tokens. This results in significant computational costs, which grow quadratically as input image resolution increases, thereby severely impacting the efficiency of both training and inference. Previous approaches have attempted to reduce the number of image tokens either before or within the early layers of LVLMs. However, these strategies inevitably result in the loss of crucial image information, ultimately diminishing model performance. To address this challenge, we conduct an empirical study revealing that all visual tokens are necessary for LVLMs in the shallow layers, and token redundancy progressively increases in the deeper layers of the model. To this end, we propose PyramidDrop, a visual redundancy reduction strategy for LVLMs to boost their efficiency in both training and inference with neglectable performance loss. Specifically, we partition the LVLM into several stages and drop part of the image tokens at the end of each stage with a pre-defined ratio, creating pyramid-like visual tokens across model layers. The dropping is based on a lightweight similarity calculation with a negligible time overhead. Extensive experiments demonstrate that PyramidDrop can achieve a 40% training time and 55% inference FLOPs acceleration of LLaVA-NeXT with comparable performance. Besides, the PyramidDrop could also serve as a plug-and-play strategy for inference acceleration without training, with better performance and lower inference cost than counterparts. We hope that the insights and approach introduced by PyramidDrop will inspire future research to further investigate the role of image tokens in LVLMs.

[Arxiv](https://arxiv.org/abs/2410.17247)
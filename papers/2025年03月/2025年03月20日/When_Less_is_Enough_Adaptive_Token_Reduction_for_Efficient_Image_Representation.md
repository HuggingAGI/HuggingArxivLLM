# # 摘要  
少即是足：自适应标记缩减实现高效图像表示

发布时间：2025年03月20日

`LLM应用` `视觉处理` `多模态剪枝`

> When Less is Enough: Adaptive Token Reduction for Efficient Image Representation

# 摘要

> 视觉编码器生成大量视觉标记，这些标记信息丰富却计算需求高昂。这引出一个关键问题：所有标记是否同等重要，还是部分标记可被舍弃以降低计算成本而不影响质量？在本文中，我们提出一种新方法，基于“较不重要的特征可从更重要的特征中重建”的理念，来确定特征的价值。我们通过结合自动编码器与Gumbel-Softmax选择机制实现这一概念，从而识别并保留最有信息量的视觉标记。为了验证我们的方法，我们将LLaVA-NeXT模型分别使用我们方法选择的特征和随机选择的特征进行了性能对比。结果显示，在基于OCR的任务中，超过50%的视觉上下文可被移除，性能损失极小；而在通用领域任务中，即使随机保留30%的标记，性能亦可与完整标记集相媲美。我们的研究为自适应、高效的多模态剪枝提供了新方向，助力实现可扩展、低开销的推理，同时保持性能不减。

> Vision encoders typically generate a large number of visual tokens, providing information-rich representations but significantly increasing computational demands. This raises the question of whether all generated tokens are equally valuable or if some of them can be discarded to reduce computational costs without compromising quality. In this paper, we introduce a new method for determining feature utility based on the idea that less valuable features can be reconstructed from more valuable ones. We implement this concept by integrating an autoencoder with a Gumbel-Softmax selection mechanism, that allows identifying and retaining only the most informative visual tokens. To validate our approach, we compared the performance of the LLaVA-NeXT model, using features selected by our method with randomly selected features. We found that on OCR-based tasks, more than 50% of the visual context can be removed with minimal performance loss, whereas randomly discarding the same proportion of features significantly affects the model capabilities. Furthermore, in general-domain tasks, even randomly retaining only 30% of tokens achieves performance comparable to using the full set of visual tokens. Our results highlight a promising direction towards adaptive and efficient multimodal pruning that facilitates scalable and low-overhead inference without compromising performance.

[Arxiv](https://arxiv.org/abs/2503.16660)
# VLMs 为何在空间推理上如此吃力？从注意力机制视角看关注区域

发布时间：2025年03月03日

`LLM应用` `计算机视觉`

> Why Is Spatial Reasoning Hard for VLMs? An Attention Mechanism Perspective on Focus Areas

# 摘要

> 大型视觉语言模型（VLMs）在空间推理任务中表现欠佳，即使是识别两个物体之间的简单空间关系，如“在...下面”或“在...后面”，也充满挑战。我们从机制可解释性的角度深入研究这一问题，通过分析模型内部状态，探讨图像与文本令牌的交互。通过追踪中间层中的图像注意力分布，我们发现成功的空间推理与模型对物体位置的注意力对齐能力密切相关，尤其在熟悉与不熟悉的空间关系间存在显著差异。基于此，我们提出ADAPTVIS方法，利用推理时的置信度分数，在高置信度时增强关键区域的关注，而在低置信度时扩展注意力窗口以考虑更广泛上下文。这一无需训练的解码方法在WhatsUp和VSR等基准测试中表现出显著提升（如绝对提升高达50个百分点），且计算成本极低。我们已将代码和数据公开发布到GitHub（https://github.com/shiqichen17/AdaptVis），供研究使用。

> Large Vision Language Models (VLMs) have long struggled with spatial reasoning tasks. Surprisingly, even simple spatial reasoning tasks, such as recognizing "under" or "behind" relationships between only two objects, pose significant challenges for current VLMs. In this work, we study the spatial reasoning challenge from the lens of mechanistic interpretability, diving into the model's internal states to examine the interactions between image and text tokens. By tracing attention distribution over the image through out intermediate layers, we observe that successful spatial reasoning correlates strongly with the model's ability to align its attention distribution with actual object locations, particularly differing between familiar and unfamiliar spatial relationships. Motivated by these findings, we propose ADAPTVIS based on inference-time confidence scores to sharpen the attention on highly relevant regions when confident, while smoothing and broadening the attention window to consider a wider context when confidence is lower. This training-free decoding method shows significant improvement (e.g., up to a 50 absolute point improvement) on spatial reasoning benchmarks such as WhatsUp and VSR with negligible cost. We make code and data publicly available for research purposes at https://github.com/shiqichen17/AdaptVis.

[Arxiv](https://arxiv.org/abs/2503.01773)
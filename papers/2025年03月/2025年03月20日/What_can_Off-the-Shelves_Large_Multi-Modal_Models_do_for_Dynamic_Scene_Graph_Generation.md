# # 现成的大型多模态模型能为动态场景图生成带来什么？

发布时间：2025年03月20日

`其他` `计算机视觉` `多模态模型`

> What can Off-the-Shelves Large Multi-Modal Models do for Dynamic Scene Graph Generation?

# 摘要

> 视频动态场景图生成（DSGG）是计算机视觉领域的一个重要挑战。现有方法通常侧重于复杂架构设计，并在评估中仅关注召回率。然而，我们深入分析后发现，现有DSGG方法存在三个关键问题：严重的精确率-召回率权衡、缺乏对三元组重要性的认识，以及不恰当的评估协议。另一方面，大型多模态模型（LMMs）在视频理解方面展现出强大能力，但尚未在细粒度、逐帧理解任务（如DSGG）上得到充分应用。本研究首次系统分析了视频LMMs在DSGG方面的潜力。我们发现，即使采用简单的解码器结构，LMMs也能成为先进的场景图生成器，有效解决上述问题，并且仅需少量微调（5-10%的训练数据）。

> Dynamic Scene Graph Generation (DSGG) for videos is a challenging task in computer vision. While existing approaches often focus on sophisticated architectural design and solely use recall during evaluation, we take a closer look at their predicted scene graphs and discover three critical issues with existing DSGG methods: severe precision-recall trade-off, lack of awareness on triplet importance, and inappropriate evaluation protocols. On the other hand, recent advances of Large Multimodal Models (LMMs) have shown great capabilities in video understanding, yet they have not been tested on fine-grained, frame-wise understanding tasks like DSGG. In this work, we conduct the first systematic analysis of Video LMMs for performing DSGG. Without relying on sophisticated architectural design, we show that LMMs with simple decoder-only structure can be turned into State-of-the-Art scene graph generators that effectively overcome the aforementioned issues, while requiring little finetuning (5-10% training data).

[Arxiv](https://arxiv.org/abs/2503.15846)
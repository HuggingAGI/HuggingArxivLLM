# iLLaVA：在大型多模态模型里，一张图像的价值还不到 1/3 的输入标记。

发布时间：2024年12月09日

`LLM应用` `计算机视觉` `人工智能`

> iLLaVA: An Image is Worth Fewer Than 1/3 Input Tokens in Large Multimodal Models

# 摘要

> 在本文中，我们介绍了 iLLaVA 这一简便方法，它能无缝应用于当下的大型视觉语言模型（LVLMs），在几乎无损模型性能的前提下大幅提升吞吐量，无需再进行训练。iLLaVA 借助精准且快速的算法来查找并逐步融合冗余标记，仅一步就能融合数百个标记。尽管此前一些方法已尝试在推理阶段直接修剪或融合标记以加速模型，但我们的方法凭借两个关键设计在性能和吞吐量上表现卓越。其一，多数先前的方法仅致力于节省大型语言模型（LLMs）的计算量，而我们的方法能加快 LVLMs 中图像编码器和 LLMs 的前向传播，这两者在推理时均占据大量时间。其二，我们的方法将修剪标记中的有益信息回收到现有标记中，避免像以往方法那样直接丢弃上下文标记从而导致性能损失。iLLaVA 能让吞吐量近乎翻倍，内存成本减半，在涵盖 7B、13B 和 34B 等不同规模的模型中，性能仅下降 0.2％ - 0.5％。在包括单图像、多图像和视频等不同领域的任务中，iLLaVA 展现出强大的泛化能力，效率始终可观。最后，我们提供了丰富的可视化内容，展示 iLLaVA 每一步的融合过程，揭示了 LVLMs 中计算资源的分布情况。代码可在 https://github.com/hulianyuyy/iLLaVA 获取。

> In this paper, we introduce iLLaVA, a simple method that can be seamlessly deployed upon current Large Vision-Language Models (LVLMs) to greatly increase the throughput with nearly lossless model performance, without a further requirement to train. iLLaVA achieves this by finding and gradually merging the redundant tokens with an accurate and fast algorithm, which can merge hundreds of tokens within only one step. While some previous methods have explored directly pruning or merging tokens in the inference stage to accelerate models, our method excels in both performance and throughput by two key designs. First, while most previous methods only try to save the computations of Large Language Models (LLMs), our method accelerates the forward pass of both image encoders and LLMs in LVLMs, which both occupy a significant part of time during inference. Second, our method recycles the beneficial information from the pruned tokens into existing tokens, which avoids directly dropping context tokens like previous methods to cause performance loss. iLLaVA can nearly 2$\times$ the throughput, and reduce the memory costs by half with only a 0.2\% - 0.5\% performance drop across models of different scales including 7B, 13B and 34B. On tasks across different domains including single-image, multi-images and videos, iLLaVA demonstrates strong generalizability with consistently promising efficiency. We finally offer abundant visualizations to show the merging processes of iLLaVA in each step, which show insights into the distribution of computing resources in LVLMs. Code is available at https://github.com/hulianyuyy/iLLaVA.

[Arxiv](https://arxiv.org/abs/2412.06263)
# LLaVA-MLB：缓解并善用注意力偏置，打造无训练的视频LLMs

发布时间：2025年03月14日

`LLM应用

理由：这篇论文讨论了如何利用预训练的图像LLMs来处理视频内容，提出了一种无需额外训练的方法，并通过改进注意力机制来提升视频理解能力。这属于LLM的应用场景，因此归类为LLM应用。` `视频处理`

> LLaVA-MLB: Mitigating and Leveraging Attention Bias for Training-Free Video LLMs

# 摘要

> 无需训练的视频大型语言模型（LLMs）借助预训练的图像LLMs处理视频内容，无需额外训练。然而，在图像LLMs的token限制下，保留关键的视觉和时间信息颇具挑战性。为此，我们提出了一种基于LLM注意力分数的两阶段方法：先压缩视频序列，再扩展序列。但在压缩阶段，图像LLMs往往会对视频序列产生位置注意力偏差，过度关注后期帧，导致早期帧信息未被充分利用。为了解决这一问题，我们提出了网格化注意力池化来保留时空结构，并引入视觉摘要尾部有效利用这种偏差，从而在序列扩展时提升整体视频理解能力。通过这种方法，我们开发的LLaVA-MLB成功地缓解并利用了注意力偏差，使冻结的图像LLM能够实现对视频内容的详细理解。实验结果表明，我们的方法在多个基准测试中均优于现有最佳方法，展现出更卓越的效率和准确性。我们的代码即将开源。

> Training-free video large language models (LLMs) leverage pretrained Image LLMs to process video content without the need for further training. A key challenge in such approaches is the difficulty of retaining essential visual and temporal information, constrained by the token limits in Image LLMs. To address this, we propose a two-stage method for selecting query-relevant tokens based on the LLM attention scores: compressing the video sequence and then expanding the sequence. However, during the compression stage, Image LLMs often exhibit a positional attention bias in video sequences, where attention is overly concentrated on later frames, causing early-frame information to be underutilized. To alleviate this attention bias during sequence compression, we propose Gridded Attention Pooling for preserving spatiotemporal structure. Additionally, we introduce Visual Summarization Tail to effectively utilize this bias, facilitating overall video understanding during sequence expansion. In this way, our method effectively Mitigates and Leverages attention Bias (LLaVA-MLB), enabling the frozen Image LLM for detailed video understanding. Experiments on several benchmarks demonstrate that our approach outperforms state-of-the-art methods, achieving superior performance in both efficiency and accuracy. Our code will be released.

[Arxiv](https://arxiv.org/abs/2503.11205)
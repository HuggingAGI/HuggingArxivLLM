# Dynamic-VLM: 针对 VideoLLM 的简单动态视觉标记压缩技术

发布时间：2024年12月12日

`LLM应用`

> Dynamic-VLM: Simple Dynamic Visual Token Compression for VideoLLM

# 摘要

> 大型视觉语言模型（LVLMs）用于图像和视频分析是个令人兴奋且发展迅猛的领域。近些年来，用于微调图像理解的高质量图像-文本数据集大幅增长，然而针对视频的可比数据集仍很缺乏。另外，许多 VideoLLMs 是单图像 VLM 的延伸，或许难以有效应对长视频的复杂性。在此研究中，我们引入了一个由专有模型创建的大规模合成数据集，借助精心设计的提示来解决各类问题。我们还探索了一种动态视觉令牌压缩架构，在计算效率和性能之间达成平衡。我们提出的\model{}在各种视频任务中取得了顶尖成果，展现出出色的泛化能力，为多图像理解设定了新基准。值得一提的是，\model{}在 VideoMME 上比 LLaVA-OneVision 绝对提升了 2.7％，在 MuirBench 上提升了 10.7％。代码可在 https://github.com/Hon-Wong/ByteVideoLLM 获取。

> The application of Large Vision-Language Models (LVLMs) for analyzing images and videos is an exciting and rapidly evolving field. In recent years, we've seen significant growth in high-quality image-text datasets for fine-tuning image understanding, but there is still a lack of comparable datasets for videos. Additionally, many VideoLLMs are extensions of single-image VLMs, which may not efficiently handle the complexities of longer videos. In this study, we introduce a large-scale synthetic dataset created from proprietary models, using carefully designed prompts to tackle a wide range of questions. We also explore a dynamic visual token compression architecture that strikes a balance between computational efficiency and performance. Our proposed \model{} achieves state-of-the-art results across various video tasks and shows impressive generalization, setting new baselines in multi-image understanding. Notably, \model{} delivers an absolute improvement of 2.7\% over LLaVA-OneVision on VideoMME and 10.7\% on MuirBench. Codes are available at https://github.com/Hon-Wong/ByteVideoLLM

[Arxiv](https://arxiv.org/abs/2412.09530)
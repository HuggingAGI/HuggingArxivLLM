# ViMGuard: 视频虚假信息防护的多模态新系统

发布时间：2024年10月21日

`LLM应用

理由：这篇论文主要讨论了如何利用深度学习架构（视频掩码自编码器，ViMGuard）来检测社交媒体和短视频中的错误信息。虽然论文中提到了检索增强生成系统（RAG），但整体上，论文的核心是应用大型语言模型（LLM）来解决实际问题（即SFV中的错误信息检测），因此应归类为“LLM应用”。` `社交媒体` `事实核查`

> ViMGuard: A Novel Multi-Modal System for Video Misinformation Guarding

# 摘要

> 社交媒体和短视频（SFV）的兴起为错误信息的传播提供了温床。随着大型语言模型的出现，大量研究致力于通过自动虚假声明检测来解决文本中的错误信息问题。然而，自动检测SFV中的错误信息仍是一个复杂且未被充分研究的领域。与单模态的文本不同，SFV包含文字、视觉和非语言音频三种模态。我们提出了首个能够通过分析SFV所有三种模态来进行事实核查的深度学习架构——视频掩码自编码器（ViMGuard）。ViMGuard采用双组件系统：首先，视频和音频掩码自编码器分析视频的视觉和非语言音频元素，判断其是否具有信息性意图；若确定其意图为信息性，则通过检索增强生成系统验证口语文字的事实准确性。评估结果显示，ViMGuard的表现优于三种尖端事实核查工具，为SFV事实核查设定了新标准，并为社交媒体上的可信新闻迈出了重要一步。为促进进一步测试和迭代，ViMGuard已部署为Chrome扩展，并在GitHub上开源所有代码。

> The rise of social media and short-form video (SFV) has facilitated a breeding ground for misinformation. With the emergence of large language models, significant research has gone into curbing this misinformation problem with automatic false claim detection for text. Unfortunately, the automatic detection of misinformation in SFV is a more complex problem that remains largely unstudied. While text samples are monomodal (only containing words), SFVs comprise three different modalities: words, visuals, and non-linguistic audio. In this work, we introduce Video Masked Autoencoders for Misinformation Guarding (ViMGuard), the first deep-learning architecture capable of fact-checking an SFV through analysis of all three of its constituent modalities. ViMGuard leverages a dual-component system. First, Video and Audio Masked Autoencoders analyze the visual and non-linguistic audio elements of a video to discern its intention; specifically whether it intends to make an informative claim. If it is deemed that the SFV has informative intent, it is passed through our second component: a Retrieval Augmented Generation system that validates the factual accuracy of spoken words. In evaluation, ViMGuard outperformed three cutting-edge fact-checkers, thus setting a new standard for SFV fact-checking and marking a significant stride toward trustworthy news on social platforms. To promote further testing and iteration, VimGuard was deployed into a Chrome extension and all code was open-sourced on GitHub.

[Arxiv](https://arxiv.org/abs/2410.16592)
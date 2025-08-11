# CLIPin：用于多模态语义对齐的非对比式CLIP插件

发布时间：2025年08月08日

`其他

理由：这篇论文主要探讨了对比语言-图像预训练（CLIP）模型的改进，提出了一种名为CLIPin的插件，用于提升跨模态语义对齐。虽然涉及语言模型，但其核心内容属于跨模态学习和模型改进，不属于特定的LLM应用或LLM理论，因此归类为其他。` `计算机视觉`

> CLIPin: A Non-contrastive Plug-in to CLIP for Multimodal Semantic Alignment

# 摘要

> 大规模自然图像-文本数据集，尤其是从网络自动收集的，常因弱监督导致语义对齐松散；而医学数据集则通常具有高跨模态相关性但内容多样性较低。这些特性给对比语言-图像预训练（CLIP）带来了共同挑战：它们限制了模型学习稳健且通用表征的能力。本研究提出了一种名为CLIPin的统一非对比式插件，可无缝集成到CLIP风格架构中，以提升跨模态语义对齐效果。通过提供更强的监督信号并增强对齐稳健性，CLIPin助力模型性能提升。此外，我们为图像和文本模态分别设计了两个共享预投影器，以在参数折衷的基础上促进对比学习与非对比学习的融合。在多样化的下游任务中进行的广泛实验验证了CLIPin作为即插即用组件的有效性和通用性，其可与多种对比框架兼容。代码可在https://github.com/T6Yang/CLIPin获取。

> Large-scale natural image-text datasets, especially those automatically collected from the web, often suffer from loose semantic alignment due to weak supervision, while medical datasets tend to have high cross-modal correlation but low content diversity. These properties pose a common challenge for contrastive language-image pretraining (CLIP): they hinder the model's ability to learn robust and generalizable representations. In this work, we propose CLIPin, a unified non-contrastive plug-in that can be seamlessly integrated into CLIP-style architectures to improve multimodal semantic alignment, providing stronger supervision and enhancing alignment robustness. Furthermore, two shared pre-projectors are designed for image and text modalities respectively to facilitate the integration of contrastive and non-contrastive learning in a parameter-compromise manner. Extensive experiments on diverse downstream tasks demonstrate the effectiveness and generality of CLIPin as a plug-and-play component compatible with various contrastive frameworks. Code is available at https://github.com/T6Yang/CLIPin.

[Arxiv](https://arxiv.org/abs/2508.06434)
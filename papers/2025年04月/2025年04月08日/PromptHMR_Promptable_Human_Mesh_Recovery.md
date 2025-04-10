# PromptHMR：可提示式人体网格恢复

发布时间：2025年04月08日

`其他` `计算机视觉` `智能视频分析`

> PromptHMR: Promptable Human Mesh Recovery

# 摘要

> 人体姿势和形状（HPS）估计在拥挤场景、人际互动及单视图重建等复杂情境下面临诸多挑战。现有方法缺乏有效机制整合辅助信息以提升重建精度，且在利用场景上下文方面存在局限：最精确的方法依赖裁剪后的人体检测，而处理整张图像的方法则常因检测失败导致精度下降。尽管基于语言的方法通过大型语言或视觉-语言模型探索了HPS推理，但其准确性仍显著低于现有水平。我们提出了一种基于Transformer的PromptHMR方法，通过空间和语义提示重新定义HPS估计。该方法处理完整图像以保留场景上下文，支持多种输入模式：如边界框和掩膜等空间提示，以及语言描述或交互标签等语义提示。PromptHMR在复杂场景中表现出色：在拥挤场景中从面部大小的边界框中识别人物，通过语言描述优化体型估计，建模人际互动，并在视频中生成连贯动作。实验结果表明，PromptHMR不仅达到了最先进的性能，还实现了对HPS估计过程的灵活控制。

> Human pose and shape (HPS) estimation presents challenges in diverse scenarios such as crowded scenes, person-person interactions, and single-view reconstruction. Existing approaches lack mechanisms to incorporate auxiliary "side information" that could enhance reconstruction accuracy in such challenging scenarios. Furthermore, the most accurate methods rely on cropped person detections and cannot exploit scene context while methods that process the whole image often fail to detect people and are less accurate than methods that use crops. While recent language-based methods explore HPS reasoning through large language or vision-language models, their metric accuracy is well below the state of the art. In contrast, we present PromptHMR, a transformer-based promptable method that reformulates HPS estimation through spatial and semantic prompts. Our method processes full images to maintain scene context and accepts multiple input modalities: spatial prompts like bounding boxes and masks, and semantic prompts like language descriptions or interaction labels. PromptHMR demonstrates robust performance across challenging scenarios: estimating people from bounding boxes as small as faces in crowded scenes, improving body shape estimation through language descriptions, modeling person-person interactions, and producing temporally coherent motions in videos. Experiments on benchmarks show that PromptHMR achieves state-of-the-art performance while offering flexible prompt-based control over the HPS estimation process.

[Arxiv](https://arxiv.org/abs/2504.06397)
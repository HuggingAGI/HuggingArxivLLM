# VideoDPO：实现视频扩散生成的全偏好对齐

发布时间：2024年12月18日

`LLM应用` `生成模型`

> VideoDPO: Omni-Preference Alignment for Video Diffusion Generation

# 摘要

> 近期生成扩散模型的进步极大地推动了文本转视频的生成。尽管基于大规模、多样化数据集训练的文本到视频模型能产生多样的输出，但这些生成结果往往偏离用户偏好，这凸显了对预训练模型进行偏好对齐的必要性。尽管直接偏好优化（DPO）在语言和图像生成领域已取得显著成效，但我们开创性地将其应用于视频扩散模型，并通过一些关键调整提出了 VideoDPO 流程。不同于以往仅专注于（i）视觉质量或（ii）文本与视频的语义对齐的图像对齐方法，我们综合考虑了这两个维度，并相应构建了一个偏好分数，称为 OmniScore。我们设计了一个流程，基于所提出的 OmniScore 自动收集偏好对数据，并且发现依据该分数对这些数据对进行重新加权会对整体偏好对齐产生显著影响。我们的实验在视觉质量和语义对齐方面均有大幅改进，确保任何偏好方面都不被忽略。代码和数据将在 https://videodpo.github.io/ 分享。

> Recent progress in generative diffusion models has greatly advanced text-to-video generation. While text-to-video models trained on large-scale, diverse datasets can produce varied outputs, these generations often deviate from user preferences, highlighting the need for preference alignment on pre-trained models. Although Direct Preference Optimization (DPO) has demonstrated significant improvements in language and image generation, we pioneer its adaptation to video diffusion models and propose a VideoDPO pipeline by making several key adjustments. Unlike previous image alignment methods that focus solely on either (i) visual quality or (ii) semantic alignment between text and videos, we comprehensively consider both dimensions and construct a preference score accordingly, which we term the OmniScore. We design a pipeline to automatically collect preference pair data based on the proposed OmniScore and discover that re-weighting these pairs based on the score significantly impacts overall preference alignment. Our experiments demonstrate substantial improvements in both visual quality and semantic alignment, ensuring that no preference aspect is neglected. Code and data will be shared at https://videodpo.github.io/.

[Arxiv](https://arxiv.org/abs/2412.14167)
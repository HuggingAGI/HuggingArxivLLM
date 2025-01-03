# ViCaS: 一个结合整体与像素级视频理解的数据集，采用带基础分割的标题

发布时间：2024年12月12日

`LLM应用

理由：这篇论文主要讨论了多模态大型语言模型（MLLMs）在视频理解中的应用，特别是视频字幕生成和问答任务，以及像素级精确的分割任务。论文引入了ViCaS数据集，并提出了评估方法和模型架构，这些都是针对LLM在实际应用中的改进和优化。因此，这篇论文应归类为LLM应用。` `视频理解` `计算机视觉`

> ViCaS: A Dataset for Combining Holistic and Pixel-level Video Understanding using Captions with Grounded Segmentation

# 摘要

> # 摘要
多模态大型语言模型（MLLMs）的最新进展推动了视频理解研究的扩展，主要集中在视频字幕生成和问答等高级任务上。然而，针对密集的、像素级精确的分割任务的研究相对较少，这些任务通常涉及类别引导或基于参考的对象分割。尽管这两个方向对于开发具备人类水平视频理解能力的模型都至关重要，但它们大多独立发展，拥有不同的基准和架构。本文通过引入ViCaS数据集，旨在统一这些研究方向。ViCaS包含数千个具有挑战性的视频，每个视频都配有详细的人工编写字幕和针对多个对象的、时间一致且像素级精确的掩码，并带有短语定位。我们的基准评估模型在整体/高级理解和语言引导的像素级精确分割方面的表现。我们还提出了经过验证的评估方法，并设计了一种能够应对该基准的有效模型架构。项目页面：https://ali2500.github.io/vicas-project/

> Recent advances in multimodal large language models (MLLMs) have expanded research in video understanding, primarily focusing on high-level tasks such as video captioning and question-answering. Meanwhile, a smaller body of work addresses dense, pixel-precise segmentation tasks, which typically involve category-guided or referral-based object segmentation. Although both research directions are essential for developing models with human-level video comprehension, they have largely evolved separately, with distinct benchmarks and architectures. This paper aims to unify these efforts by introducing ViCaS, a new dataset containing thousands of challenging videos, each annotated with detailed, human-written captions and temporally consistent, pixel-accurate masks for multiple objects with phrase grounding. Our benchmark evaluates models on both holistic/high-level understanding and language-guided, pixel-precise segmentation. We also present carefully validated evaluation measures and propose an effective model architecture that can tackle our benchmark. Project page: https://ali2500.github.io/vicas-project/

[Arxiv](https://arxiv.org/abs/2412.09754)
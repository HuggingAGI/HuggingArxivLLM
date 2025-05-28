# VLM-3R：基于指令对齐的三维重建增强的视觉语言模型

发布时间：2025年05月26日

`LLM应用

摘要讨论了大型多模态模型（LMMs）在理解3D场景中的应用，提出了一个名为VLM-3R的框架，用于单目视频输入的3D空间理解和推理。该研究专注于将视觉-语言模型应用于3D重建和时空推理，属于LLM在具体任务中的应用。` `3D重建` `空间推理`

> VLM-3R: Vision-Language Models Augmented with Instruction-Aligned 3D Reconstruction

# 摘要

> 大型多模态模型（LMMs）在2D图像和视频领域的突破激发了将这些模型扩展到理解3D场景的兴趣，目标是实现类似人类的视觉-空间智能。然而，要达到与人类能力相当的深度空间理解，模型编码和数据获取方面仍面临重大挑战。现有方法通常依赖外部深度传感器来捕捉几何信息，或者使用现成算法预先构建3D地图，这限制了它们的扩展性，尤其是在面对普遍存在的单目视频输入和时间敏感型应用时。本研究中，我们引入了VLM-3R，这是一个整合了3D重建指令微调的视觉-语言模型（VLMs）统一框架。VLM-3R通过几何编码器处理单目视频帧，生成表示空间理解的隐式3D令牌。借助我们的空间-视觉-视角融合方法以及超过20万条精心策划的3D重建指令微调问答对，VLM-3R能够有效地将现实世界的空间语境与语言指令对齐。这使得单目3D空间辅助和具身推理成为可能。为了促进对时间推理的评估，我们引入了Vision-Spatial-Temporal Intelligence基准，该基准包含超过138.6万个问答对，涵盖五个关注动态空间关系的不同任务。大量实验表明，我们的模型VLM-3R不仅支持强大的视觉-空间推理，还能理解时序3D上下文的变化，在准确性和扩展性方面均表现优异。

> The rapid advancement of Large Multimodal Models (LMMs) for 2D images and videos has motivated extending these models to understand 3D scenes, aiming for human-like visual-spatial intelligence. Nevertheless, achieving deep spatial understanding comparable to human capabilities poses significant challenges in model encoding and data acquisition. Existing methods frequently depend on external depth sensors for geometry capture or utilize off-the-shelf algorithms for pre-constructing 3D maps, thereby limiting their scalability, especially with prevalent monocular video inputs and for time-sensitive applications. In this work, we introduce VLM-3R, a unified framework for Vision-Language Models (VLMs) that incorporates 3D Reconstructive instruction tuning. VLM-3R processes monocular video frames by employing a geometry encoder to derive implicit 3D tokens that represent spatial understanding. Leveraging our Spatial-Visual-View Fusion and over 200K curated 3D reconstructive instruction tuning question-answer (QA) pairs, VLM-3R effectively aligns real-world spatial context with language instructions. This enables monocular 3D spatial assistance and embodied reasoning. To facilitate the evaluation of temporal reasoning, we introduce the Vision-Spatial-Temporal Intelligence benchmark, featuring over 138.6K QA pairs across five distinct tasks focused on evolving spatial relationships. Extensive experiments demonstrate that our model, VLM-3R, not only facilitates robust visual-spatial reasoning but also enables the understanding of temporal 3D context changes, excelling in both accuracy and scalability.

[Arxiv](https://arxiv.org/abs/2505.20279)
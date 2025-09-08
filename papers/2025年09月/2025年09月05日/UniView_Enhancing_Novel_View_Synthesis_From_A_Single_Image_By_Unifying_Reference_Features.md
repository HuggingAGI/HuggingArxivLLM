# UniView：通过统一参考特征增强单张图像的新视角合成

发布时间：2025年09月05日

`LLM应用` `媒体与娱乐`

> UniView: Enhancing Novel View Synthesis From A Single Image By Unifying Reference Features

# 摘要

> 从单张图像合成新视角的任务极具不适定性，因为未观测区域存在多种可能的解释。当前多数方法往往依赖模糊先验和输入视角附近的插值来生成未观测区域，这常导致严重失真。为解决这一局限，我们提出名为UniView的新型模型，它可借助相似物体的参考图像，在视角合成时提供强先验信息。具体而言，我们构建了检索与增强系统，并利用多模态大型语言模型（MLLM）辅助筛选符合要求的参考图像。此外，我们引入带多级隔离层的即插即用适配器模块，动态生成目标视角的参考特征。同时，为保留原始输入图像的细节，我们设计了解耦三重注意力机制，可有效对齐并将多分支特征整合到合成过程中。大量实验表明，UniView显著提升了新视角合成性能，且在挑战性数据集上超越了现有最先进方法。

> The task of synthesizing novel views from a single image is highly ill-posed due to multiple explanations for unobserved areas. Most current methods tend to generate unseen regions from ambiguity priors and interpolation near input views, which often lead to severe distortions. To address this limitation, we propose a novel model dubbed as UniView, which can leverage reference images from a similar object to provide strong prior information during view synthesis. More specifically, we construct a retrieval and augmentation system and employ a multimodal large language model (MLLM) to assist in selecting reference images that meet our requirements. Additionally, a plug-and-play adapter module with multi-level isolation layers is introduced to dynamically generate reference features for the target views. Moreover, in order to preserve the details of an original input image, we design a decoupled triple attention mechanism, which can effectively align and integrate multi-branch features into the synthesis process. Extensive experiments have demonstrated that our UniView significantly improves novel view synthesis performance and outperforms state-of-the-art methods on the challenging datasets.

[Arxiv](https://arxiv.org/abs/2509.04932)
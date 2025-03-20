# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年03月19日

`LLM应用` `计算机视觉` `合成图像`

> LEGION: Learning to Ground and Explain for Synthetic Image Detection

# 摘要

> 生成技术的迅猛发展如同一把双刃剑。它不仅为人们带来了提升便利的强大力具，同时也引发了诸多社会隐忧。作为防御者，当前的合成图像检测方法往往在可解释性方面表现不足，过于专注于图像篡改检测，而现有数据集则普遍面临生成器过时和标注颗粒度不足的问题。本文推出SynthScars——一个包含12,236张高质量合成图像的多样化数据集，每张图像均附有人类专家标注。该数据集涵盖4种独特图像内容类型、3类合成痕迹，并提供像素级分割、详细文本解释及合成痕迹类别标签的细粒度标注。同时，我们提出LEGION框架（基于多模态大型语言模型的合成图像检测与解释系统），集成了合成痕迹检测、分割和解释功能。基于此能力，我们进一步将LEGION作为控制器，将其嵌入图像优化管道，以指导生成更高质量和更具真实感的图像。大量实验表明，LEGION在多个基准测试中超越现有方法，特别是在SynthScars数据集上，其mIoU和F1分数分别比第二好的传统方法高出3.31%和7.75%。此外，在其指导下生成的优化图像更符合人类审美偏好。相关代码、模型和数据集即将开源。

> The rapid advancements in generative technology have emerged as a double-edged sword. While offering powerful tools that enhance convenience, they also pose significant social concerns. As defenders, current synthetic image detection methods often lack artifact-level textual interpretability and are overly focused on image manipulation detection, and current datasets usually suffer from outdated generators and a lack of fine-grained annotations. In this paper, we introduce SynthScars, a high-quality and diverse dataset consisting of 12,236 fully synthetic images with human-expert annotations. It features 4 distinct image content types, 3 categories of artifacts, and fine-grained annotations covering pixel-level segmentation, detailed textual explanations, and artifact category labels. Furthermore, we propose LEGION (LEarning to Ground and explain for Synthetic Image detectiON), a multimodal large language model (MLLM)-based image forgery analysis framework that integrates artifact detection, segmentation, and explanation. Building upon this capability, we further explore LEGION as a controller, integrating it into image refinement pipelines to guide the generation of higher-quality and more realistic images. Extensive experiments show that LEGION outperforms existing methods across multiple benchmarks, particularly surpassing the second-best traditional expert on SynthScars by 3.31% in mIoU and 7.75% in F1 score. Moreover, the refined images generated under its guidance exhibit stronger alignment with human preferences. The code, model, and dataset will be released.

[Arxiv](https://arxiv.org/abs/2503.15264)
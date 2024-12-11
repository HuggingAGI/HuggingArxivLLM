# DiffSensei：连接多模态大型语言模型与扩散模型，实现定制漫画生成

发布时间：2024年12月10日

`LLM应用` `图像生成`

> DiffSensei: Bridging Multi-Modal LLMs and Diffusion Models for Customized Manga Generation

# 摘要

> 故事可视化，也就是依据文本描述来创作视觉叙事的任务，在文本到图像生成模型的助力下有了进展。不过，这类模型在角色的外观和互动方面，尤其是在多角色场景中，常常缺乏有效的把控。为应对这些局限，我们提出了一项新任务：	extbf{定制漫画生成} ，并引入了 	extbf{DiffSensei} ，这是一个专为生成具有动态多角色控制的漫画而打造的创新框架。DiffSensei 把基于扩散的图像生成器与作为文本适配身份适配器的多模态大型语言模型（MLLM）整合到了一起。我们的方法运用掩码交叉注意力，无缝融合角色特征，无需直接的像素转移就能实现精准的布局控制。另外，基于 MLLM 的适配器会调整角色特征，使其与特定面板的文本提示相契合，能够在角色的表情、姿势和动作方面进行灵活调整。我们还推出了 	extbf{MangaZero} ，这是一个专为该任务定制的大规模数据集，涵盖 43,264 个漫画页面和 427,147 个有注释的面板，支持对连续帧中的各种角色互动和动作进行可视化。大量实验表明，DiffSensei 比现有模型更出色，通过实现文本自适应的角色定制，在漫画生成领域取得了重大突破。项目页面是 https://jianzongwu.github.io/projects/diffsensei/。

> Story visualization, the task of creating visual narratives from textual descriptions, has seen progress with text-to-image generation models. However, these models often lack effective control over character appearances and interactions, particularly in multi-character scenes. To address these limitations, we propose a new task: \textbf{customized manga generation} and introduce \textbf{DiffSensei}, an innovative framework specifically designed for generating manga with dynamic multi-character control. DiffSensei integrates a diffusion-based image generator with a multimodal large language model (MLLM) that acts as a text-compatible identity adapter. Our approach employs masked cross-attention to seamlessly incorporate character features, enabling precise layout control without direct pixel transfer. Additionally, the MLLM-based adapter adjusts character features to align with panel-specific text cues, allowing flexible adjustments in character expressions, poses, and actions. We also introduce \textbf{MangaZero}, a large-scale dataset tailored to this task, containing 43,264 manga pages and 427,147 annotated panels, supporting the visualization of varied character interactions and movements across sequential frames. Extensive experiments demonstrate that DiffSensei outperforms existing models, marking a significant advancement in manga generation by enabling text-adaptable character customization. The project page is https://jianzongwu.github.io/projects/diffsensei/.

[Arxiv](https://arxiv.org/abs/2412.07589)
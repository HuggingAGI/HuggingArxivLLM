# PromptVFX：基于文本驱动的场，实现开放世界中的3D高斯动画效果

发布时间：2025年06月01日

`LLM应用` `视觉效果` `3D内容创作`

> PromptVFX: Text-Driven Fields for Open-World 3D Gaussian Animation

# 摘要

> 视觉效果（VFX）是现代电影、游戏和AR/VR沉浸感的核心。然而，制作3D特效需要专业知识和培训，耗时较长。传统生成式解决方案通常依赖计算密集型方法，如扩散模型，在进行4D推理时速度较慢。我们重新定义3D动画为场预测任务，并引入了一个文本驱动框架，用于推理作用于3D高斯体的时变四维流场。通过利用大型语言模型（LLMs）和视觉-语言模型（VLMs）进行功能生成，我们的方法能够解析任意提示（例如，“让花瓶发出橙光，然后爆炸”），并实时更新3D高斯体的颜色、不透明度和位置。这种设计避免了网格提取、手动或物理模拟等额外开销，使得无论是新手还是专家用户，都能在消费级设备上甚至通过网页浏览器轻松制作体积动画。实验结果表明，简单的文本指令足以生成引人入胜的时变视觉效果，减少了传统建模或高级绑定所需的繁琐工作。因此，我们提供了一条快速、易用的语言驱动3D内容创作途径，为视觉效果的进一步普及铺平了道路。

> Visual effects (VFX) are key to immersion in modern films, games, and AR/VR. Creating 3D effects requires specialized expertise and training in 3D animation software and can be time consuming. Generative solutions typically rely on computationally intense methods such as diffusion models which can be slow at 4D inference. We reformulate 3D animation as a field prediction task and introduce a text-driven framework that infers a time-varying 4D flow field acting on 3D Gaussians. By leveraging large language models (LLMs) and vision-language models (VLMs) for function generation, our approach interprets arbitrary prompts (e.g., "make the vase glow orange, then explode") and instantly updates color, opacity, and positions of 3D Gaussians in real time. This design avoids overheads such as mesh extraction, manual or physics-based simulations and allows both novice and expert users to animate volumetric scenes with minimal effort on a consumer device even in a web browser. Experimental results show that simple textual instructions suffice to generate compelling time-varying VFX, reducing the manual effort typically required for rigging or advanced modeling. We thus present a fast and accessible pathway to language-driven 3D content creation that can pave the way to democratize VFX further.

[Arxiv](https://arxiv.org/abs/2506.01091)
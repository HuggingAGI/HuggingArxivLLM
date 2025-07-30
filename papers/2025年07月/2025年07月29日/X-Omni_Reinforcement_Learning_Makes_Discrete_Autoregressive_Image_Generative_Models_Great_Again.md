# X-Omni：强化学习让离散自回归图像生成模型焕发新生机

发布时间：2025年07月29日

`LLM应用

摘要中提到的研究将“下一个词预测”范式扩展到视觉内容，结合了强化学习和扩散模型来提升图像生成质量，并提出了一个统一的框架X-Omni，展示了语言模型在图像生成中的应用，属于LLM的实际应用。` `图像生成` `视觉内容处理`

> X-Omni: Reinforcement Learning Makes Discrete Autoregressive Image Generative Models Great Again

# 摘要

> 研究者们尝试将“下一个词预测”范式扩展到视觉内容，以实现图像生成与理解的统一。然而，基于离散标记的自回归建模在图像生成中面临视觉保真度低、输出失真以及难以处理复杂细节的挑战，这些问题可能源于自回归推理中的累积误差或离散化导致的信息丢失。为此，近期研究逐渐转向结合扩散目标的图像生成与自回归目标的语言生成，而非单一建模方法。本研究提出，强化学习可有效减少伪影并显著提升离散自回归建模的生成质量，从而实现图像与语言生成的无缝融合。我们的框架X-Omni包含语义图像标记器、统一的语言与图像自回归模型，以及离线扩散解码器。X-Omni采用7B语言模型，在图像生成任务中达到顶尖水平，生成高美学质量的图像，同时具备强大的指令遵循与长文本呈现能力。

> Numerous efforts have been made to extend the ``next token prediction'' paradigm to visual contents, aiming to create a unified approach for both image generation and understanding. Nevertheless, attempts to generate images through autoregressive modeling with discrete tokens have been plagued by issues such as low visual fidelity, distorted outputs, and failure to adhere to complex instructions when rendering intricate details. These shortcomings are likely attributed to cumulative errors during autoregressive inference or information loss incurred during the discretization process. Probably due to this challenge, recent research has increasingly shifted toward jointly training image generation with diffusion objectives and language generation with autoregressive objectives, moving away from unified modeling approaches. In this work, we demonstrate that reinforcement learning can effectively mitigate artifacts and largely enhance the generation quality of a discrete autoregressive modeling method, thereby enabling seamless integration of image and language generation. Our framework comprises a semantic image tokenizer, a unified autoregressive model for both language and images, and an offline diffusion decoder for image generation, termed X-Omni. X-Omni achieves state-of-the-art performance in image generation tasks using a 7B language model, producing images with high aesthetic quality while exhibiting strong capabilities in following instructions and rendering long texts.

[Arxiv](https://arxiv.org/abs/2507.22058)
# Text2Relight：借助文本引导实现创意人像重新打光

发布时间：2024年12月18日

`LLM应用` `图像编辑` `光照感知`

> Text2Relight: Creative Portrait Relighting with Text Guidance

# 摘要

> 我们呈现了一个具备光照感知能力的图像编辑流程，只要给定一张肖像图和一段文本提示，就能实现单幅图像的重新照明。我们的模型会调整前景和背景的光照与色彩，使其与所提供的文本描述相符。文本在创意上的无边界特性，让我们能够用包括温度、情感、气味、时间等在内的任何感官特征来描绘场景的光照。然而，由于缺乏数据集，其中没有能提供大量文本与重新照明配对的可扩展数据，所以对无边界文本与光照之间的这种映射进行建模极具挑战，当前由文本驱动的图像编辑模型无法推广应用到特定的照明场景中。我们通过引入一种新颖的数据合成流程来解决这个问题：首先，利用大型语言模型（比如 ChatGPT）在精心构建的层级结构下自动生成描述各种光照场景的丰富且有创意的文本提示。一个由文本引导的图像生成模型会创建与文本最匹配的光照图像。作为光照图像的条件，我们使用单张肖像图或者从光舞台系统采集的一组 OLAT（一次一光）图像，对前景和背景进行基于图像的重新照明。特别是对于背景重新照明，我们将光照图像表示为一组点光源，并将其转移到其他背景图像上。一个生成扩散模型通过辅助任务增强（比如肖像照明和光定位）来学习合成的大规模数据，以关联潜在的文本和光照分布，从而实现文本引导的肖像重新照明。

> We present a lighting-aware image editing pipeline that, given a portrait image and a text prompt, performs single image relighting. Our model modifies the lighting and color of both the foreground and background to align with the provided text description. The unbounded nature in creativeness of a text allows us to describe the lighting of a scene with any sensory features including temperature, emotion, smell, time, and so on. However, the modeling of such mapping between the unbounded text and lighting is extremely challenging due to the lack of dataset where there exists no scalable data that provides large pairs of text and relighting, and therefore, current text-driven image editing models does not generalize to lighting-specific use cases. We overcome this problem by introducing a novel data synthesis pipeline: First, diverse and creative text prompts that describe the scenes with various lighting are automatically generated under a crafted hierarchy using a large language model (*e.g.,* ChatGPT). A text-guided image generation model creates a lighting image that best matches the text. As a condition of the lighting images, we perform image-based relighting for both foreground and background using a single portrait image or a set of OLAT (One-Light-at-A-Time) images captured from lightstage system. Particularly for the background relighting, we represent the lighting image as a set of point lights and transfer them to other background images. A generative diffusion model learns the synthesized large-scale data with auxiliary task augmentation (*e.g.,* portrait delighting and light positioning) to correlate the latent text and lighting distribution for text-guided portrait relighting.

[Arxiv](https://arxiv.org/abs/2412.13734)
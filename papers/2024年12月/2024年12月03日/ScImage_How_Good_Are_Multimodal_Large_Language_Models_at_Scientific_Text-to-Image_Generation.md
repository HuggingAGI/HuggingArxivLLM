# ScImage：多模态大型语言模型在科学文本转图像生成方面的表现究竟怎样？

发布时间：2024年12月03日

`LLM应用` `图像生成`

> ScImage: How Good Are Multimodal Large Language Models at Scientific Text-to-Image Generation?

# 摘要

> 多模态大型语言模型（LLMs）在依据文本指令生成高质量图像方面展现出了非凡的能力。然而，它们在生成科学图像这一加速科学进步的关键应用上的表现，尚未得到充分探究。在本研究中，我们引入了 ScImage 来弥补这一空缺，它是用于评估 LLMs 从文本描述生成科学图像的多模态能力的基准。ScImage 评估了三个关键的理解维度：空间、数字和属性理解，以及它们的组合，重点关注科学对象（如正方形、圆形）之间的关系。我们采用两种输出生成模式对五个模型（GPT-4o、Llama、AutomaTikZ、Dall-E 和 StableDiffusion）进行了评估：基于代码的输出（Python、TikZ）和直接生成光栅图像。此外，我们还研究了四种不同的输入语言：英语、德语、波斯语和中文。我们与 11 位科学家依据三个标准（正确性、相关性和科学准确性）进行的评估显示，虽然 GPT-4o 对于涉及单个维度（如空间、数字或属性理解）的简单提示能够生成质量尚可的输出，但所有模型在这项任务中都面临挑战，尤其是面对更复杂的提示时。

> Multimodal large language models (LLMs) have demonstrated impressive capabilities in generating high-quality images from textual instructions. However, their performance in generating scientific images--a critical application for accelerating scientific progress--remains underexplored. In this work, we address this gap by introducing ScImage, a benchmark designed to evaluate the multimodal capabilities of LLMs in generating scientific images from textual descriptions. ScImage assesses three key dimensions of understanding: spatial, numeric, and attribute comprehension, as well as their combinations, focusing on the relationships between scientific objects (e.g., squares, circles). We evaluate five models, GPT-4o, Llama, AutomaTikZ, Dall-E, and StableDiffusion, using two modes of output generation: code-based outputs (Python, TikZ) and direct raster image generation. Additionally, we examine four different input languages: English, German, Farsi, and Chinese. Our evaluation, conducted with 11 scientists across three criteria (correctness, relevance, and scientific accuracy), reveals that while GPT-4o produces outputs of decent quality for simpler prompts involving individual dimensions such as spatial, numeric, or attribute understanding in isolation, all models face challenges in this task, especially for more complex prompts.

[Arxiv](https://arxiv.org/abs/2412.02368)
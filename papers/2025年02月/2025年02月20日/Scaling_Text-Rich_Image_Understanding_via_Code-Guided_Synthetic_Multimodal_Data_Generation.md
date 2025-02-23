# 通过代码引导的合成多模态数据生成扩展文本丰富图像理解

发布时间：2025年02月20日

`LLM应用` `多模态`

> Scaling Text-Rich Image Understanding via Code-Guided Synthetic Multimodal Data Generation

# 摘要

> 处理包含丰富文本（如图表和文档）的图像推理任务是视觉语言模型（VLMs）的重要应用，但这些模型在这些领域常常表现不佳，主要由于缺乏多样化的文本丰富视觉语言数据。为了解决这一问题，我们提出了CoSyn框架，该框架通过仅基于文本的大语言模型（LLMs）的编码能力，自动创建合成的文本丰富多模态数据。当输入描述目标领域的文本（例如，“营养成分标签”）时，CoSyn会提示一个文本大模型生成用于渲染合成图像的代码（如Python、HTML、LaTeX等）。基于这些底层代码作为合成图像的文本表示，CoSyn可以借助仅基于文本的LLM生成高质量的指令微调数据。借助CoSyn，我们构建了一个包含40万张图像和270万行视觉语言指令微调数据的大型数据集。在七个基准测试上的全面实验表明，使用我们的合成数据训练的模型在开源竞争模型中达到了当前最优性能，包括Llama 3.2，并且超越了专有模型如GPT-4V和Gemini 1.5 Flash。此外，CoSyn还可以生成合成指针数据，使VLMs能够将信息定位在输入图像中，展示了其在开发能够在现实环境中行动的多模态智能体方面的潜力。


> Reasoning about images with rich text, such as charts and documents, is a critical application of vision-language models (VLMs). However, VLMs often struggle in these domains due to the scarcity of diverse text-rich vision-language data. To address this challenge, we present CoSyn, a framework that leverages the coding capabilities of text-only large language models (LLMs) to automatically create synthetic text-rich multimodal data. Given input text describing a target domain (e.g., "nutrition fact labels"), CoSyn prompts an LLM to generate code (Python, HTML, LaTeX, etc.) for rendering synthetic images. With the underlying code as textual representations of the synthetic images, CoSyn can generate high-quality instruction-tuning data, again relying on a text-only LLM. Using CoSyn, we constructed a dataset comprising 400K images and 2.7M rows of vision-language instruction-tuning data. Comprehensive experiments on seven benchmarks demonstrate that models trained on our synthetic data achieve state-of-the-art performance among competitive open-source models, including Llama 3.2, and surpass proprietary models such as GPT-4V and Gemini 1.5 Flash. Furthermore, CoSyn can produce synthetic pointing data, enabling VLMs to ground information within input images, showcasing its potential for developing multimodal agents capable of acting in real-world environments.

[Arxiv](https://arxiv.org/abs/2502.14846)
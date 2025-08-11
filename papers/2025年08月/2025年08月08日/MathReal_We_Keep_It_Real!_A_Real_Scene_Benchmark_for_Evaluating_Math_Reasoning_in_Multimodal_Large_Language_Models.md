# # MathReal：真实到底！评估多模态大语言模型数学推理能力的真实场景基准

发布时间：2025年08月08日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型在视觉数学推理方面的应用，特别是在真实场景中的表现。他们开发了一个新的数据集，用于评估这些模型在处理实际教育场景中的能力，并分析了模型的性能和错误模式。这属于LLM的应用和评估，因此归类为LLM应用。` `教育技术`

> MathReal: We Keep It Real! A Real Scene Benchmark for Evaluating Math Reasoning in Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在视觉数学推理方面表现突出，但在现有基准测试中，这些模型主要处理干净或经过处理的多模态输入，缺乏对真实场景中K-12教育用户图像的考量。为解决这一问题，我们推出了MathReal，一个包含2000道数学问题的数据集，这些问题的图像均由手持设备在真实场景中拍摄。每个问题图像均包含问题文本和相关视觉元素。我们系统性地将这些真实图像分为三大类：图像质量退化、视角变化和无关内容干扰，并进一步细分为14个子类别。此外，MathReal覆盖了五个核心知识和能力类别，包含三种问题类型，并根据难度分为三个级别。为全面评估MLLMs在现实场景中的多模态数学推理能力，我们设计了六个实验设置，以系统性分析模型表现。实验结果显示，现有MLLMs在真实教育场景中的问题解决能力面临严峻挑战。我们对其性能和错误模式进行了深入分析，揭示了模型在识别、理解和推理方面的优势与不足，并为未来研究指明了方向。数据和代码已开源：https://github.com/junfeng0288/MathReal。

> Multimodal Large Language Models (MLLMs) have demonstrated remarkable capabilities in visual mathematical reasoning across various existing benchmarks. However, these benchmarks are predominantly based on clean or processed multimodal inputs, without incorporating the images provided by real-world Kindergarten through 12th grade (K-12) educational users. To address this gap, we introduce MathReal, a meticulously curated dataset comprising 2,000 mathematical questions with images captured by handheld mobile devices in authentic scenarios. Each question is an image, containing the question text and visual element. We systematically classify the real images into three primary categories: image quality degradation, perspective variation, and irrelevant content interference, which are further delineated into 14 subcategories. Additionally, MathReal spans five core knowledge and ability categories, which encompass three question types and are divided into three difficulty levels. To comprehensively evaluate the multimodal mathematical reasoning abilities of state-of-the-art MLLMs in real-world scenarios, we design six experimental settings that enable a systematic analysis of their performance. Through extensive experimentation, we find that the problem-solving abilities of existing MLLMs are significantly challenged in realistic educational contexts. Based on this, we conduct a thorough analysis of their performance and error patterns, providing insights into their recognition, comprehension, and reasoning capabilities, and outlining directions for future improvements. Data and code: https://github.com/junfeng0288/MathReal.

[Arxiv](https://arxiv.org/abs/2508.06009)
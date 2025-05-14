# 视觉引导解码：基于语言模型的无梯度硬提示反转方法

发布时间：2025年05月13日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLMs）生成更有效和连贯的文本提示，以改进文本到图像生成模型的效果。它展示了LLMs在实际应用中的具体用途，属于LLM应用类别。` `创意设计`

> Visually Guided Decoding: Gradient-Free Hard Prompt Inversion with Language Models

# 摘要

> 文本到图像生成模型（如 DALL-E 和 Stable Diffusion）彻底改变了广告、个性化媒体和设计原型等领域的视觉内容创作。然而，要为这些模型创建有效的文本提示仍然充满挑战，通常需要反复尝试。现有的提示反转方法（如软提示和硬提示技术）由于提示的可解释性有限和生成的提示缺乏连贯性，效果并不理想。为了解决这些问题，我们提出了视觉引导解码（VGD），这是一种无梯度的方法，通过结合大型语言模型（LLMs）和基于 CLIP 的指导，生成连贯且语义对齐的提示。VGD 利用 LLMs 的强大文本生成能力，生成可读的提示。此外，通过 CLIP 评分确保与用户指定的视觉概念一致，VGD 增强了提示生成的可解释性、通用性和灵活性，无需额外训练。实验结果表明，VGD 在生成可理解且上下文相关的提示方面优于现有方法，使用户能够更直观、更可控地与文本到图像模型进行交互。

> Text-to-image generative models like DALL-E and Stable Diffusion have revolutionized visual content creation across various applications, including advertising, personalized media, and design prototyping. However, crafting effective textual prompts to guide these models remains challenging, often requiring extensive trial and error. Existing prompt inversion approaches, such as soft and hard prompt techniques, are not so effective due to the limited interpretability and incoherent prompt generation. To address these issues, we propose Visually Guided Decoding (VGD), a gradient-free approach that leverages large language models (LLMs) and CLIP-based guidance to generate coherent and semantically aligned prompts. In essence, VGD utilizes the robust text generation capabilities of LLMs to produce human-readable prompts. Further, by employing CLIP scores to ensure alignment with user-specified visual concepts, VGD enhances the interpretability, generalization, and flexibility of prompt generation without the need for additional training. Our experiments demonstrate that VGD outperforms existing prompt inversion techniques in generating understandable and contextually relevant prompts, facilitating more intuitive and controllable interactions with text-to-image models.

[Arxiv](https://arxiv.org/abs/2505.08622)
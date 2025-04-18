# # Early Accessibility: Automating Alt-Text Generation for UI Icons During App Development
早期可访问性：在应用开发过程中自动化生成 UI 图标替代文本

发布时间：2025年04月17日

`LLM应用` `移动应用` `人工智能`

> Early Accessibility: Automating Alt-Text Generation for UI Icons During App Development

# 摘要

> 替代文本对移动应用的可访问性至关重要，但UI图标常缺乏有意义的描述，这限制了屏幕阅读器用户的使用体验。现有的解决方案要么依赖大量标注数据，要么难以处理不完整的UI上下文，或只能在开发完成后使用，从而增加技术债务。我们首先开展了一项形成性研究，旨在了解开发人员在何时及如何偏好生成图标替代文本。随后，我们提出了ALTICON方法，该方法在开发过程中利用两个微调模型为UI图标生成替代文本：一个处理提取UI元数据的纯文本大型语言模型，以及一个结合分析图标图像和文本上下文的多模态模型。为提升准确性，该方法从DOM树中提取相关UI信息，通过OCR技术提取图标内文字，并采用结构化提示生成替代文本。与最相关的深度学习和视觉-语言模型的实证评估显示，ALTICON生成的替代文本质量更优，且无需全屏输入。

> Alt-text is essential for mobile app accessibility, yet UI icons often lack meaningful descriptions, limiting accessibility for screen reader users. Existing approaches either require extensive labeled datasets, struggle with partial UI contexts, or operate post-development, increasing technical debt. We first conduct a formative study to determine when and how developers prefer to generate icon alt-text. We then explore the ALTICON approach for generating alt-text for UI icons during development using two fine-tuned models: a text-only large language model that processes extracted UI metadata and a multi-modal model that jointly analyzes icon images and textual context. To improve accuracy, the method extracts relevant UI information from the DOM tree, retrieves in-icon text via OCR, and applies structured prompts for alt-text generation. Our empirical evaluation with the most closely related deep-learning and vision-language models shows that ALTICON generates alt-text that is of higher quality while not requiring a full-screen input.

[Arxiv](https://arxiv.org/abs/2504.13069)
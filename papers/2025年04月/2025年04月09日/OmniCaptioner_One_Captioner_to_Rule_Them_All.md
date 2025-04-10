# OmniCaptioner：一网打尽，通配所有图像描述工具

发布时间：2025年04月09日

`LLM应用

这篇论文主要探讨了如何利用LLM（特别是DeepSeek-R1系列）在多模态场景下的推理能力和生成任务中的应用。OmniCaptioner通过生成详细的视觉描述，增强了LLM在视觉与文本之间的桥梁作用，属于LLM的应用领域。` `视觉处理` `文本生成`

> OmniCaptioner: One Captioner to Rule Them All

# 摘要

> 我们提出了一种灵活多样的视觉描述框架OmniCaptioner，能够为广泛视觉领域生成细致入微的文本描述。与传统方法局限于特定图像类型不同，OmniCaptioner统一支持自然图像、视觉文本（如海报、UI、教科书）和结构化视觉（如文档、表格、图表）的描述生成。通过将低级像素信息转化为语义丰富的文本表示，OmniCaptioner在视觉与文本模态之间架起了一座桥梁。

我们的框架具有三大优势：首先，通过长上下文视觉描述，显著增强了LLMs（特别是DeepSeek-R1系列）在多模态场景下的推理能力；其次，详细精准的描述大幅提升了文本到图像生成和图像变换等任务的效果；最后，实现了高效的监督微调（SFT），在更少数据下实现更快收敛。OmniCaptioner的灵活性和适应性为弥合语言与视觉模态的鸿沟提供了全新视角。

> We propose OmniCaptioner, a versatile visual captioning framework for generating fine-grained textual descriptions across a wide variety of visual domains. Unlike prior methods limited to specific image types (e.g., natural images or geometric visuals), our framework provides a unified solution for captioning natural images, visual text (e.g., posters, UIs, textbooks), and structured visuals (e.g., documents, tables, charts). By converting low-level pixel information into semantically rich textual representations, our framework bridges the gap between visual and textual modalities. Our results highlight three key advantages: (i) Enhanced Visual Reasoning with LLMs, where long-context captions of visual modalities empower LLMs, particularly the DeepSeek-R1 series, to reason effectively in multimodal scenarios; (ii) Improved Image Generation, where detailed captions improve tasks like text-to-image generation and image transformation; and (iii) Efficient Supervised Fine-Tuning (SFT), which enables faster convergence with less data. We believe the versatility and adaptability of OmniCaptioner can offer a new perspective for bridging the gap between language and visual modalities.

[Arxiv](https://arxiv.org/abs/2504.07089)
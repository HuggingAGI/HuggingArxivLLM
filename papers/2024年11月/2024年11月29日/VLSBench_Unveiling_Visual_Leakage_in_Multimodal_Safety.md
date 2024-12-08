# VLSBench：揭开多模态安全中的视觉泄漏之谜

发布时间：2024年11月29日

`LLM应用` `多模态`

> VLSBench: Unveiling Visual Leakage in Multimodal Safety

# 摘要

> 多模态大型语言模型（MLLMs）的安全问题在各类应用中已逐步成为重要问题。令人惊讶的是，以往研究显示出一种反直觉的现象，即运用文本遗忘来调整 MLLMs 能取得与用图像-文本对训练的 MLLMs 相近的安全性能。为阐释这一反直觉现象，我们在现有的多模态安全基准中发现了视觉安全信息泄漏（VSIL）问题，也就是说，图像中潜在的危险和敏感内容在文本查询中已被暴露。如此一来，MLLMs 能够依据文本查询轻易拒绝这些敏感的文本-图像查询。然而，无 VSIL 的图像-文本对在现实场景中颇为常见，却被现有的多模态安全基准所忽略。为此，我们构建了包含 2.4k 图像-文本对的多模态视觉无泄漏安全基准（VLSBench），以阻止图像到文本查询的视觉安全泄漏。实验结果表明，VLSBench 对包括 LLaVA、Qwen2-VL、Llama3.2-Vision 和 GPT-4o 在内的开源和闭源 MLLMs 均构成重大挑战。本研究表明，对于有 VSIL 的多模态安全场景，文本对齐已足够，而对于无 VSIL 的多模态安全场景，多模态对齐是更具前景的解决方案。请访问以下网址查看我们的代码和数据：http://hxhcreate.github.io/VLSBench

> Safety concerns of Multimodal large language models (MLLMs) have gradually become an important problem in various applications. Surprisingly, previous works indicate a counter-intuitive phenomenon that using textual unlearning to align MLLMs achieves comparable safety performances with MLLMs trained with image-text pairs. To explain such a counter-intuitive phenomenon, we discover a visual safety information leakage (VSIL) problem in existing multimodal safety benchmarks, i.e., the potentially risky and sensitive content in the image has been revealed in the textual query. In this way, MLLMs can easily refuse these sensitive text-image queries according to textual queries. However, image-text pairs without VSIL are common in real-world scenarios and are overlooked by existing multimodal safety benchmarks. To this end, we construct multimodal visual leakless safety benchmark (VLSBench) preventing visual safety leakage from image to textual query with 2.4k image-text pairs. Experimental results indicate that VLSBench poses a significant challenge to both open-source and close-source MLLMs, including LLaVA, Qwen2-VL, Llama3.2-Vision, and GPT-4o. This study demonstrates that textual alignment is enough for multimodal safety scenarios with VSIL, while multimodal alignment is a more promising solution for multimodal safety scenarios without VSIL. Please see our code and data at: http://hxhcreate.github.io/VLSBench

[Arxiv](https://arxiv.org/abs/2411.19939)
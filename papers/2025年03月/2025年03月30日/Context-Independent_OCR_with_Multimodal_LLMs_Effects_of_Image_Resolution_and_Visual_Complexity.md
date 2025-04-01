# 上下文无关 OCR 与多模态大语言模型：图像分辨率与视觉复杂度的影响

发布时间：2025年03月30日

`LLM应用

这篇论文探讨了多模态大型语言模型在OCR任务中的应用，具体研究了这些模型在不同图像条件下的性能，属于应用层面的研究。` `文档处理` `OCR`

> Context-Independent OCR with Multimodal LLMs: Effects of Image Resolution and Visual Complexity

# 摘要

> 多模态大型语言模型（LLMs）在图像描述、文档分析和自动化内容生成等任务中表现出色，因此在多个工业领域备受关注。尤其是在光学字符识别（OCR）方面，它们已超越了专门的模型。然而，它们在不同图像条件下的性能仍有待深入研究，且由于依赖上下文线索，单个字符识别的可靠性尚未得到保证。本研究通过使用具有不同视觉复杂度的单字符图像，探索了一个上下文无关的 OCR 任务，以确定准确识别的条件。我们的研究发现，在约 300 ppi 时，多模态 LLMs 可与传统 OCR 方法相媲美，但低于 150 ppi 时性能显著下降。此外，我们观察到视觉复杂度与误识别之间存在非常弱的相关性，而传统 OCR 专用模型则无此相关性。这些结果表明，图像分辨率和视觉复杂度可能在多模态 LLMs 可靠应用于需要精确字符级准确性的 OCR 任务中发挥重要作用。

> Due to their high versatility in tasks such as image captioning, document analysis, and automated content generation, multimodal Large Language Models (LLMs) have attracted significant attention across various industrial fields. In particular, they have been shown to surpass specialized models in Optical Character Recognition (OCR). Nevertheless, their performance under different image conditions remains insufficiently investigated, and individual character recognition is not guaranteed due to their reliance on contextual cues. In this work, we examine a context-independent OCR task using single-character images with diverse visual complexities to determine the conditions for accurate recognition. Our findings reveal that multimodal LLMs can match conventional OCR methods at about 300 ppi, yet their performance deteriorates significantly below 150 ppi. Additionally, we observe a very weak correlation between visual complexity and misrecognitions, whereas a conventional OCR-specific model exhibits no correlation. These results suggest that image resolution and visual complexity may play an important role in the reliable application of multimodal LLMs to OCR tasks that require precise character-level accuracy.

[Arxiv](https://arxiv.org/abs/2503.23667)
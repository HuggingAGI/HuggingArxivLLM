# PsOCR: 评估大型多模态模型在资源匮乏的普什图语光学字符识别中的表现

发布时间：2025年05月15日

`LLM应用` `光学字符识别`

> PsOCR: Benchmarking Large Multimodal Models for Optical Character Recognition in Low-resource Pashto Language

# 摘要

> 本文评估了大型多模态模型（LMMs）在低资源普什图语光学字符识别（OCR）上的性能。普什图语的自然语言处理面临诸多挑战，主要是由于其文字的手写体特性以及结构化数据集的匮乏。为解决这一问题，我们开发了一个合成普什图OCR数据集PsOCR，包含一百万张图像，这些图像在单词、行和文档级别标注了边界框，适用于基于不同架构（包括卷积神经网络（CNNs）和Transformer）的模型训练和评估。PsOCR涵盖了1,000种独特的字体家族、颜色、图像尺寸和布局的变化。我们从中精选了10,000张图像作为基准测试集，用于评估多个LMMs的性能，其中包括七种开源模型：深度求索的Janus模型、InternVL、MiniCPM、Florence以及Qwen（3B和7B版本），以及四种闭源模型：GPT-4o、Gemini、Claude和Grok。实验结果表明，Gemini在所有模型中表现最佳，而在开源模型中，Qwen-7B脱颖而出。这项研究为当前LMMs在普什图语OCR任务中的能力和局限性提供了深刻的评估，同时也为后续研究奠定了基础，不仅限于普什图OCR，还包括其他类似的文字系统，如阿拉伯语、波斯语和乌尔都语。PsOCR数据集可在https://github.com/zirak-ai/PashtoOCR获取。

> This paper evaluates the performance of Large Multimodal Models (LMMs) on Optical Character Recognition (OCR) in the low-resource Pashto language. Natural Language Processing (NLP) in Pashto faces several challenges due to the cursive nature of its script and a scarcity of structured datasets. To address this, we developed a synthetic Pashto OCR dataset, PsOCR, consisting of one million images annotated with bounding boxes at word, line, and document levels, suitable for training and evaluating models based on different architectures, including Convolutional Neural Networks (CNNs) and Transformers. PsOCR covers variations across 1,000 unique font families, colors, image sizes, and layouts. A benchmark subset of 10K images was selected to evaluate the performance of several LMMs, including seven open-source models: DeepSeek's Janus, InternVL, MiniCPM, Florence, and Qwen (3B and 7B), and four closed-source models: GPT-4o, Gemini, Claude, and Grok. Experimental results demonstrate that Gemini achieves the best performance among all models, whereas among open-source models, Qwen-7B stands out. This work provides an insightful assessment of the capabilities and limitations of current LMMs for OCR tasks in Pashto and establishes a foundation for further research not only in Pashto OCR but also for other similar scripts such as Arabic, Persian, and Urdu. PsOCR is available at https://github.com/zirak-ai/PashtoOCR.

[Arxiv](https://arxiv.org/abs/2505.10055)
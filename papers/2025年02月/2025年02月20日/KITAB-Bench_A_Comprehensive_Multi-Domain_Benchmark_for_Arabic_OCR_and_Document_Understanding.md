# KITAB-Bench：面向阿拉伯语OCR与文档理解的多领域综合性基准测试

发布时间：2025年02月20日

`RAG` `文档分析` `OCR`

> KITAB-Bench: A Comprehensive Multi-Domain Benchmark for Arabic OCR and Document Understanding

# 摘要

> 随着检索增强生成（RAG）在文档处理中的广泛应用，强大的文本识别能力对于知识提取变得越来越重要。尽管英语及其他语言的OCR（光学字符识别）得益于大规模数据集和成熟的基准测试，但阿拉伯语OCR因连写文字、右左书写方向以及复杂排版和书法特征而面临独特挑战。我们推出KITAB-Bench，一个全面的阿拉伯语OCR基准测试，填补现有评估体系的空白。我们的基准测试包含来自9个主要领域和36个子领域的8,809个样本，涵盖手写文本、结构化表格，以及针对商业智能的21种图表类型。研究结果显示，现代视觉语言模型（如GPT-4、Gemini和Qwen）在字符错误率（CER）上平均比传统OCR方法（如EasyOCR、PaddleOCR和Surya）高出60%。此外，我们发现当前阿拉伯语OCR模型在PDF转Markdown转换方面存在重大局限性，表现最佳的模型Gemini-2.0-Flash仅能达到65%的准确率。这凸显了准确识别阿拉伯语文本的挑战，包括复杂字体、数字识别错误、单词拉伸以及表格结构检测等问题。这项工作建立了一个严格的评估框架，旨在推动阿拉伯语文档分析方法的改进，并缩小与英语OCR技术的性能差距。

> With the growing adoption of Retrieval-Augmented Generation (RAG) in document processing, robust text recognition has become increasingly critical for knowledge extraction. While OCR (Optical Character Recognition) for English and other languages benefits from large datasets and well-established benchmarks, Arabic OCR faces unique challenges due to its cursive script, right-to-left text flow, and complex typographic and calligraphic features. We present KITAB-Bench, a comprehensive Arabic OCR benchmark that fills the gaps in current evaluation systems. Our benchmark comprises 8,809 samples across 9 major domains and 36 sub-domains, encompassing diverse document types including handwritten text, structured tables, and specialized coverage of 21 chart types for business intelligence. Our findings show that modern vision-language models (such as GPT-4, Gemini, and Qwen) outperform traditional OCR approaches (like EasyOCR, PaddleOCR, and Surya) by an average of 60% in Character Error Rate (CER). Furthermore, we highlight significant limitations of current Arabic OCR models, particularly in PDF-to-Markdown conversion, where the best model Gemini-2.0-Flash achieves only 65% accuracy. This underscores the challenges in accurately recognizing Arabic text, including issues with complex fonts, numeral recognition errors, word elongation, and table structure detection. This work establishes a rigorous evaluation framework that can drive improvements in Arabic document analysis methods and bridge the performance gap with English OCR technologies.

[Arxiv](https://arxiv.org/abs/2502.14949)
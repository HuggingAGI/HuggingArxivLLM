# OCR翻译中的迷失？基于视觉的健壮文档检索方法

发布时间：2025年05月08日

`RAG` `文档处理` `问答系统`

> Lost in OCR Translation? Vision-Based Approaches to Robust Document Retrieval

# 摘要

> 检索增强生成（RAG）成为提升大型语言模型（LLMs）可靠性和实用性的热门技术，通过将响应扎根于外部文档。传统的RAG系统依赖光学字符识别（OCR）将扫描文档转换为文本。然而，即使是先进的OCR也可能在降级或复杂文档中出错。最近的视觉语言方法如ColPali提出直接对文档进行视觉嵌入，无需OCR。本研究利用Llama 3.2（90B）和Nougat OCR，系统比较了基于视觉的RAG系统（ColPali）与传统OCR管道在不同文档质量下的表现。除了传统检索准确性指标，我们引入语义答案评估基准来衡量端到端问答性能。研究发现，基于视觉的RAG在其微调文档上表现优异，但基于OCR的RAG更擅长泛化到不同质量的未见文档。我们揭示了计算效率与语义准确性之间的关键权衡，为RAG从业者在生产环境中选择依赖OCR还是基于视觉的文档检索系统提供了实用建议。


> Retrieval-Augmented Generation (RAG) has become a popular technique for enhancing the reliability and utility of Large Language Models (LLMs) by grounding responses in external documents. Traditional RAG systems rely on Optical Character Recognition (OCR) to first process scanned documents into text. However, even state-of-the-art OCRs can introduce errors, especially in degraded or complex documents. Recent vision-language approaches, such as ColPali, propose direct visual embedding of documents, eliminating the need for OCR. This study presents a systematic comparison between a vision-based RAG system (ColPali) and more traditional OCR-based pipelines utilizing Llama 3.2 (90B) and Nougat OCR across varying document qualities. Beyond conventional retrieval accuracy metrics, we introduce a semantic answer evaluation benchmark to assess end-to-end question-answering performance. Our findings indicate that while vision-based RAG performs well on documents it has been fine-tuned on, OCR-based RAG is better able to generalize to unseen documents of varying quality. We highlight the key trade-offs between computational efficiency and semantic accuracy, offering practical guidance for RAG practitioners in selecting between OCR-dependent and vision-based document retrieval systems in production environments.

[Arxiv](https://arxiv.org/abs/2505.05666)
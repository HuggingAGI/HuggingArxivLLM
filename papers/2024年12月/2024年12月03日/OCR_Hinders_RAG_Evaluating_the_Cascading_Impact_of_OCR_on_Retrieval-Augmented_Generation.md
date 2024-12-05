# OCR 对 RAG 造成阻碍：评估 OCR 对检索增强生成的连锁影响

发布时间：2024年12月03日

`RAG` `文档处理` `语言模型`

> OCR Hinders RAG: Evaluating the Cascading Impact of OCR on Retrieval-Augmented Generation

# 摘要

> 检索增强生成（RAG）整合外部知识来强化大型语言模型（LLMs），能减少幻觉并融入最新信息，无需重新训练。作为 RAG 的关键部分，外部知识库一般通过用光学字符识别（OCR）从非结构化 PDF 文档中提取结构化数据来构建。但由于 OCR 预测不完美以及结构化数据本身的非均匀表示，知识库难免存在各种 OCR 噪声。在本文中，我们推出了 OHRBench，这是首个用于理解 OCR 对 RAG 系统级联影响的基准。OHRBench 涵盖了从六个真实 RAG 应用领域精心筛选的 350 个非结构化 PDF 文档，还有源自文档多模态元素的问答，对用于 RAG 的现有 OCR 解决方案构成挑战。为更好地理解 OCR 对 RAG 系统的影响，我们明确了两种主要的 OCR 噪声类型：语义噪声和格式噪声，并通过扰动生成一组具有不同程度每种噪声的结构化数据。借助 OHRBench，我们先是对当前的 OCR 解决方案进行了全面评估，发现没有一个能为 RAG 系统构建高质量的知识库。接着，我们系统评估了这两种噪声类型的影响，展现了 RAG 系统的脆弱性。此外，我们探讨了在 RAG 系统中使用无 OCR 的视觉语言模型（VLMs）的可能性。代码：https://github.com/opendatalab/OHR-Bench

> Retrieval-augmented Generation (RAG) enhances Large Language Models (LLMs) by integrating external knowledge to reduce hallucinations and incorporate up-to-date information without retraining. As an essential part of RAG, external knowledge bases are commonly built by extracting structured data from unstructured PDF documents using Optical Character Recognition (OCR). However, given the imperfect prediction of OCR and the inherent non-uniform representation of structured data, knowledge bases inevitably contain various OCR noises. In this paper, we introduce OHRBench, the first benchmark for understanding the cascading impact of OCR on RAG systems. OHRBench includes 350 carefully selected unstructured PDF documents from six real-world RAG application domains, along with Q&As derived from multimodal elements in documents, challenging existing OCR solutions used for RAG To better understand OCR's impact on RAG systems, we identify two primary types of OCR noise: Semantic Noise and Formatting Noise and apply perturbation to generate a set of structured data with varying degrees of each OCR noise. Using OHRBench, we first conduct a comprehensive evaluation of current OCR solutions and reveal that none is competent for constructing high-quality knowledge bases for RAG systems. We then systematically evaluate the impact of these two noise types and demonstrate the vulnerability of RAG systems. Furthermore, we discuss the potential of employing Vision-Language Models (VLMs) without OCR in RAG systems. Code: https://github.com/opendatalab/OHR-Bench

[Arxiv](https://arxiv.org/abs/2412.02592)
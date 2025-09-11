# 多模态文本的向量嵌入：发现工具？

发布时间：2025年09月09日

`LLM应用` `教育科技`

> Vector embedding of multi-modal texts: a tool for discovery?

# 摘要

> 计算机科学文本内容丰富，既包含叙事性内容，也有说明性图表、算法、图像、带注释的示意图等。本研究探讨了在视觉语言模型（VLMs）支持下，基于向量的多模态检索能在多大程度上提升跨多模态（文本与图像）内容的发现效果。研究团队使用了3600多页主要来自计算机科学教科书的数字化课本页面，并结合视觉语言模型（VLM），生成了能够捕捉文本和视觉语义的多向量表示。这些嵌入向量被存储在向量数据库中。我们构建了包含75个自然语言查询的基准测试集，将检索性能与真实结果进行对比，并比较了四种相似度（距离）度量的效果。本研究旨在揭示该方法的优势与不足。结果表明，余弦相似度能最有效地检索出语义和视觉上相关的页面。我们还探讨了将向量数据库与多模态嵌入应用于实际信息检索的可行性。本文旨在为数字图书馆的内容发现系统提供设计思路。
  关键词：向量嵌入，多模态文档检索，向量数据库基准，数字图书馆发现

> Computer science texts are particularly rich in both narrative content and illustrative charts, algorithms, images, annotated diagrams, etc. This study explores the extent to which vector-based multimodal retrieval, powered by vision-language models (VLMs), can improve discovery across multi-modal (text and images) content. Using over 3,600 digitized textbook pages largely from computer science textbooks and a Vision Language Model (VLM), we generate multi-vector representations capturing both textual and visual semantics. These embeddings are stored in a vector database. We issue a benchmark of 75 natural language queries and compare retrieval performance to ground truth and across four similarity (distance) measures. The study is intended to expose both the strengths and weakenesses of such an approach. We find that cosine similarity most effectively retrieves semantically and visually relevant pages. We further discuss the practicality of using a vector database and multi-modal embedding for operational information retrieval. Our paper is intended to offer design insights for discovery over digital libraries.
  Keywords: Vector embedding, multi-modal document retrieval, vector database benchmark, digital library discovery

[Arxiv](https://arxiv.org/abs/2509.08216)
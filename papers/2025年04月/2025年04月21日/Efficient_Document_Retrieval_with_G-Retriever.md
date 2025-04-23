# # 高效文档检索：G-Retriever的解决方案

发布时间：2025年04月21日

`RAG` `问答系统` `文本处理`

> Efficient Document Retrieval with G-Retriever

# 摘要

> 文本数据问答系统因广泛应用而备受关注。我们提出了一种结合检索增强生成（RAG）方法的改进方案，采用基于注意力机制的子图构建技术，替代原有的 Prize-Collecting Steiner Tree（PCST）方法。通过编码节点和边属性，我们生成了更丰富的图表示，并引入优化的投影层和多头注意力池化技术，以更好地适配大型语言模型（LLMs）。实验结果表明，我们的方案在 WebQSP 数据集上表现优异，问答准确性显著提升。


> Textual data question answering has gained significant attention due to its growing applicability. Recently, a novel approach leveraging the Retrieval-Augmented Generation (RAG) method was introduced, utilizing the Prize-Collecting Steiner Tree (PCST) optimization for sub-graph construction. However, this method focused solely on node attributes, leading to incomplete contextual understanding. In this paper, we propose an enhanced approach that replaces the PCST method with an attention-based sub-graph construction technique, enabling more efficient and context-aware retrieval. Additionally, we encode both node and edge attributes, leading to richer graph representations. Our method also incorporates an improved projection layer and multi-head attention pooling for better alignment with Large Language Models (LLMs). Experimental evaluations on the WebQSP dataset demonstrate that our approach is competitive and achieves marginally better results compared to the original method, underscoring its potential for more accurate question answering.

[Arxiv](https://arxiv.org/abs/2504.14955)
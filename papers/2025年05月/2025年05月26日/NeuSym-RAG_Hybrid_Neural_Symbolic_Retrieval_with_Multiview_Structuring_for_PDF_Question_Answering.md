# NeuSym-RAG: 面向PDF问答的混合神经符号检索方法，结合多视图结构化技术

发布时间：2025年05月26日

`RAG` `学术研究` `信息检索`

> NeuSym-RAG: Hybrid Neural Symbolic Retrieval with Multiview Structuring for PDF Question Answering

# 摘要

> 面对日益增长的学术论文数量，研究人员在高效获取关键信息方面正面临严峻挑战。虽然基于大型语言模型（LLM）的检索增强生成（RAG）在自动问答中展现出巨大潜力，但以往研究往往忽视了神经检索与符号检索的互补优势，将二者割裂开来。此外，传统单一视图分块方法忽略了PDF文件中丰富的结构和布局信息，例如章节和表格。为此，我们提出了NeuSym-RAG，一种结合神经和符号检索的混合框架，通过交互式流程将两种范式有机结合。通过多视图分块和基于模式的解析，NeuSym-RAG将半结构化PDF内容高效组织到关系型数据库和向量存储中，使LLM代理能够迭代收集上下文直至生成高质量答案。在三个完整的PDF问答数据集上的实验结果，包括一个自标注的AIRQA-REAL，充分证明了NeuSym-RAG在性能上的显著优势，其不仅超越了传统基于向量的RAG方法，还优于多种结构化基线，充分展现了其统一两种检索方案并充分利用多视图信息的能力。代码和数据已在GitHub公开，访问地址为https://github.com/X-LANCE/NeuSym-RAG。

> The increasing number of academic papers poses significant challenges for researchers to efficiently acquire key details. While retrieval augmented generation (RAG) shows great promise in large language model (LLM) based automated question answering, previous works often isolate neural and symbolic retrieval despite their complementary strengths. Moreover, conventional single-view chunking neglects the rich structure and layout of PDFs, e.g., sections and tables. In this work, we propose NeuSym-RAG, a hybrid neural symbolic retrieval framework which combines both paradigms in an interactive process. By leveraging multi-view chunking and schema-based parsing, NeuSym-RAG organizes semi-structured PDF content into both the relational database and vectorstore, enabling LLM agents to iteratively gather context until sufficient to generate answers. Experiments on three full PDF-based QA datasets, including a self-annotated one AIRQA-REAL, show that NeuSym-RAG stably defeats both the vector-based RAG and various structured baselines, highlighting its capacity to unify both retrieval schemes and utilize multiple views. Code and data are publicly available at https://github.com/X-LANCE/NeuSym-RAG.

[Arxiv](https://arxiv.org/abs/2505.19754)
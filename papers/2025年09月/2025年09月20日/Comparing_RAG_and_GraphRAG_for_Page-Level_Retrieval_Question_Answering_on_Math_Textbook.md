# RAG与GraphRAG在数学教材页面级检索问答中的比较

发布时间：2025年09月20日

`RAG` `教育科技`

> Comparing RAG and GraphRAG for Page-Level Retrieval Question Answering on Math Textbook

# 摘要

> 技术赋能的学习环境通常能帮助学生在自主学习时，针对遇到的问题检索相关学习内容。大型语言模型（LLMs）已成为学习过程中信息检索的新型辅助工具。尽管LLMs在通用问答方面表现出色，但它们通常与特定课程材料（如教材和幻灯片）的领域知识不够契合。我们研究了检索增强生成（RAG）和GraphRAG——一种知识图谱增强的RAG方法，用于本科数学教材的页面级问答。虽然RAG在检索离散的、上下文相关的段落方面效果显著，但GraphRAG在建模互联概念和层级知识结构上可能更具优势。我们构建了包含477个问答对的数据集，每个问答对都与教材中特定的页面相关联。随后，我们对比了基于嵌入的标准RAG方法与GraphRAG，评估了检索准确性（即是否检索到正确页面）和通过F1分数衡量的生成答案质量。研究结果显示，与GraphRAG相比，基于嵌入的RAG检索准确性更高，F1分数更优；而GraphRAG由于其基于实体的结构，往往会检索过多且有时不相关的内容。我们还尝试用LLM对检索到的页面重新排序，结果喜忧参半，包括在处理更大上下文窗口时出现性能下降和幻觉现象。总体而言，本研究揭示了教育场景下页面级检索系统的潜力与挑战，强调需开发更精细的检索方法，以构建能提供参考页码的可靠AI辅导解决方案。

> Technology-enhanced learning environments often help students retrieve relevant learning content for questions arising during self-paced study. Large language models (LLMs) have emerged as novel aids for information retrieval during learning. While LLMs are effective for general-purpose question-answering, they typically lack alignment with the domain knowledge of specific course materials such as textbooks and slides. We investigate Retrieval-Augmented Generation (RAG) and GraphRAG, a knowledge graph-enhanced RAG approach, for page-level question answering in an undergraduate mathematics textbook. While RAG has been effective for retrieving discrete, contextually relevant passages, GraphRAG may excel in modeling interconnected concepts and hierarchical knowledge structures. We curate a dataset of 477 question-answer pairs, each tied to a distinct textbook page. We then compare the standard embedding-based RAG methods to GraphRAG for evaluating both retrieval accuracy-whether the correct page is retrieved-and generated answer quality via F1 scores. Our findings show that embedding-based RAG achieves higher retrieval accuracy and better F1 scores compared to GraphRAG, which tends to retrieve excessive and sometimes irrelevant content due to its entity-based structure. We also explored re-ranking the retrieved pages with LLM and observed mixed results, including performance drop and hallucinations when dealing with larger context windows. Overall, this study highlights both the promises and challenges of page-level retrieval systems in educational contexts, emphasizing the need for more refined retrieval methods to build reliable AI tutoring solutions in providing reference page numbers.

[Arxiv](https://arxiv.org/abs/2509.16780)
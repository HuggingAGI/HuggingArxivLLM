# MRAG：一个用于时间敏感型问答的模块化检索框架

发布时间：2024年12月19日

`RAG` `问答系统` `时间推理`

> MRAG: A Modular Retrieval Framework for Time-Sensitive Question Answering

# 摘要

> 理解时间关系并回答时间敏感问题，对于由大型语言模型（LLMs）驱动的问答系统而言，极为关键但也充满挑战。现有的办法，要么用新事实更新LLMs的参数知识，这既耗费资源又常不现实，要么把LLMs与外部知识检索（即检索增强生成）相融合。然而，现成的检索器常常难以找出需要深度时间推理的相关文档。为了系统探究时间敏感型问答，我们引入了TempRAGEval基准，它通过融入时间扰动和黄金证据标签来重新利用现有数据集。不出所料，所有现有的检索方法在处理这些时间推理密集型问题时都颇为吃力。我们进一步提出了模块化检索（MRAG），这是一个无需训练的框架，涵盖三个模块：（1）问题处理，将问题拆解为主要内容和时间约束；（2）检索与总结，检索证据并依据主要内容利用LLMs进行总结；（3）语义-时间混合排序，基于语义和时间相关性为每个证据总结打分。在TempRAGEval上，MRAG在检索性能方面显著优于基线检索器，进而使最终答案的准确性得到进一步提升。

> Understanding temporal relations and answering time-sensitive questions is crucial yet a challenging task for question-answering systems powered by large language models (LLMs). Existing approaches either update the parametric knowledge of LLMs with new facts, which is resource-intensive and often impractical, or integrate LLMs with external knowledge retrieval (i.e., retrieval-augmented generation). However, off-the-shelf retrievers often struggle to identify relevant documents that require intensive temporal reasoning. To systematically study time-sensitive question answering, we introduce the TempRAGEval benchmark, which repurposes existing datasets by incorporating temporal perturbations and gold evidence labels. As anticipated, all existing retrieval methods struggle with these temporal reasoning-intensive questions. We further propose Modular Retrieval (MRAG), a trainless framework that includes three modules: (1) Question Processing that decomposes question into a main content and a temporal constraint; (2) Retrieval and Summarization that retrieves evidence and uses LLMs to summarize according to the main content; (3) Semantic-Temporal Hybrid Ranking that scores each evidence summarization based on both semantic and temporal relevance. On TempRAGEval, MRAG significantly outperforms baseline retrievers in retrieval performance, leading to further improvements in final answer accuracy.

[Arxiv](https://arxiv.org/abs/2412.15540)
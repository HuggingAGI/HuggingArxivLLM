# # 弱到强的GraphRAG：弱检索器与大语言模型的融合，实现基于图的检索增强生成

发布时间：2025年06月26日

`RAG` `知识图谱` `问答系统`

> Weak-to-Strong GraphRAG: Aligning Weak Retrievers with Large Language Models for Graph-based Retrieval Augmented Generation

# 摘要

> 基于图的检索增强生成（RAG）使大型语言模型（LLMs）能够通过最新的知识图谱（KGs）中的结构化外部知识来生成有依据的回答，从而减少幻觉。然而，在基于图的RAG中，LLMs通常依赖于性能较弱的检索器：I) 由于缺乏真实标注数据，检索器通常在弱监督下进行训练，这往往会向LLMs引入无关的信号。II) 由于图数据的抽象性，检索到的知识通常以无序的形式呈现。为了解决这一问题，我们提出了精炼图增强生成（ReG），用于在基于图的RAG中对齐弱检索器与LLMs。具体来说，ReG通过引入LLM的反馈来消除无关信号并提升监督质量。同时，ReG引入了一个结构感知的重组模块，将检索结果重新组织为逻辑连贯的证据链。在知名基准测试中的实验表明，与不同LLM主干模型相比，ReG显著且一致地提升了性能，最高提升达10%。改进的监督质量使ReG能够以5%的训练数据达到最先进性能，并能够迁移到分布外的知识图谱。值得注意的是，当应用于基于推理的LLMs时，ReG最多可将推理令牌成本降低30%，并提升性能达4%。

> Graph-based retrieval-augmented generation (RAG) enables large language models (LLMs) to ground responses with structured external knowledge from up-to-date knowledge graphs (KGs) and reduce hallucinations. However, LLMs often rely on a weak retriever in graph-based RAG: I) Due to the lack of ground truth, the retriever is often trained on weak supervision, which often introduces spurious signals to the LLMs. II) Due to the abstraction of graph data, the retrieved knowledge is often presented in unorganized forms. To mitigate the issue, we present Refined Graph-based RAG (ReG) to align weak retrievers to LLMs for graph-based RAG. Specifically, ReG incorporates LLM feedback to get rid of spurious signals and improve the quality of the supervision. Meanwhile, ReG introduces a structure-aware reorganization module to refactor the retrieval results into logically coherent evidence chains. Experiments on prominent benchmarks demonstrate that ReG significantly and consistently brings improvements across different LLM backbones by up to 10%. The improved supervision quality enables ReG to match the state-of-the-art performance with 5% training data and to transfer to out-of-distribution KGs. Notably, when adopted to reasoning-based LLMs, ReG reduces the reasoning token cost by up to 30% and improves the performance by up to 4%.

[Arxiv](https://arxiv.org/abs/2506.22518)
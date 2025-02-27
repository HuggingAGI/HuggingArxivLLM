# 像管道和仪表图一样交流 (P&IDs)

发布时间：2025年02月26日

`LLM应用` `工业自动化` `制造业`

> Talking like Piping and Instrumentation Diagrams (P&IDs)

# 摘要

> 我们提出了一种通过自然语言与管道仪表图 (P&IDs) 交流的方法。具体来说，我们采用 DEXPI 数据模型将 P&IDs 转化为带标签的属性图，并将其与大型语言模型 (LLMs) 集成。该方法由三个主要部分组成：1) 使用我们的 pyDEXPI Python 包，将 P&IDs 从 DEXPI 格式转换为图表示。2) 一个从 pyDEXPI 生成 P&ID 知识图的工具。3) 通过图增强检索生成（图-RAG）将 P&ID 知识图与 LLMs 集成。这种方法让用户能够用自然语言与 P&IDs 交流，不仅提升了 LLM 从 P&IDs 中提取上下文数据的能力，还有效缓解了幻觉问题。借助 LLM 的大规模语料库，该模型还能解读 P&IDs 中的工艺信息，助力工程师日常工作。未来，这项研究将为其他生成式人工智能 (genAI) 解决方案以及 AI 辅助的 HAZOP 研究带来新的机遇。

> We propose a methodology that allows communication with Piping and Instrumentation Diagrams (P&IDs) using natural language. In particular, we represent P&IDs through the DEXPI data model as labeled property graphs and integrate them with Large Language Models (LLMs). The approach consists of three main parts: 1) P&IDs are cast into a graph representation from the DEXPI format using our pyDEXPI Python package. 2) A tool for generating P&ID knowledge graphs from pyDEXPI. 3) Integration of the P&ID knowledge graph to LLMs using graph-based retrieval augmented generation (graph-RAG). This approach allows users to communicate with P&IDs using natural language. It extends LLM's ability to retrieve contextual data from P&IDs and mitigate hallucinations. Leveraging the LLM's large corpus, the model is also able to interpret process information in PIDs, which could help engineers in their daily tasks. In the future, this work will also open up opportunities in the context of other generative Artificial Intelligence (genAI) solutions on P&IDs, and AI-assisted HAZOP studies.

[Arxiv](https://arxiv.org/abs/2502.18928)
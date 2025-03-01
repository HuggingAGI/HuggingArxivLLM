# HopRAG：通过多跳推理实现逻辑感知的检索增强生成
发布时间：2025年02月17日

`RAG`
> HopRAG: Multi-Hop Reasoning for Logic-Aware Retrieval-Augmented Generation
>
> 检索增强生成（RAG）系统常常面临检索不完美的问题，因为传统检索器侧重于词汇或语义相似性，而非逻辑相关性。为解决这一问题，我们提出了HopRAG，一个通过图结构知识探索增强检索的新型RAG框架。在索引阶段，HopRAG构建一个段落图，其中文本片段作为节点，通过LLM生成的伪查询建立逻辑连接作为边。在检索阶段，它采用检索-推理-剪枝机制：从词汇或语义相似的段落开始，系统通过伪查询和LLM推理引导多跳邻居探索，以识别真正相关的段落。大量实验表明，HopRAG表现出色，相比传统方法，答案准确率提高了76.78%，检索F1分数提升了65.07%。该仓库可在https://github.com/LIU-Hao-2002/HopRAG获取。
>
> https://arxiv.org/abs/2502.12442

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.12442](https://arxiv.org/abs/2502.12442)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
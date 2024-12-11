# 基于 RAG 的针对异构数据和文本的问答

发布时间：2024年12月10日

`RAG` `问答系统` `知识图谱`

> RAG-based Question Answering over Heterogeneous Data and Text

# 摘要

> 这篇文章介绍了用于处理非结构化文本、结构化表格和知识图谱问答的 QUASAR 系统，对各类来源统一对待。该系统采用基于 RAG 的架构，先进行证据检索，再生成答案，答案生成由中等规模语言模型驱动。尤为独特的是，QUASAR 具备问题理解组件，能得出更清晰的证据检索输入，还能在将最具信息量的部分输入答案生成环节之前，对检索到的证据进行重新排序和筛选。通过三个不同基准的实验表明，我们的方法回答质量颇高，与大型 GPT 模型不相上下甚至更优，同时计算成本和能源消耗低好几个数量级。

> This article presents the QUASAR system for question answering over unstructured text, structured tables, and knowledge graphs, with unified treatment of all sources. The system adopts a RAG-based architecture, with a pipeline of evidence retrieval followed by answer generation, with the latter powered by a moderate-sized language model. Additionally and uniquely, QUASAR has components for question understanding, to derive crisper input for evidence retrieval, and for re-ranking and filtering the retrieved evidence before feeding the most informative pieces into the answer generation. Experiments with three different benchmarks demonstrate the high answering quality of our approach, being on par with or better than large GPT models, while keeping the computational cost and energy consumption orders of magnitude lower.

[Arxiv](https://arxiv.org/abs/2412.07420)
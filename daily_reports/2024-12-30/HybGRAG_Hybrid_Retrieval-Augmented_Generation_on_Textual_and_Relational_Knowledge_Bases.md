# HybGRAG：关于文本和关系知识库的混合检索增强式生成
发布时间：2024年12月20日

`RAG`
> HybGRAG: Hybrid Retrieval-Augmented Generation on Textual and Relational Knowledge Bases
>
> 给定一个半结构化知识库（SKB），其中文本文档通过关系相互连接，怎样才能有效地检索相关信息来回答用户的问题呢？检索增强生成（RAG）会检索文档来辅助大型语言模型（LLM）回答问题；而图 RAG（GRAG）则以结构化知识库作为知识源。然而，很多问题都需要 SKB 中的文本和关系信息，即所谓的“混合”问题，这让检索过程变得复杂，也凸显出需要一种能利用这两种信息的混合检索方法。在本文中，通过实证分析，我们得出了关键见解，说明了为何现有方法在处理 SKB 上的混合问答（HQA）时可能会遇到难题。基于这些见解，我们提出了用于 HQA 的 HybGRAG，它由检索器组和评论模块构成，具有以下优点：（1）具有智能性，能结合评论模块的反馈自动优化输出；（2）具有适应性，能通过检索器组解决需要文本和关系信息的混合问题；（3）具有可解释性，能通过直观的优化路径为决策提供依据；（4）具有有效性，在 HQA 基准测试中超越了所有基线。在 STaRK 基准测试的实验中，HybGRAG 取得了显著的性能提升，Hit@1 的平均相对提升率达到 51%。
>
> https://arxiv.org/abs/2412.16311

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.16311](https://arxiv.org/abs/2412.16311)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
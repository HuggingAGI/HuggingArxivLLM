# 图式 RAG 工具融合
发布时间：2025年02月10日

`RAG`
> Graph RAG-Tool Fusion
>
> 最近，检索增强生成（RAG）在从工具知识库中选择相关工具方面取得了显著进展，使LLM代理能够将复杂的工具调用能力扩展到数百个甚至数千个外部工具、API或代理工具。然而，传统的基于RAG的工具检索方法未能捕捉到工具之间的结构化依赖关系，从而限制了检索到工具的依赖关系的准确性。例如，在一个向量数据库中，“获取股票价格”的API需要从“获取股票代码”的API中获取“股票代码”参数，而这两个API都依赖于操作系统级别的互联网连接工具。在本文中，我们通过引入Graph RAG-Tool Fusion来解决这一限制，这是一种结合了基于向量的检索和高效图遍历优势的即插即用方法，能够在预定义的工具知识图中捕获所有相关工具（节点）及其嵌套依赖关系（边）。我们还提出了ToolLinkOS，一个新的工具选择基准，包含573个虚构工具，覆盖15个以上行业，每个工具平均具有6.3个工具依赖关系。我们展示了Graph RAG-Tool Fusion在ToolLinkOS和ToolSandbox基准上分别比 naive RAG 提高了71.7%和22.1%的绝对改进（mAP@10）。ToolLinkOS数据集可在https://github.com/EliasLumer/Graph-RAG-Tool-Fusion-ToolLinkOS获取。
>
> https://arxiv.org/abs/2502.07223

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.07223](https://arxiv.org/abs/2502.07223)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)
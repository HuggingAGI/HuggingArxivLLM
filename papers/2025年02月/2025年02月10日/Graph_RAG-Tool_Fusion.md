# 图式 RAG 工具融合

发布时间：2025年02月10日

`RAG` `知识图谱` `系统集成`

> Graph RAG-Tool Fusion

# 摘要

> 最近，检索增强生成（RAG）在从工具知识库中选择相关工具方面取得了显著进展，使LLM代理能够将复杂的工具调用能力扩展到数百个甚至数千个外部工具、API或代理工具。然而，传统的基于RAG的工具检索方法未能捕捉到工具之间的结构化依赖关系，从而限制了检索到工具的依赖关系的准确性。例如，在一个向量数据库中，“获取股票价格”的API需要从“获取股票代码”的API中获取“股票代码”参数，而这两个API都依赖于操作系统级别的互联网连接工具。在本文中，我们通过引入Graph RAG-Tool Fusion来解决这一限制，这是一种结合了基于向量的检索和高效图遍历优势的即插即用方法，能够在预定义的工具知识图中捕获所有相关工具（节点）及其嵌套依赖关系（边）。我们还提出了ToolLinkOS，一个新的工具选择基准，包含573个虚构工具，覆盖15个以上行业，每个工具平均具有6.3个工具依赖关系。我们展示了Graph RAG-Tool Fusion在ToolLinkOS和ToolSandbox基准上分别比 naive RAG 提高了71.7%和22.1%的绝对改进（mAP@10）。ToolLinkOS数据集可在https://github.com/EliasLumer/Graph-RAG-Tool-Fusion-ToolLinkOS获取。

> Recent developments in retrieval-augmented generation (RAG) for selecting relevant tools from a tool knowledge base enable LLM agents to scale their complex tool calling capabilities to hundreds or thousands of external tools, APIs, or agents-as-tools. However, traditional RAG-based tool retrieval fails to capture structured dependencies between tools, limiting the retrieval accuracy of a retrieved tool's dependencies. For example, among a vector database of tools, a "get stock price" API requires a "stock ticker" parameter from a "get stock ticker" API, and both depend on OS-level internet connectivity tools. In this paper, we address this limitation by introducing Graph RAG-Tool Fusion, a novel plug-and-play approach that combines the strengths of vector-based retrieval with efficient graph traversal to capture all relevant tools (nodes) along with any nested dependencies (edges) within the predefined tool knowledge graph. We also present ToolLinkOS, a new tool selection benchmark of 573 fictional tools, spanning over 15 industries, each with an average of 6.3 tool dependencies. We demonstrate that Graph RAG-Tool Fusion achieves absolute improvements of 71.7% and 22.1% over naïve RAG on ToolLinkOS and ToolSandbox benchmarks, respectively (mAP@10). ToolLinkOS dataset is available at https://github.com/EliasLumer/Graph-RAG-Tool-Fusion-ToolLinkOS

[Arxiv](https://arxiv.org/abs/2502.07223)
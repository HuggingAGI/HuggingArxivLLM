# RAG-MCP：利用检索增强生成缓解LLM工具选择中的提示膨胀

发布时间：2025年05月06日

`RAG` `人工智能` `系统优化`

> RAG-MCP: Mitigating Prompt Bloat in LLM Tool Selection via Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）难以有效利用不断增加的外部工具（例如由模型上下文协议MCP\cite{IntroducingMCP}定义的工具），主要受限于prompt膨胀和选择复杂性。我们提出了RAG-MCP框架，通过卸载工具发现过程来解决这一问题。该框架在调用LLM前，利用语义检索从外部索引中为给定查询找到最相关的MCP(s)，仅将选定工具描述传递给模型，从而大幅减少prompt规模并简化决策流程。实验结果（包括MCP压力测试）显示，RAG-MCP在基准任务中将prompt令牌数量减少了50%以上，工具选择准确率从13.62%提升到43.13%，实现了三倍以上的提升。这一创新使LLMs能够实现更高效、更精准的工具集成。


> Large language models (LLMs) struggle to effectively utilize a growing number of external tools, such as those defined by the Model Context Protocol (MCP)\cite{IntroducingMCP}, due to prompt bloat and selection complexity. We introduce RAG-MCP, a Retrieval-Augmented Generation framework that overcomes this challenge by offloading tool discovery. RAG-MCP uses semantic retrieval to identify the most relevant MCP(s) for a given query from an external index before engaging the LLM. Only the selected tool descriptions are passed to the model, drastically reducing prompt size and simplifying decision-making. Experiments, including an MCP stress test, demonstrate RAG-MCP significantly cuts prompt tokens (e.g., by over 50%) and more than triples tool selection accuracy (43.13% vs 13.62% baseline) on benchmark tasks. RAG-MCP enables scalable and accurate tool integration for LLMs.

[Arxiv](https://arxiv.org/abs/2505.03275)
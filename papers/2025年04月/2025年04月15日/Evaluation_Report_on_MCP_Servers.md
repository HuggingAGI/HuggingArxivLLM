# # 评估报告：MCP 服务器

发布时间：2025年04月15日

`LLM应用` `搜索引擎` `AI应用`

> Evaluation Report on MCP Servers

# 摘要

> 随着大型语言模型（LLMs）的兴起，自2024年底以来，模型上下文协议（MCP）服务迅速发展。然而，这些服务的实际效果和运行效率尚待深入研究。为此，我们开发了一个名为MCPBench的评估框架，对几款主流MCP服务器进行了全面测试，涵盖准确性、响应时间和token使用效率等关键指标。实验数据显示，Bing Web Search作为表现最佳的MCP，实现了64%的准确率。更值得注意的是，通过引入声明式接口，MCP服务器的性能得到了显著提升。这项研究不仅引领了从零散探索到系统研究的转变，更为未来优化MCP技术、打造更高效的AI应用和数据检索方案指明了方向。

> With the rise of LLMs, a large number of Model Context Protocol (MCP) services have emerged since the end of 2024. However, the effectiveness and efficiency of MCP servers have not been well studied. To study these questions, we propose an evaluation framework, called MCPBench. We selected several widely used MCP server and conducted an experimental evaluation on their accuracy, time, and token usage. Our experiments showed that the most effective MCP, Bing Web Search, achieved an accuracy of 64%. Importantly, we found that the accuracy of MCP servers can be substantially enhanced by involving declarative interface. This research paves the way for further investigations into optimized MCP implementations, ultimately leading to better AI-driven applications and data retrieval solutions.

[Arxiv](https://arxiv.org/abs/2504.11094)
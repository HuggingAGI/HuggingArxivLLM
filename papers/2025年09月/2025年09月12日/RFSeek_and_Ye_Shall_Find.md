# RFSeek：求索必有所获

发布时间：2025年09月12日

`LLM应用` `基础理论`

> RFSeek and Ye Shall Find

# 摘要

> 请求评论文档（RFCs）是网络协议的详尽规范文档，但其散文式格式和冗长篇幅常阻碍对协议操作逻辑的精准理解。为此，我们提出交互式工具RFSeek，它能从RFC中自动提取协议逻辑的可视化摘要。RFSeek借助大型语言模型（LLMs）生成带来源链接的可探索图表，不仅呈现官方状态机，还能挖掘RFC文本中隐含的额外逻辑。与现有RFC可视化工具相比，RFSeek的可视化摘要更透明，也更易对照文本来源进行审计。我们通过TCP、QUIC、PPTP和DCCP等协议的一系列用例（如引导式知识提取和语义差异比较）展示了该工具的潜力。
  实际应用中，RFSeek不仅能重建部分规范中已有的RFC图表，更有趣的是，还能揭示文本中描述但图表缺失的关键逻辑（如节点或边）。我们将这种方法命名为“摘要可视化”，它为协议理解开辟了新方向：结合LLMs与正式的用户定制可视化，既能深化协议理解，也能支持稳健的协议实现。

> Requests for Comments (RFCs) are extensive specification documents for network protocols, but their prose-based format and their considerable length often impede precise operational understanding. We present RFSeek, an interactive tool that automatically extracts visual summaries of protocol logic from RFCs. RFSeek leverages large language models (LLMs) to generate provenance-linked, explorable diagrams, surfacing both official state machines and additional logic found only in the RFC text. Compared to existing RFC visualizations, RFSeek's visual summaries are more transparent and easier to audit against their textual source. We showcase the tool's potential through a series of use cases, including guided knowledge extraction and semantic diffing, applied to protocols such as TCP, QUIC, PPTP, and DCCP.
  In practice, RFSeek not only reconstructs the RFC diagrams included in some specifications, but, more interestingly, also uncovers important logic such as nodes or edges described in the text but missing from those diagrams. RFSeek further derives new visualization diagrams for complex RFCs, with QUIC as a representative case. Our approach, which we term \emph{Summary Visualization}, highlights a promising direction: combining LLMs with formal, user-customized visualizations to enhance protocol comprehension and support robust implementations.

[Arxiv](https://arxiv.org/abs/2509.10216)
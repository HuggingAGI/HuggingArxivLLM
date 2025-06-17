# 初探模型上下文协议（MCP）：研究其服务器的安全性和可维护性

发布时间：2025年06月16日

`LLM应用` `软件工程`

> Model Context Protocol (MCP) at First Glance: Studying the Security and Maintainability of MCP Servers

# 摘要

> 尽管GPT-4等基础模型（FMs）在金融和软件工程等领域应用日益广泛，但其对文本界面的依赖限制了现实世界的交互能力。为解决这一问题，FM供应商引入了工具调用功能，由此催生了众多具有不同工具接口的框架。2024年底，Anthropic推出了模型上下文协议（MCP），旨在统一这一工具生态系统，目前该协议已获得每周超过800万次SDK下载量，成为事实上的行业标准。

尽管被广泛采用，但MCP基于AI驱动的非确定性控制流引入了可持续性、安全性和可维护性方面的新风险，值得进一步审视。为此，我们首次针对MCP展开了大规模实证研究。借助先进的健康指标和结合通用静态分析工具与MCP专用扫描器的混合分析管道，我们评估了1,899个开源MCP服务器，对其健康状况、安全性和可维护性进行了评估。

尽管MCP服务器表现出强劲的健康指标，但我们发现了8种独特漏洞，其中仅3种与传统软件漏洞重叠。此外，7.2%的服务器存在通用漏洞，而5.5%的服务器则出现了MCP特有的工具投毒问题。就可维护性而言，尽管66%的服务器存在代码异味，但仍有14.4%的服务器包含10种与先前研究重叠的bug模式。这些发现凸显了开发MCP专用漏洞检测技术的必要性，同时也印证了传统分析和重构实践的价值。

> Although Foundation Models (FMs), such as GPT-4, are increasingly used in domains like finance and software engineering, reliance on textual interfaces limits these models' real-world interaction. To address this, FM providers introduced tool calling-triggering a proliferation of frameworks with distinct tool interfaces. In late 2024, Anthropic introduced the Model Context Protocol (MCP) to standardize this tool ecosystem, which has become the de facto standard with over eight million weekly SDK downloads. Despite its adoption, MCP's AI-driven, non-deterministic control flow introduces new risks to sustainability, security, and maintainability, warranting closer examination.
  Towards this end, we present the first large-scale empirical study of MCP. Using state-of-the-art health metrics and a hybrid analysis pipeline, combining a general-purpose static analysis tool with an MCP-specific scanner, we evaluate 1,899 open-source MCP servers to assess their health, security, and maintainability. Despite MCP servers demonstrating strong health metrics, we identify eight distinct vulnerabilities-only three overlapping with traditional software vulnerabilities. Additionally, 7.2% of servers contain general vulnerabilities and 5.5% exhibit MCP-specific tool poisoning. Regarding maintainability, while 66% exhibit code smells, 14.4% contain ten bug patterns overlapping prior research. These findings highlight the need for MCP-specific vulnerability detection techniques while reaffirming the value of traditional analysis and refactoring practices.

[Arxiv](https://arxiv.org/abs/2506.13538)
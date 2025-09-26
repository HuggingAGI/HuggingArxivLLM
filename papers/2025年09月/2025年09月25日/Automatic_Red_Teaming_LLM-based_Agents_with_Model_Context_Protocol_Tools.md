# 利用模型上下文协议工具对基于LLM的智能体进行自动红队测试

发布时间：2025年09月25日

`Agent` `基础理论`

> Automatic Red Teaming LLM-based Agents with Model Context Protocol Tools

# 摘要

> 大型语言模型（LLMs）的卓越能力推动基于LLM的智能体在各领域广泛落地。为标准化这类智能体与环境的交互，模型上下文协议（MCP）工具已成为事实标准并被广泛集成。但MCP工具的引入也带来工具投毒攻击风险，可能操纵智能体行为。尽管已有研究识别出这些漏洞，但其红队方法多停留在概念验证阶段，导致在MCP工具投毒范式下，对LLM智能体进行自动、系统的红队测试仍是开放问题。为填补这一空白，我们提出AutoMalTool——一个通过生成恶意MCP工具对LLM智能体开展自动红队测试的框架。大量评估显示，AutoMalTool能高效生成恶意MCP工具，在规避现有检测机制的同时操纵主流LLM智能体行为，由此揭示了这些智能体的新型安全风险。

> The remarkable capability of large language models (LLMs) has led to the wide application of LLM-based agents in various domains. To standardize interactions between LLM-based agents and their environments, model context protocol (MCP) tools have become the de facto standard and are now widely integrated into these agents. However, the incorporation of MCP tools introduces the risk of tool poisoning attacks, which can manipulate the behavior of LLM-based agents. Although previous studies have identified such vulnerabilities, their red teaming approaches have largely remained at the proof-of-concept stage, leaving the automatic and systematic red teaming of LLM-based agents under the MCP tool poisoning paradigm an open question. To bridge this gap, we propose AutoMalTool, an automated red teaming framework for LLM-based agents by generating malicious MCP tools. Our extensive evaluation shows that AutoMalTool effectively generates malicious MCP tools capable of manipulating the behavior of mainstream LLM-based agents while evading current detection mechanisms, thereby revealing new security risks in these agents.

[Arxiv](https://arxiv.org/abs/2509.21011)
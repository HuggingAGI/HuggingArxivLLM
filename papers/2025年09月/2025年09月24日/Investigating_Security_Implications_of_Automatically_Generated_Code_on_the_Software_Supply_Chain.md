# 探究自动生成代码对软件供应链的安全影响

发布时间：2025年09月24日

`LLM应用` `基础理论`

> Investigating Security Implications of Automatically Generated Code on the Software Supply Chain

# 摘要

> 近年来，各类软件供应链（SSC）攻击已对全球造成严重风险。一旦开发人员将易遭SSC攻击的不安全代码片段集成到产品中，便可能引发严重后果。尤其是代码生成技术（如大型语言模型LLMs），已在开发者群体中广泛普及。但LLMs生成代码时存在固有缺陷，如虚构内容、错误信息及依赖过时训练数据，这些都会引发严重的软件供应链威胁。本文针对这些固有问题引发的SSC安全威胁展开研究，深入分析了三类威胁（含十一种潜在SSC相关威胁），涉及源代码中的外部组件及持续集成配置文件。研究发现，LLM生成代码中的部分威胁可让攻击者劫持软件与工作流，另有部分则可能形成潜在隐患，久而久之危及软件安全。为明确这些安全影响及严重程度，我们开发了工具SSCGuard，它基于在线收集的SSC相关问题生成439,138条提示词，并对GPT和Llama系列的四款主流LLM的响应进行了分析。结果显示，所有已识别的SSC相关威胁均持续存在。为缓解这些风险，我们提出两种防御方案：一是新颖的基于提示词的“确认链”（Chain-of-Confirmation）机制，以减少虚构内容；二是基于中间件的防御机制，用于向用户预警各类SSC威胁。

> In recent years, various software supply chain (SSC) attacks have posed significant risks to the global community. Severe consequences may arise if developers integrate insecure code snippets that are vulnerable to SSC attacks into their products. Particularly, code generation techniques, such as large language models (LLMs), have been widely utilized in the developer community. However, LLMs are known to suffer from inherent issues when generating code, including fabrication, misinformation, and reliance on outdated training data, all of which can result in serious software supply chain threats. In this paper, we investigate the security threats to the SSC that arise from these inherent issues. We examine three categories of threats, including eleven potential SSC-related threats, related to external components in source code, and continuous integration configuration files. We find some threats in LLM-generated code could enable attackers to hijack software and workflows, while some others might cause potential hidden threats that compromise the security of the software over time. To understand these security impacts and severity, we design a tool, SSCGuard, to generate 439,138 prompts based on SSC-related questions collected online, and analyze the responses of four popular LLMs from GPT and Llama. Our results show that all identified SSC-related threats persistently exist. To mitigate these risks, we propose a novel prompt-based defense mechanism, namely Chain-of-Confirmation, to reduce fabrication, and a middleware-based defense that informs users of various SSC threats.

[Arxiv](https://arxiv.org/abs/2509.20277)
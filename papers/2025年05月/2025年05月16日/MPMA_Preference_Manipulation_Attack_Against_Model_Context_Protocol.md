# MPMA：一种针对模型上下文协议的偏好操控攻击

发布时间：2025年05月16日

`LLM应用` `人工智能` `网络安全`

> MPMA: Preference Manipulation Attack Against Model Context Protocol

# 摘要

> 模型上下文协议 (MCP) 为大型语言模型 (LLMs) 访问外部数据和工具提供了标准化接口，推动了工具选择范式的革命性转变，并加速了 LLM 代理工具生态系统的扩展。然而，随着 MCP 的普及，第三方定制的 MCP 服务器版本暴露出潜在的安全漏洞。本文首次提出了一种新型安全威胁——MCP 偏好操纵攻击 (MPMA)。攻击者通过部署定制的 MCP 服务器，诱导 LLMs 将其优先级置于其他竞争服务器之上。这可能为攻击者带来经济收益，如付费 MCP 服务收入或免费服务器上的广告收益。为实现 MPMA，我们设计了直接偏好操纵攻击（$\mathtt{DPMA}$），通过在工具名称和描述中嵌入操纵性词汇实现显著效果。然而，这种直接修改易于察觉，缺乏隐蔽性。为此，我们进一步提出了基于遗传算法的广告偏好操纵攻击（$\mathtt{GAPMA}$）。该方法采用四种常用策略初始化描述，并结合遗传算法 (GA) 增强隐蔽性。实验结果表明，$\mathtt{GAPMA}$ 在效果和隐蔽性之间实现了良好平衡。本研究揭示了 MCP 在开放生态系统中的关键漏洞，凸显了构建 robust 防御机制以保障 MCP 生态系统公平性的紧迫需求。

> Model Context Protocol (MCP) standardizes interface mapping for large language models (LLMs) to access external data and tools, which revolutionizes the paradigm of tool selection and facilitates the rapid expansion of the LLM agent tool ecosystem. However, as the MCP is increasingly adopted, third-party customized versions of the MCP server expose potential security vulnerabilities. In this paper, we first introduce a novel security threat, which we term the MCP Preference Manipulation Attack (MPMA). An attacker deploys a customized MCP server to manipulate LLMs, causing them to prioritize it over other competing MCP servers. This can result in economic benefits for attackers, such as revenue from paid MCP services or advertising income generated from free servers. To achieve MPMA, we first design a Direct Preference Manipulation Attack ($\mathtt{DPMA}$) that achieves significant effectiveness by inserting the manipulative word and phrases into the tool name and description. However, such a direct modification is obvious to users and lacks stealthiness. To address these limitations, we further propose Genetic-based Advertising Preference Manipulation Attack ($\mathtt{GAPMA}$). $\mathtt{GAPMA}$ employs four commonly used strategies to initialize descriptions and integrates a Genetic Algorithm (GA) to enhance stealthiness. The experiment results demonstrate that $\mathtt{GAPMA}$ balances high effectiveness and stealthiness. Our study reveals a critical vulnerability of the MCP in open ecosystems, highlighting an urgent need for robust defense mechanisms to ensure the fairness of the MCP ecosystem.

[Arxiv](https://arxiv.org/abs/2505.11154)
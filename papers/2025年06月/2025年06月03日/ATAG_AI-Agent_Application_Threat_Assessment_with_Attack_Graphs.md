# ATAG：基于攻击图的AI代理威胁评估应用

发布时间：2025年06月03日

`Agent` `人工智能` `网络安全`

> ATAG: AI-Agent Application Threat Assessment with Attack Graphs

# 摘要

> 评估由大型语言模型（LLMs）驱动的多智能体系统（MASs）的安全性面临两大挑战：系统的复杂内部动态和LLM漏洞的不断演变。传统攻击图（AG）方法难以有效建模针对LLMs的攻击。为此，我们提出了AI-代理应用威胁评估与攻击图（ATAG），一个专注于系统化分析AI-代理应用安全风险的创新框架。ATAG基于MulVAL逻辑攻击图生成工具，通过自定义事实和交互规则，精准描绘AI-代理的拓扑结构、漏洞及攻击场景。为推动LLM漏洞文档的标准化，我们还开发了LLM漏洞数据库（LVD）。通过在两个多智能体应用中的实际应用，ATAG展现了其在建模和生成复杂多步骤攻击场景攻击图方面的强大能力，这些攻击场景涵盖了提示注入、过度代理、敏感信息泄露和不安全输出处理等漏洞。ATAG为构建多智能体AI系统（MAASs）中的复杂攻击路径理解、可视化和优先处理提供了一套强大工具，标志着在多智能体应用中主动识别和缓解AI-代理威胁的重要进展。

> Evaluating the security of multi-agent systems (MASs) powered by large language models (LLMs) is challenging, primarily because of the systems' complex internal dynamics and the evolving nature of LLM vulnerabilities. Traditional attack graph (AG) methods often lack the specific capabilities to model attacks on LLMs. This paper introduces AI-agent application Threat assessment with Attack Graphs (ATAG), a novel framework designed to systematically analyze the security risks associated with AI-agent applications. ATAG extends the MulVAL logic-based AG generation tool with custom facts and interaction rules to accurately represent AI-agent topologies, vulnerabilities, and attack scenarios. As part of this research, we also created the LLM vulnerability database (LVD) to initiate the process of standardizing LLM vulnerabilities documentation. To demonstrate ATAG's efficacy, we applied it to two multi-agent applications. Our case studies demonstrated the framework's ability to model and generate AGs for sophisticated, multi-step attack scenarios exploiting vulnerabilities such as prompt injection, excessive agency, sensitive information disclosure, and insecure output handling across interconnected agents. ATAG is an important step toward a robust methodology and toolset to help understand, visualize, and prioritize complex attack paths in multi-agent AI systems (MAASs). It facilitates proactive identification and mitigation of AI-agent threats in multi-agent applications.

[Arxiv](https://arxiv.org/abs/2506.02859)
# 新兴AI搜索引擎面临的威胁日益加剧

发布时间：2025年02月07日

`LLM应用

理由：这篇论文主要讨论了大型语言模型（LLMs）在AI驱动的搜索引擎（AIPSEs）中的应用，特别是其安全风险及防御机制。论文涉及了LLMs在实际应用中的问题（如引用恶意内容）以及如何通过基于代理的防御机制来应对这些风险。因此，这篇论文应归类为LLM应用。` `搜索引擎` `网络安全`

> The Rising Threat to Emerging AI-Powered Search Engines

# 摘要

> # 摘要
最近大型语言模型（LLMs）的突破性进展显著提升了AI驱动的搜索引擎（AIPSEs）的能力，通过整合外部数据库与现有知识，提供了精准且高效的响应。然而，我们发现这些AIPSEs存在引用恶意内容或恶意网站的风险，导致有害或未经核实的信息传播。本研究首次对七个生产级AIPSEs进行了安全风险量化，系统定义了威胁模型和风险级别，并评估了其对各类查询的响应。基于PhishTank、ThreatBook和LevelBlue的数据，我们发现AIPSEs即使在良性查询（如使用良性关键词）下，也频繁生成包含恶意URL的有害内容。此外，直接查询URL会提高风险级别，而使用自然语言查询则能降低风险。我们还通过在线文档欺骗和钓鱼的案例研究，展示了在现实环境中欺骗AIPSEs的容易程度。为应对这些风险，我们开发了一种基于代理的防御机制，包括基于GPT-4o的内容精炼工具和基于XGBoost的URL检测器。评估结果显示，该防御机制能有效降低风险，但会减少可用信息。我们的研究强调了在AIPSEs中实施强有力安全措施的紧迫性。

> Recent advancements in Large Language Models (LLMs) have significantly enhanced the capabilities of AI-Powered Search Engines (AIPSEs), offering precise and efficient responses by integrating external databases with pre-existing knowledge. However, we observe that these AIPSEs raise risks such as quoting malicious content or citing malicious websites, leading to harmful or unverified information dissemination. In this study, we conduct the first safety risk quantification on seven production AIPSEs by systematically defining the threat model, risk level, and evaluating responses to various query types. With data collected from PhishTank, ThreatBook, and LevelBlue, our findings reveal that AIPSEs frequently generate harmful content that contains malicious URLs even with benign queries (e.g., with benign keywords). We also observe that directly query URL will increase the risk level while query with natural language will mitigate such risk. We further perform two case studies on online document spoofing and phishing to show the ease of deceiving AIPSEs in the real-world setting. To mitigate these risks, we develop an agent-based defense with a GPT-4o-based content refinement tool and an XGBoost-based URL detector. Our evaluation shows that our defense can effectively reduce the risk but with the cost of reducing available information. Our research highlights the urgent need for robust safety measures in AIPSEs.

[Arxiv](https://arxiv.org/abs/2502.04951)
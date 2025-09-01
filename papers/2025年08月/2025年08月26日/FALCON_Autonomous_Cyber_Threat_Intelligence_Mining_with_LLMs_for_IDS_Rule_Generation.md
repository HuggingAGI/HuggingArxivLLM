# FALCON：基于LLMs的自主网络威胁情报挖掘与IDS规则生成

发布时间：2025年08月26日

`Agent` `基础理论`

> FALCON: Autonomous Cyber Threat Intelligence Mining with LLMs for IDS Rule Generation

# 摘要

> 基于签名的入侵检测系统（IDS）通过匹配网络或主机活动与预定义规则来识别恶意行为。这些规则源于海量网络威胁情报（CTI），涵盖经自动化工具与手动威胁分析（如沙箱技术）获取的攻击特征和行为模式。CTI随后转化为IDS引擎的可执行规则，实现实时检测与防御。但网络威胁的持续演变迫使规则需频繁更新，导致部署延迟，削弱整体安全防护能力。而近期由大型语言模型（LLMs）驱动的智能体系统取得突破，为IDS规则的自主生成与内部评估提供了可能。我们提出FALCON——一个自主智能体框架，可从CTI数据实时生成可部署的IDS规则，并通过内置多阶段验证器完成评估。为体现通用性，我们同时面向网络层（Snort）和主机层（YARA）场景，构建了含对应CTI的综合IDS规则数据集。评估结果显示，FALCON在自动规则生成上表现卓越：定性评估平均准确率达95%，多位网络安全分析师在所有指标上的评分者一致性达84%。这些结果证实，LLM驱动的数据挖掘在实时网络威胁防御中具备可行性与高效性。

> Signature-based Intrusion Detection Systems (IDS) detect malicious activities by matching network or host activity against predefined rules. These rules are derived from extensive Cyber Threat Intelligence (CTI), which includes attack signatures and behavioral patterns obtained through automated tools and manual threat analysis, such as sandboxing. The CTI is then transformed into actionable rules for the IDS engine, enabling real-time detection and prevention. However, the constant evolution of cyber threats necessitates frequent rule updates, which delay deployment time and weaken overall security readiness. Recent advancements in agentic systems powered by Large Language Models (LLMs) offer the potential for autonomous IDS rule generation with internal evaluation. We introduce FALCON, an autonomous agentic framework that generates deployable IDS rules from CTI data in real-time and evaluates them using built-in multi-phased validators. To demonstrate versatility, we target both network (Snort) and host-based (YARA) mediums and construct a comprehensive dataset of IDS rules with their corresponding CTIs. Our evaluations indicate FALCON excels in automatic rule generation, with an average of 95% accuracy validated by qualitative evaluation with 84% inter-rater agreement among multiple cybersecurity analysts across all metrics. These results underscore the feasibility and effectiveness of LLM-driven data mining for real-time cyber threat mitigation.

[Arxiv](https://arxiv.org/abs/2508.18684)
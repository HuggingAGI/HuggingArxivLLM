# 基于LLM的截图信息窃取者传播途径识别：以Aurora为例

发布时间：2025年07月31日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLMs）来分析感染截图，提取妥协指标，映射感染向量，并追踪恶意软件活动。研究展示了LLMs在恶意软件分析和威胁情报方面的实际应用，属于LLM的应用层面研究。` `网络安全` `恶意软件分析`

> LLM-Based Identification of Infostealer Infection Vectors from Screenshots: The Case of Aurora

# 摘要

> 信息窃取者从感染的系统中窃取凭证、会话cookie和敏感数据。2024年报告了超过2900万条窃取日志，大规模的手动分析和缓解几乎不可行。尽管大多数研究集中在主动恶意软件检测上，但利用窃取日志及其相关工件进行反应性分析仍存在显著空白。特别是感染工件，如截图和受攻击点捕获的图像，基本上被现有文献忽视。

本文提出了一种利用大型语言模型（LLMs），特别是gpt-4o-mini，来分析感染截图的新方法。通过这种方法，我们可以提取潜在的妥协指标，映射感染向量并追踪恶意软件活动。以Aurora信息窃取者为例，我们展示了LLMs如何处理截图以识别感染向量，如恶意URL、安装程序文件和被利用的软件主题。

我们的方法从1000张截图中提取了337个可操作的URL和246个相关文件，揭示了关键的恶意软件分发方法和社会工程战术。通过关联提取的文件名、URL和感染主题，我们识别了三个不同的恶意软件活动，展示了LLM驱动分析在揭示感染工作流程和增强威胁情报方面的潜力。

通过将恶意软件分析从传统的基于日志的检测方法转向基于感染截图的反应式方法，这项研究提供了一种可扩展的方法来识别感染向量并实现早期干预。

> Infostealers exfiltrate credentials, session cookies, and sensitive data from infected systems. With over 29 million stealer logs reported in 2024, manual analysis and mitigation at scale are virtually unfeasible/unpractical. While most research focuses on proactive malware detection, a significant gap remains in leveraging reactive analysis of stealer logs and their associated artifacts. Specifically, infection artifacts such as screenshots, image captured at the point of compromise, are largely overlooked by the current literature. This paper introduces a novel approach leveraging Large Language Models (LLMs), more specifically gpt-4o-mini, to analyze infection screenshots to extract potential Indicators of Compromise (IoCs), map infection vectors, and track campaigns. Focusing on the Aurora infostealer, we demonstrate how LLMs can process screenshots to identify infection vectors, such as malicious URLs, installer files, and exploited software themes. Our method extracted 337 actionable URLs and 246 relevant files from 1000 screenshots, revealing key malware distribution methods and social engineering tactics. By correlating extracted filenames, URLs, and infection themes, we identified three distinct malware campaigns, demonstrating the potential of LLM-driven analysis for uncovering infection workflows and enhancing threat intelligence. By shifting malware analysis from traditional log-based detection methods to a reactive, artifact-driven approach that leverages infection screenshots, this research presents a scalable method for identifying infection vectors and enabling early intervention.

[Arxiv](https://arxiv.org/abs/2507.23611)
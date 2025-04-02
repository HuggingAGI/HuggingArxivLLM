# LLM助力主动威胁情报，赋能自动化推理

发布时间：2025年04月01日

`RAG` `网络安全` `威胁情报管理`

> LLM-Assisted Proactive Threat Intelligence for Automated Reasoning

# 摘要

> 面对不断演变的网络威胁，我们需要更先进和复杂的防御技术。本研究提出了一种创新方法，通过结合大型语言模型（LLMs）与增强检索生成（RAG）系统，并引入持续的威胁情报数据源，显著提升了实时网络安全威胁的检测与响应能力。基于GPT-4o等大型语言模型的最新进展，以及RAG技术的创新应用，我们的方法突破了传统静态威胁分析的局限，成功整合了动态实时数据源。通过RAG技术，我们实现了对最新威胁情报的实时获取，这是现有GPT-4o模型无法实现的。我们采用Patrowl框架，自动化检索包括CVE、CWE、EPSS和KEV等多源网络安全威胁情报数据，并结合all-mpnet-base-v2模型进行高维向量嵌入，存储和查询于Milvus中。通过多个案例研究，我们展示了该系统在处理近期披露的漏洞、KEVs和高EPSS评分CVE方面相较于基准GPT-4o的显著提升。这项研究不仅推动了大型语言模型在网络安全领域的应用，还为自动化智能网络威胁信息管理系统的开发奠定了坚实基础，填补了当前网络安全实践中的关键空白。

> Successful defense against dynamically evolving cyber threats requires advanced and sophisticated techniques. This research presents a novel approach to enhance real-time cybersecurity threat detection and response by integrating large language models (LLMs) and Retrieval-Augmented Generation (RAG) systems with continuous threat intelligence feeds. Leveraging recent advancements in LLMs, specifically GPT-4o, and the innovative application of RAG techniques, our approach addresses the limitations of traditional static threat analysis by incorporating dynamic, real-time data sources. We leveraged RAG to get the latest information in real-time for threat intelligence, which is not possible in the existing GPT-4o model. We employ the Patrowl framework to automate the retrieval of diverse cybersecurity threat intelligence feeds, including Common Vulnerabilities and Exposures (CVE), Common Weakness Enumeration (CWE), Exploit Prediction Scoring System (EPSS), and Known Exploited Vulnerabilities (KEV) databases, and integrate these with the all-mpnet-base-v2 model for high-dimensional vector embeddings, stored and queried in Milvus. We demonstrate our system's efficacy through a series of case studies, revealing significant improvements in addressing recently disclosed vulnerabilities, KEVs, and high-EPSS-score CVEs compared to the baseline GPT-4o. This work not only advances the role of LLMs in cybersecurity but also establishes a robust foundation for the development of automated intelligent cyberthreat information management systems, addressing crucial gaps in current cybersecurity practices.

[Arxiv](https://arxiv.org/abs/2504.00428)
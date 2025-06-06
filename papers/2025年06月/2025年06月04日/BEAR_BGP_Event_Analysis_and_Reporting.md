# BEAR - BGP事件分析与报告

发布时间：2025年06月04日

`LLM应用` `网络管理`

> BEAR: BGP Event Analysis and Reporting

# 摘要

> 互联网由相互连接的自治系统（AS）构成，这些系统通过边界网关协议（BGP）实现域间路由。BGP异常，如路由泄露和劫持，会导致流量被引导至未经授权或低效的路径，严重威胁网络的可靠性和安全性。现有的基于规则和机器学习的方法虽然能利用结构化指标检测这些异常，但解读事件并提出补救措施仍需依赖具备深厚BGP知识的专家。本文提出BEAR（BGP事件分析与报告）框架，该框架借助大型语言模型（LLMs）自动生成详尽报告，解释检测到的BGP异常事件。BEAR通过多步骤推理，将表格化的BGP数据转化为详尽的文本叙述，从而提升可解释性和分析精度。针对公开BGP异常数据的稀缺性，我们还开发了一种基于LLMs的合成数据生成框架。在真实和合成数据集上的评估结果表明，BEAR实现了100%的准确率，超越了基于链式思维和上下文学习的基线方法。这项研究首次实现了BGP异常事件的自动化解释，为网络管理提供了宝贵的运营洞见。

> The Internet comprises of interconnected, independently managed Autonomous Systems (AS) that rely on the Border Gateway Protocol (BGP) for inter-domain routing. BGP anomalies--such as route leaks and hijacks--can divert traffic through unauthorized or inefficient paths, jeopardizing network reliability and security. Although existing rule-based and machine learning methods can detect these anomalies using structured metrics, they still require experts with in-depth BGP knowledge of, for example, AS relationships and historical incidents, to interpret events and propose remediation. In this paper, we introduce BEAR (BGP Event Analysis and Reporting), a novel framework that leverages large language models (LLMs) to automatically generate comprehensive reports explaining detected BGP anomaly events. BEAR employs a multi-step reasoning process that translates tabular BGP data into detailed textual narratives, enhancing interpretability and analytical precision. To address the limited availability of publicly documented BGP anomalies, we also present a synthetic data generation framework powered by LLMs. Evaluations on both real and synthetic datasets demonstrate that BEAR achieves 100% accuracy, outperforming Chain-of-Thought and in-context learning baselines. This work pioneers an automated approach for explaining BGP anomaly events, offering valuable operational insights for network management.

[Arxiv](https://arxiv.org/abs/2506.04514)
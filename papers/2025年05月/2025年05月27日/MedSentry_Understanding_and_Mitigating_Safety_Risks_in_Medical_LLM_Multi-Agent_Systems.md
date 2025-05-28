# MedSentry：深入理解与有效缓解医疗LLM多智能体系统中的安全风险

发布时间：2025年05月27日

`LLM应用` `多智能体系统`

> MedSentry: Understanding and Mitigating Safety Risks in Medical LLM Multi-Agent Systems

# 摘要

> 随着大型语言模型（LLMs）在医疗领域的广泛应用，确保其安全性，特别是在协作型多智能体配置中，至关重要。本文介绍了MedSentry，一个包含5000个对抗性医疗提示的基准数据集，涵盖25种威胁类别和100个子主题。与该数据集配套，我们开发了一个端到端的攻击-防御评估流水线，系统性地分析了四种代表性的多智能体拓扑结构（Layers、SharedPool、Centralized和Decentralized）如何抵御来自'暗黑人格'智能体的攻击。

我们的研究发现，这些架构在处理信息污染和保持稳健决策方面存在显著差异，揭示了其潜在的漏洞机制。例如，SharedPool的开放信息共享使其极易受到攻击，而Decentralized架构则表现出更强的抗风险能力，得益于其固有的冗余和隔离特性。为降低这些风险，我们提出了一种人格尺度检测与修复机制，能够识别并修复恶意智能体，将系统安全性恢复至接近基线水平。

MedSentry因此不仅提供了一个严谨的评估框架，还提供了实用的防御策略，为设计更安全的LLM多智能体系统在医疗领域的应用提供了指导。

> As large language models (LLMs) are increasingly deployed in healthcare, ensuring their safety, particularly within collaborative multi-agent configurations, is paramount. In this paper we introduce MedSentry, a benchmark comprising 5 000 adversarial medical prompts spanning 25 threat categories with 100 subthemes. Coupled with this dataset, we develop an end-to-end attack-defense evaluation pipeline to systematically analyze how four representative multi-agent topologies (Layers, SharedPool, Centralized, and Decentralized) withstand attacks from 'dark-personality' agents. Our findings reveal critical differences in how these architectures handle information contamination and maintain robust decision-making, exposing their underlying vulnerability mechanisms. For instance, SharedPool's open information sharing makes it highly susceptible, whereas Decentralized architectures exhibit greater resilience thanks to inherent redundancy and isolation. To mitigate these risks, we propose a personality-scale detection and correction mechanism that identifies and rehabilitates malicious agents, restoring system safety to near-baseline levels. MedSentry thus furnishes both a rigorous evaluation framework and practical defense strategies that guide the design of safer LLM-based multi-agent systems in medical domains.

[Arxiv](https://arxiv.org/abs/2505.20824)
# 基于图表示的联邦大型语言模型于网络安全边缘环境下的模型中毒研究

发布时间：2025年07月02日

`LLM应用` `网络安全` `隐私保护`

> Graph Representation-based Model Poisoning on Federated LLMs in CyberEdge Networks

# 摘要

> 联邦大型语言模型（FedLLMs）在保护数据隐私的同时，为 CyberEdge 网络提供了强大的生成能力。然而，FedLLMs仍然极易受到模型中毒攻击的影响。本文首先回顾了近期针对 FedLLMs 的模型中毒技术及现有的防御机制，重点指出了在非独立同分布（non-IID）文本分布下存在的关键限制。当前的防御措施主要依赖于基于距离的异常检测或范数约束，其假设是恶意更新与良性统计量存在显著偏差。然而，这一假设在面对针对十亿参数规模 LLMs 的自适应攻击者时可能失效。接下来，本文深入探讨了新兴的基于图表示的模型中毒攻击（Graph Representation-Based Model Poisoning, GRMP），这是一种新型攻击范式，通过利用诚实客户端梯度之间的高阶相关性，生成难以区分于合法模型更新的恶意更新。GRMP 可以有效避开先进的防御机制，导致模型准确性和性能大幅下降。此外，本文还概述了未来的研究路线图，强调了图感知安全聚合方法、FedLLMs 特定的漏洞度量以及评估框架的重要性，以增强未来联邦语言模型部署的鲁棒性。

> Federated large language models (FedLLMs) provide powerful generative capabilities in CyberEdge networks while protecting data privacy. However, FedLLMs remains highly vulnerable to model poisoning attacks. This article first reviews recent model poisoning techniques and existing defense mechanisms for FedLLMs, highlighting critical limitations, particularly under non-IID text distributions. In particular, current defenses primarily utilize distance-based outlier detection or norm constraints, operating under the assumption that adversarial updates significantly diverge from benign statistics. This assumption can fail when facing adaptive attackers targeting billionparameter LLMs. Next, this article investigates emerging Graph Representation-Based Model Poisoning (GRMP), a novel attack paradigm that leverages higher-order correlations among honest client gradients to synthesize malicious updates indistinguishable from legitimate model updates. GRMP can effectively evade advanced defenses, resulting in substantial accuracy loss and performance degradation. Moreover, this article outlines a research roadmap emphasizing the importance of graph-aware secure aggregation methods, FedLLMs-specific vulnerability metrics, and evaluation frameworks to strengthen the robustness of future federated language model deployments.

[Arxiv](https://arxiv.org/abs/2507.01694)
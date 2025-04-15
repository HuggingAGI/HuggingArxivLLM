# StruPhantom: 基于大型语言模型的黑盒表格智能体进化注入攻击研究

发布时间：2025年04月13日

`Agent`

> StruPhantom: Evolutionary Injection Attacks on Black-Box Tabular Agents Powered by Large Language Models

# 摘要

> 大型语言模型（LLMs）驱动的自主代理为处理表格数据的商业应用带来了革命性变化，即所谓的表格代理。尽管LLMs易受外部数据源的提示注入攻击，但表格代理通过严格的格式和规则限制了攻击载荷的效果，除非代理能够深入多层结构化数据进行整合。为解决这一难题，我们提出了一种名为StruPhantom的新型攻击方法，专门针对黑盒LLM驱动的表格代理。该攻击设计了一种进化优化流程，结合约束蒙特卡洛树搜索和偏离主题评估器，持续优化攻击载荷。StruPhantom系统地探索并利用目标应用的弱点，实现目标劫持。我们的评估验证了StruPhantom在多种LLM代理和攻击场景中的有效性，包括真实世界平台上的应用。与基准方法相比，StruPhantom在迫使应用响应中包含钓鱼链接或恶意代码方面，成功率达到50%以上。

> The proliferation of autonomous agents powered by large language models (LLMs) has revolutionized popular business applications dealing with tabular data, i.e., tabular agents. Although LLMs are observed to be vulnerable against prompt injection attacks from external data sources, tabular agents impose strict data formats and predefined rules on the attacker's payload, which are ineffective unless the agent navigates multiple layers of structural data to incorporate the payload. To address the challenge, we present a novel attack termed StruPhantom which specifically targets black-box LLM-powered tabular agents. Our attack designs an evolutionary optimization procedure which continually refines attack payloads via the proposed constrained Monte Carlo Tree Search augmented by an off-topic evaluator. StruPhantom helps systematically explore and exploit the weaknesses of target applications to achieve goal hijacking. Our evaluation validates the effectiveness of StruPhantom across various LLM-based agents, including those on real-world platforms, and attack scenarios. Our attack achieves over 50% higher success rates than baselines in enforcing the application's response to contain phishing links or malicious codes.

[Arxiv](https://arxiv.org/abs/2504.09841)
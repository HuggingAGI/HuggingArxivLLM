# 思想纯净：链式思考攻击的防御范式

发布时间：2025年07月16日

`LLM理论` `人工智能`

> Thought Purity: Defense Paradigm For Chain-of-Thought Attack

# 摘要

> 强化学习训练的大型推理模型（如Deepseek-R1）在不断发展的大型语言模型领域中展现出强大的推理能力，但其安全性仍存在重大漏洞。这一弱点在链式思维（CoT）生成过程中尤为突出，因为对抗方法如后门提示攻击可系统性破坏模型的核心推理机制。新兴的链式思维攻击（CoTA）通过利用提示可控性揭示这一漏洞，同时以低成本手段削弱CoT安全性和任务性能。为解决这一安全与性能双重漏洞，我们提出"思维纯净度"（TP）：一种防御范式，系统性增强对恶意内容的抵抗力，同时保持操作效能。我们的解决方案通过三个协同组件实现：（1）安全优化的数据处理管道（2）强化学习增强的规则约束（3）自适应监控指标。我们的方法建立了针对强化学习对齐推理系统中CoTA漏洞的首个全面防御机制，显著推进了下一代AI架构的安全-功能性平衡。

> While reinforcement learning-trained Large Reasoning Models (LRMs, e.g., Deepseek-R1) demonstrate advanced reasoning capabilities in the evolving Large Language Models (LLMs) domain, their susceptibility to security threats remains a critical vulnerability. This weakness is particularly evident in Chain-of-Thought (CoT) generation processes, where adversarial methods like backdoor prompt attacks can systematically subvert the model's core reasoning mechanisms. The emerging Chain-of-Thought Attack (CoTA) reveals this vulnerability through exploiting prompt controllability, simultaneously degrading both CoT safety and task performance with low-cost interventions. To address this compounded security-performance vulnerability, we propose Thought Purity (TP): a defense paradigm that systematically strengthens resistance to malicious content while preserving operational efficacy. Our solution achieves this through three synergistic components: (1) a safety-optimized data processing pipeline (2) reinforcement learning-enhanced rule constraints (3) adaptive monitoring metrics. Our approach establishes the first comprehensive defense mechanism against CoTA vulnerabilities in reinforcement learning-aligned reasoning systems, significantly advancing the security-functionality equilibrium for next-generation AI architectures.

[Arxiv](https://arxiv.org/abs/2507.12314)
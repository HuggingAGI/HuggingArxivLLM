# G-Safeguard：基于拓扑结构的安全视角与处理方法，专为大型语言模型驱动的多智能体系统设计

发布时间：2025年02月16日

`Agent` `多智能体系统`

> G-Safeguard: A Topology-Guided Security Lens and Treatment on LLM-based Multi-agent Systems

# 摘要

> 基于大语言模型（LLM）的多智能体系统（MAS）在复杂任务中展现出卓越的能力，从协作问题解决到自主决策均表现不凡。然而，随着这些系统在关键应用中的广泛应用，对抗攻击、虚假信息传播和意外行为带来的安全风险日益凸显。为应对这一挑战，我们提出了G-Safeguard，这是一种基于拓扑的鲁棒LLM-MAS安全解决方案。它利用图神经网络在多智能体言论图中精准检测异常，并通过拓扑干预实现攻击修复。实验结果表明，G-Safeguard具有以下优势：（I）在多种攻击策略下表现出色，修复了40%以上的提示注入性能；（II）能够灵活适应不同LLM架构和大规模MAS；（III）可无缝集成到主流MAS中，同时提供可靠的安全保障。项目代码已开源，访问地址为https://github.com/wslong20/G-safeguard。

> Large Language Model (LLM)-based Multi-agent Systems (MAS) have demonstrated remarkable capabilities in various complex tasks, ranging from collaborative problem-solving to autonomous decision-making. However, as these systems become increasingly integrated into critical applications, their vulnerability to adversarial attacks, misinformation propagation, and unintended behaviors have raised significant concerns. To address this challenge, we introduce G-Safeguard, a topology-guided security lens and treatment for robust LLM-MAS, which leverages graph neural networks to detect anomalies on the multi-agent utterance graph and employ topological intervention for attack remediation. Extensive experiments demonstrate that G-Safeguard: (I) exhibits significant effectiveness under various attack strategies, recovering over 40% of the performance for prompt injection; (II) is highly adaptable to diverse LLM backbones and large-scale MAS; (III) can seamlessly combine with mainstream MAS with security guarantees. The code is available at https://github.com/wslong20/G-safeguard.

[Arxiv](https://arxiv.org/abs/2502.11127)
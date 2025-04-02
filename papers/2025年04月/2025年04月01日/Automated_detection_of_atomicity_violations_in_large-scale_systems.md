# 大规模系统中原子性违规的自动化检测

发布时间：2025年04月01日

`LLM应用` `软件安全` `软件工程`

> Automated detection of atomicity violations in large-scale systems

# 摘要

> 中断驱动程序中的原子性违规对关键系统软件安全构成重大威胁。这些违规源于共享资源的操作序列因异步中断而被打断。然而，检测原子性违规面临诸多挑战，主要源于程序状态空间庞大、应用级代码依赖复杂以及特定领域知识的复杂性。我们提出Clover，这是一个结合静态分析与大型语言模型（LLM）代理的创新混合框架，用于检测真实程序中的原子性违规。Clover首先通过静态分析提取关键代码片段和操作信息，随后启动一个多代理流程。在该流程中，专家代理利用特定领域知识识别原子性违规，随后由裁判代理进行验证。在RaceBench 2.1、SV-COMP和RWIP上的评估表明，Clover实现了92.3%的精度和86.6%的召回率，其F1分数相较于现有方法提升了27.4%至118.2%。

> Atomicity violations in interrupt-driven programs pose a significant threat to software safety in critical systems. These violations occur when the execution sequence of operations on shared resources is disrupted by asynchronous interrupts. Detecting atomicity violations is challenging due to the vast program state space, application-level code dependencies, and complex domain-specific knowledge. We propose Clover, a hybrid framework that integrates static analysis with large language model (LLM) agents to detect atomicity violations in real-world programs. Clover first performs static analysis to extract critical code snippets and operation information. It then initiates a multi-agent process, where the expert agent leverages domain-specific knowledge to detect atomicity violations, which are subsequently validated by the judge agent. Evaluations on RaceBench 2.1, SV-COMP, and RWIP demonstrate that Clover achieves a precision/recall of 92.3%/86.6%, outperforming existing approaches by 27.4-118.2% on F1-score.

[Arxiv](https://arxiv.org/abs/2504.00521)
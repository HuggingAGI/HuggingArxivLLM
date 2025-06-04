# SALAD：LLM辅助硬件设计的机器遗忘系统性评估

发布时间：2025年06月02日

`LLM应用

摘要中提到大型语言模型在硬件设计自动化中的应用，特别是Verilog代码生成，并讨论了相关的数据安全挑战。论文提出的方法SALAD用于缓解这些安全威胁，属于LLM的应用层面。` `硬件设计自动化` `数据安全`

> SALAD: Systematic Assessment of Machine Unlearing on LLM-Aided Hardware Design

# 摘要

> 大型语言模型（LLMs）为硬件设计自动化，尤其是Verilog代码生成，带来了革命性变革。然而，随之而来的是数据安全方面的重大挑战，包括Verilog评估数据污染、知识产权（IP）泄露以及恶意代码生成风险。我们推出SALAD，通过机器遗忘技术全面评估并缓解这些威胁。我们的方法无需重新训练，即可从预训练的LLMs中精准移除受污染的基准、敏感IP或恶意代码模式。通过详实的案例研究，我们证实了机器遗忘技术在降低LLM辅助硬件设计中数据安全风险方面的有效性。

> Large Language Models (LLMs) offer transformative capabilities for hardware design automation, particularly in Verilog code generation. However, they also pose significant data security challenges, including Verilog evaluation data contamination, intellectual property (IP) design leakage, and the risk of malicious Verilog generation. We introduce SALAD, a comprehensive assessment that leverages machine unlearning to mitigate these threats. Our approach enables the selective removal of contaminated benchmarks, sensitive IP and design artifacts, or malicious code patterns from pre-trained LLMs, all without requiring full retraining. Through detailed case studies, we demonstrate how machine unlearning techniques effectively reduce data security risks in LLM-aided hardware design.

[Arxiv](https://arxiv.org/abs/2506.02089)
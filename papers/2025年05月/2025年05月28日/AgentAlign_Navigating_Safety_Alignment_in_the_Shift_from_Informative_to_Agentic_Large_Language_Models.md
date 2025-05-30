# AgentAlign：指引安全对齐之路，从信息型到智能体型的大型语言模型转变中

发布时间：2025年05月28日

`Agent` `人工智能`

> AgentAlign: Navigating Safety Alignment in the Shift from Informative to Agentic Large Language Models

# 摘要

> 代理能力的获取使大型语言模型（LLMs）从“知识提供者”转变为“行动执行者”。这一转变在扩展LLMs能力边界的同时，也显著增加了其被恶意使用的风险。先前的研究表明，当前基于LLMs的代理即使在未遭受攻击的情况下，仍能执行大量恶意任务，这表明在后训练阶段，代理使用与安全性的对齐存在明显不足。

为解决这一问题，我们提出了AgentAlign，这是一个利用抽象行为链作为媒介进行安全性对齐数据合成的新框架。通过在模拟环境中实例化这些行为链与多样化的工具实例，我们的框架能够生成高度真实且可执行的指令，同时捕捉复杂的多步动态。此外，框架通过非恶意行为链解释，按比例合成良性指令，精确校准“有用”与“无害”之间的边界，从而确保模型的实用性。

在AgentHarm上的评估结果表明，使用我们的方法微调三个开源模型家族，显著提升了它们的安全性（改进幅度达35.8%至79.5%），同时对它们的有用性影响微乎其微，甚至有所提升，超越了各种提示方法的表现。数据集和代码均已开源。

> The acquisition of agentic capabilities has transformed LLMs from "knowledge providers" to "action executors", a trend that while expanding LLMs' capability boundaries, significantly increases their susceptibility to malicious use. Previous work has shown that current LLM-based agents execute numerous malicious tasks even without being attacked, indicating a deficiency in agentic use safety alignment during the post-training phase. To address this gap, we propose AgentAlign, a novel framework that leverages abstract behavior chains as a medium for safety alignment data synthesis. By instantiating these behavior chains in simulated environments with diverse tool instances, our framework enables the generation of highly authentic and executable instructions while capturing complex multi-step dynamics. The framework further ensures model utility by proportionally synthesizing benign instructions through non-malicious interpretations of behavior chains, precisely calibrating the boundary between helpfulness and harmlessness. Evaluation results on AgentHarm demonstrate that fine-tuning three families of open-source models using our method substantially improves their safety (35.8% to 79.5% improvement) while minimally impacting or even positively enhancing their helpfulness, outperforming various prompting methods. The dataset and code have both been open-sourced.

[Arxiv](https://arxiv.org/abs/2505.23020)
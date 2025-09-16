# ToolRM：面向工具调用大型语言模型的结果奖励模型

发布时间：2025年09月15日

`LLM应用` `基础理论`

> ToolRM: Outcome Reward Models for Tool-Calling Large Language Models

# 摘要

> 随着大型语言模型（LLMs）与外部工具的交互愈发频繁，工具使用的奖励建模已成为至关重要却研究不足的领域。现有的奖励模型主要针对自然语言输出训练，难以有效评估基于工具的推理与执行过程。为量化这一差距，我们推出了FC-RewardBench——首个专门用于系统评估奖励模型在工具调用场景下性能的基准。分析显示，当前奖励模型常遗漏有效工具使用的关键信号，这凸显了领域专用建模的迫切需求。为解决此问题，我们提出一种基于结果的奖励模型训练框架，其数据来源于宽松许可的开源权重LLM合成。我们训练了参数规模从17亿到140亿的模型，并在七个域外基准上进行了评估。这些模型在性能上持续超越通用基线，下游任务平均提升幅度高达25%，同时通过奖励引导过滤实现了数据高效的微调。

> As large language models (LLMs) increasingly interact with external tools, reward modeling for tool use has become a critical yet underexplored area. Existing reward models, trained primarily on natural language outputs, struggle to evaluate tool-based reasoning and execution. To quantify this gap, we introduce FC-RewardBench, the first benchmark designed to systematically assess reward models' performance in tool-calling scenarios. Our analysis shows that current reward models often miss key signals of effective tool use, highlighting the need for domain-specific modeling. To address this, we propose a training framework for outcome-based reward models using data synthesized from permissively licensed, open-weight LLMs. We train models ranging from 1.7B to 14B parameters and evaluate them across seven out-of-domain benchmarks. These models consistently outperform general-purpose baselines, achieving up to 25\% average improvement in downstream task performance and enabling data-efficient fine-tuning through reward-guided filtering.

[Arxiv](https://arxiv.org/abs/2509.11963)
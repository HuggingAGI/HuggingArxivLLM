# # 推理能力的扩展，失控：大型推理模型中的指令遵循评估
推理能力的扩展，失控：评估大型推理模型中的指令遵循情况

发布时间：2025年05月20日

`LLM应用

理由：这篇论文专注于评估和改进大型语言模型在数学推理任务中的指令遵循能力，属于LLM的应用层面研究。` `数学推理` `数学领域`

> Scaling Reasoning, Losing Control: Evaluating Instruction Following in Large Reasoning Models

# 摘要

> 指令遵循是实现大型语言模型 (LLMs) 与用户意图对齐的核心要素。尽管以推理为导向的模型在解决复杂数学问题方面表现出色，但它们对自然语言指令的遵循能力仍待深入研究。本研究推出了 MathIF，首个专注于评估数学推理任务中指令遵循能力的基准测试。

通过实证分析，我们发现推理能力的提升与模型可控性之间存在着持续的矛盾：推理能力越强的模型，往往越难遵循用户指令。研究发现，无论是经过蒸馏长思维链微调，还是采用推理导向强化学习训练的模型，在指令遵循能力上都会出现不同程度的下降，尤其在生成长度增加时表现更为明显。

有趣的是，我们还发现即使是最简单的干预措施，也能部分恢复模型的服从性，但这种改进通常需要以推理性能的降低为代价。这些发现不仅揭示了当前 LLM 训练范式中的根本性矛盾，也为开发更具指令感知能力的推理模型提供了重要研究方向。所有代码和数据均已开源，访问地址为 https://github.com/TingchenFu/MathIF。


> Instruction-following is essential for aligning large language models (LLMs) with user intent. While recent reasoning-oriented models exhibit impressive performance on complex mathematical problems, their ability to adhere to natural language instructions remains underexplored. In this work, we introduce MathIF, a dedicated benchmark for evaluating instruction-following in mathematical reasoning tasks. Our empirical analysis reveals a consistent tension between scaling up reasoning capacity and maintaining controllability, as models that reason more effectively often struggle to comply with user directives. We find that models tuned on distilled long chains-of-thought or trained with reasoning-oriented reinforcement learning often degrade in instruction adherence, especially when generation length increases. Furthermore, we show that even simple interventions can partially recover obedience, though at the cost of reasoning performance. These findings highlight a fundamental tension in current LLM training paradigms and motivate the need for more instruction-aware reasoning models. We release the code and data at https://github.com/TingchenFu/MathIF.

[Arxiv](https://arxiv.org/abs/2505.14810)
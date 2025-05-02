# 哪个代理导致任务失败，以及何时发生？大型语言模型多智能体系统的任务失败自动归因分析

发布时间：2025年04月30日

`Agent` `人工智能` `多智能体系统`

> Which Agent Causes Task Failures and When? On Automated Failure Attribution of LLM Multi-Agent Systems

# 摘要

> 大型语言模型（LLMs）多智能体系统中的故障归因，即识别导致任务失败的责任智能体和步骤，是系统调试的关键线索来源。然而，这一领域尚未得到充分探索，且需要大量人工介入。本文提出并定义了一个全新的研究方向：LLM多智能体系统的自动化故障归因。为支持这一研究，我们推出了Who&When数据集，该数据集整合了127个LLM多智能体系统的详尽故障日志，并通过精细标注将故障与具体智能体及关键错误步骤关联起来。基于Who&When数据集，我们开发并评估了三种自动化故障归因方法，总结了它们的优缺点。其中表现最佳的方法在识别故障责任智能体方面达到了53.5%的准确率，但在精确定位故障步骤方面仅达到14.2%。部分方法的表现甚至低于随机水平。即使是像OpenAI o1和DeepSeek R1这样的顶尖推理模型，也未能实现实际应用价值。这些结果凸显了该任务的复杂性，并强调了在这一领域进行深入研究的必要性。代码和数据集可在https://github.com/mingyin1/Agents_Failure_Attribution获取。

> Failure attribution in LLM multi-agent systems-identifying the agent and step responsible for task failures-provides crucial clues for systems debugging but remains underexplored and labor-intensive. In this paper, we propose and formulate a new research area: automated failure attribution for LLM multi-agent systems. To support this initiative, we introduce the Who&When dataset, comprising extensive failure logs from 127 LLM multi-agent systems with fine-grained annotations linking failures to specific agents and decisive error steps. Using the Who&When, we develop and evaluate three automated failure attribution methods, summarizing their corresponding pros and cons. The best method achieves 53.5% accuracy in identifying failure-responsible agents but only 14.2% in pinpointing failure steps, with some methods performing below random. Even SOTA reasoning models, such as OpenAI o1 and DeepSeek R1, fail to achieve practical usability. These results highlight the task's complexity and the need for further research in this area. Code and dataset are available at https://github.com/mingyin1/Agents_Failure_Attribution

[Arxiv](https://arxiv.org/abs/2505.00212)
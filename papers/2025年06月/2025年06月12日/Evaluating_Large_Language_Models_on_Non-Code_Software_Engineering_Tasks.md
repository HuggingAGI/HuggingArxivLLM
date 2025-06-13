# 大型语言模型在非代码软件工程任务上的评测研究

发布时间：2025年06月12日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在非代码软件工程任务中的应用潜力，提出了一个基准测试SELU，并评估了多个模型在这些任务中的表现。研究集中在实际应用和模型评估上，属于LLM的应用层面。` `软件工程` `计算机科学`

> Evaluating Large Language Models on Non-Code Software Engineering Tasks

# 摘要

> 大型语言模型（LLMs）在代码理解和生成方面展现出了非凡的能力，但在非代码软件工程（SE）任务中的应用潜力尚未得到充分挖掘。我们首次提出了一个全面的基准测试——“软件工程语言理解”（SELU），用于评估LLMs在17个非代码任务上的表现，涵盖从识别需求类型到估算 backlog 项的复杂性。SELU涵盖了分类、回归、命名实体识别（NER）和遮蔽语言建模（MLM）目标，数据来源包括代码仓库、问题追踪系统和开发者论坛。我们微调了22个开源LLMs，测试了两个专有模型，并训练了两个基线。通过F1-macro、SMAPE、F1-micro和准确率等指标衡量性能，并采用贝叶斯符号秩检验进行比较。结果显示，中等规模的解码器-only 模型表现出色，具有高平均性能和低跨任务方差。通过代码聚焦预训练进行领域适应可能仅带来适度改进。这些发现为非代码SE工作流程中的模型选择提供了指导，并为将SELU扩展到生成和设计导向场景提供了方向。

> Large Language Models (LLMs) have demonstrated remarkable capabilities in code understanding and generation; however, their effectiveness on non-code Software Engineering (SE) tasks remains underexplored. We present the first comprehensive benchmark, which we name `Software Engineering Language Understanding' (SELU), for evaluating LLMs on 17 non-code tasks, spanning from identifying whether a requirement is functional or non-functional to estimating the effort and complexity of backlog items. SELU covers classification, regression, Named Entity Recognition (NER), and Masked Language Modeling (MLM) targets, with data drawn from diverse sources such as code repositories, issue tracking systems, and developer forums. We fine-tune 22 open-source LLMs, prompt two proprietary alternatives, and train two baselines. Performance is measured using metrics such as F1-macro, SMAPE, F1-micro, and accuracy, and compared via the Bayesian signed-rank test. Our results show that moderate-scale decoder-only models consistently form a top-tier, exhibiting high mean performance and low across-task variance, while domain adaptation via code-focused pre-training might yield only modest improvements. These insights guide model selection for non-code SE workflows and highlight directions for expanding SELU to generative and design-oriented scenarios.

[Arxiv](https://arxiv.org/abs/2506.10833)
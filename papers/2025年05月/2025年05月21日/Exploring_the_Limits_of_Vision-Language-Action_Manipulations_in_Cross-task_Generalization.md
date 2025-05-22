# Exploring the Limits of Vision-Language-Action Manipulations in Cross-task Generalization
在跨任务泛化中探索视觉-语言-动作操作的极限

发布时间：2025年05月21日

`Agent` `机器人` `机器人操作`

> Exploring the Limits of Vision-Language-Action Manipulations in Cross-task Generalization

# 摘要

> 实现开放世界环境下的通用机器人操作，关键在于视觉语言动作（VLA）模型在未见过任务上的泛化能力。然而，现有VLA模型的跨任务泛化能力研究仍显不足。为此，我们推出了AGNOSTOS——一个全新的模拟基准测试平台，专注于严格评估操作任务中的跨任务零样本泛化能力。该平台包含23个独特设计的未见过操作任务，与常见训练任务分布不同，并通过两个难度级别的泛化评估来测试模型的鲁棒性。系统性评估结果表明，尽管当前VLA模型基于多样化数据集进行训练，但在泛化到这些未见过任务时仍显乏力。为突破这一限制，我们提出了跨任务上下文操作（X-ICM）方法。该方法通过在大型语言模型（LLMs）中引入已见任务的上下文演示，来预测未见过任务的动作序列。同时，我们还引入了基于动力学的样本选择策略，通过捕捉跨任务动力学特征来识别相关演示。在AGNOSTOS基准测试中，X-ICM显著提升了跨任务零样本泛化性能，超越了现有领先的VLA模型。我们相信，AGNOSTOS和X-ICM将为推动通用机器人操作的发展提供宝贵的工具支持。

> The generalization capabilities of vision-language-action (VLA) models to unseen tasks are crucial to achieving general-purpose robotic manipulation in open-world settings. However, the cross-task generalization capabilities of existing VLA models remain significantly underexplored. To address this gap, we introduce AGNOSTOS, a novel simulation benchmark designed to rigorously evaluate cross-task zero-shot generalization in manipulation. AGNOSTOS comprises 23 unseen manipulation tasks for testing, distinct from common training task distributions, and incorporates two levels of generalization difficulty to assess robustness. Our systematic evaluation reveals that current VLA models, despite being trained on diverse datasets, struggle to generalize effectively to these unseen tasks. To overcome this limitation, we propose Cross-Task In-Context Manipulation (X-ICM), a method that conditions large language models (LLMs) on in-context demonstrations from seen tasks to predict action sequences for unseen tasks. Additionally, we introduce a dynamics-guided sample selection strategy that identifies relevant demonstrations by capturing cross-task dynamics. On AGNOSTOS, X-ICM significantly improves cross-task zero-shot generalization performance over leading VLAs. We believe AGNOSTOS and X-ICM will serve as valuable tools for advancing general-purpose robotic manipulation.

[Arxiv](https://arxiv.org/abs/2505.15660)
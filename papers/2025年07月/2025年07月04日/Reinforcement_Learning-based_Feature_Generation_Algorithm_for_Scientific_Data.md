# # 强化学习驱动的科学数据特征生成算法研究

发布时间：2025年07月04日

`Agent

这篇论文主要探讨了多智能体特征生成框架，结合强化学习和多智能体系统来优化特征生成过程，因此归类为Agent。` `机器学习` `数据科学`

> Reinforcement Learning-based Feature Generation Algorithm for Scientific Data

# 摘要

> 特征生成（FG）通过构建高阶特征组合并去除冗余特征，旨在提升原始数据的预测能力。它是提高表格型科学数据下游机器学习模型性能的关键预处理步骤。然而，传统方法在处理科学数据的特征生成时面临两大挑战：首先，高阶特征组合的有效构建需要深厚且广泛的领域专业知识；其次，随着特征组合阶数的增加，搜索空间呈指数级扩展，导致人力成本居高不下。

数据-centric人工智能（DCAI）范式的进步为特征生成的自动化带来了新的可能性。本文受到这一启发，重新审视了传统的特征生成工作流程，并提出了多智能体特征生成（MAFG）框架。在迭代探索阶段，多智能体协同构建数学变换方程，合成并识别信息量高的特征组合，并通过强化学习机制优化策略。探索阶段完成后，MAFG整合大型语言模型（LLMs）对每个重要性能突破的生成特征进行解释性评估。

实验结果和案例研究一致表明，MAFG框架能够有效自动化特征生成过程，并显著提升各种下游科学数据挖掘任务的性能。


> Feature generation (FG) aims to enhance the prediction potential of original data by constructing high-order feature combinations and removing redundant features. It is a key preprocessing step for tabular scientific data to improve downstream machine-learning model performance. Traditional methods face the following two challenges when dealing with the feature generation of scientific data: First, the effective construction of high-order feature combinations in scientific data necessitates profound and extensive domain-specific expertise. Secondly, as the order of feature combinations increases, the search space expands exponentially, imposing prohibitive human labor consumption. Advancements in the Data-Centric Artificial Intelligence (DCAI) paradigm have opened novel avenues for automating feature generation processes. Inspired by that, this paper revisits the conventional feature generation workflow and proposes the Multi-agent Feature Generation (MAFG) framework. Specifically, in the iterative exploration stage, multi-agents will construct mathematical transformation equations collaboratively, synthesize and identify feature combinations ex-hibiting high information content, and leverage a reinforcement learning mechanism to evolve their strategies. Upon completing the exploration phase, MAFG integrates the large language models (LLMs) to interpreta-tively evaluate the generated features of each significant model performance breakthrough. Experimental results and case studies consistently demonstrate that the MAFG framework effectively automates the feature generation process and significantly enhances various downstream scientific data mining tasks.

[Arxiv](https://arxiv.org/abs/2507.03498)
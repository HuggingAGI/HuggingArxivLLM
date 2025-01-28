# 利用多智能体强化学习提升检索增强生成效果

发布时间：2025年01月25日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）的优化问题，提出了一种多模块联合优化算法（MMOA-RAG），利用多智能体强化学习来协调各个组件，以提高生成答案的准确性。虽然涉及了多智能体强化学习，但核心内容仍然是围绕RAG的优化和应用展开的，因此应归类为RAG。` `问答系统`

> Improving Retrieval-Augmented Generation through Multi-Agent Reinforcement Learning

# 摘要

> # 摘要
检索增强生成（RAG）通过整合外部最新知识到大型语言模型中，有效减少了幻觉现象。标准RAG流程通常包括查询重写、文档检索、文档过滤和答案生成等组件。然而，这些组件通常通过监督微调单独优化，导致各模块目标与生成准确答案的总体目标不一致。尽管近期研究尝试用强化学习（RL）优化特定RAG组件，但这些方法往往只关注简化的两组件流程，未能充分解决模块间的复杂依赖和协作问题。为此，我们提出将RAG流程视为多智能体协作任务，每个组件作为一个RL智能体。我们提出了MMOA-RAG，一种多模块联合优化算法，利用多智能体强化学习协调各智能体目标，以实现如最终答案F1分数等统一奖励。实验表明，MMOA-RAG在多个QA数据集上提升了整体性能，优于现有基线。此外，消融研究验证了各组件贡献及MMOA-RAG在不同RAG组件和数据集中的适应性。代码详见https://github.com/chenyiqun/MMOA-RAG。

> Retrieval-augmented generation (RAG) is extensively utilized to incorporate external, current knowledge into large language models, thereby minimizing hallucinations. A standard RAG pipeline may comprise several components, such as query rewriting, document retrieval, document filtering, and answer generation. However, these components are typically optimized separately through supervised fine-tuning, which can lead to misalignments between the objectives of individual modules and the overarching aim of generating accurate answers in question-answering (QA) tasks. Although recent efforts have explored reinforcement learning (RL) to optimize specific RAG components, these approaches often focus on overly simplistic pipelines with only two components or do not adequately address the complex interdependencies and collaborative interactions among the modules. To overcome these challenges, we propose treating the RAG pipeline as a multi-agent cooperative task, with each component regarded as an RL agent. Specifically, we present MMOA-RAG, a Multi-Module joint Optimization Algorithm for RAG, which employs multi-agent reinforcement learning to harmonize all agents' goals towards a unified reward, such as the F1 score of the final answer. Experiments conducted on various QA datasets demonstrate that MMOA-RAG improves the overall pipeline performance and outperforms existing baselines. Furthermore, comprehensive ablation studies validate the contributions of individual components and the adaptability of MMOA-RAG across different RAG components and datasets. The code of MMOA-RAG is on https://github.com/chenyiqun/MMOA-RAG.

[Arxiv](https://arxiv.org/abs/2501.15228)
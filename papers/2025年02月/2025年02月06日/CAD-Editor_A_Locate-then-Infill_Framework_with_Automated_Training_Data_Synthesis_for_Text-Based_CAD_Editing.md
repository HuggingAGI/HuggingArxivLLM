# CAD-Editor: 基于定位-填充框架的自动化训练数据合成方法，助力文本驱动的CAD编辑

发布时间：2025年02月06日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）和大型视觉语言模型（LVLMs）来实现基于文本的CAD编辑。虽然涉及到CAD设计，但其核心在于利用LLMs的自然语言理解和CAD知识来完成任务，因此属于LLM应用的范畴。` `计算机辅助设计` `制造业`

> CAD-Editor: A Locate-then-Infill Framework with Automated Training Data Synthesis for Text-Based CAD Editing

# 摘要

> # 计算机辅助设计（CAD）在各行各业中不可或缺。\emph{基于文本的CAD编辑}，即通过文本指令自动修改CAD模型，潜力巨大但尚未充分开发。现有方法多集中于设计变体生成或基于文本的CAD生成，要么缺乏文本控制支持，要么忽视了现有CAD模型的约束。我们推出了\emph{CAD-Editor}，首个基于文本的CAD编辑框架。为解决训练中所需精确对应的三元组数据难题，我们设计了一套自动数据合成流程。该流程利用设计变体模型生成原始与编辑后的CAD模型对，并通过大型视觉语言模型（LVLMs）将其差异转化为编辑指令。针对基于文本的CAD编辑的复杂性，我们提出了“定位-填充”框架，将任务拆分为两个子任务：定位需修改区域并填充适当编辑。大型语言模型（LLMs）作为核心，充分发挥其在自然语言理解和CAD知识上的优势。实验证明，CAD-Editor在定量与定性评估中均表现卓越。

> Computer Aided Design (CAD) is indispensable across various industries. \emph{Text-based CAD editing}, which automates the modification of CAD models based on textual instructions, holds great potential but remains underexplored. Existing methods primarily focus on design variation generation or text-based CAD generation, either lacking support for text-based control or neglecting existing CAD models as constraints. We introduce \emph{CAD-Editor}, the first framework for text-based CAD editing. To address the challenge of demanding triplet data with accurate correspondence for training, we propose an automated data synthesis pipeline. This pipeline utilizes design variation models to generate pairs of original and edited CAD models and employs Large Vision-Language Models (LVLMs) to summarize their differences into editing instructions. To tackle the composite nature of text-based CAD editing, we propose a locate-then-infill framework that decomposes the task into two focused sub-tasks: locating regions requiring modification and infilling these regions with appropriate edits. Large Language Models (LLMs) serve as the backbone for both sub-tasks, leveraging their capabilities in natural language understanding and CAD knowledge. Experiments show that CAD-Editor achieves superior performance both quantitatively and qualitatively.

[Arxiv](https://arxiv.org/abs/2502.03997)
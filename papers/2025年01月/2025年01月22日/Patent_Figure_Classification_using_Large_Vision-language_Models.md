# 基于大型视觉语言模型的专利图分类

发布时间：2025年01月22日

`LLM应用

**理由**：该论文主要探讨了大型视觉语言模型（LVLMs）在专利图分类中的应用，特别是在零-shot和少-shot学习场景下的表现。虽然涉及视觉语言模型，但其核心是应用这些模型来解决具体的专利图分类问题，属于LLM在实际任务中的应用范畴。因此，分类为“LLM应用”是合适的。` `计算机视觉`

> Patent Figure Classification using Large Vision-language Models

# 摘要

> # 专利图分类
专利图分类助力专利检索系统的分面搜索，提升现有技术搜索效率。现有方法仅针对单一或有限概念的专利图分类进行了探索。近年来，大型视觉语言模型（LVLMs）在计算机视觉下游任务中表现卓越，但尚未涉足专利图分类领域。本研究聚焦于零-shot和少-shot学习场景，探索LVLMs在专利图视觉问答（VQA）和分类中的应用。为此，我们推出了PatFigVQA和PatFigCLS数据集，用于专利图类型、投影、专利类别及对象等多方面的微调与评估。为高效处理大量类别，我们创新性地提出了基于多项选择题的锦标赛式分类策略。少-shot设置下，基于LVLMs和卷积神经网络（CNNs）的多种分类方法实验与比较，验证了所提方法的可行性。

> Patent figure classification facilitates faceted search in patent retrieval systems, enabling efficient prior art search. Existing approaches have explored patent figure classification for only a single aspect and for aspects with a limited number of concepts. In recent years, large vision-language models (LVLMs) have shown tremendous performance across numerous computer vision downstream tasks, however, they remain unexplored for patent figure classification. Our work explores the efficacy of LVLMs in patent figure visual question answering (VQA) and classification, focusing on zero-shot and few-shot learning scenarios. For this purpose, we introduce new datasets, PatFigVQA and PatFigCLS, for fine-tuning and evaluation regarding multiple aspects of patent figures~(i.e., type, projection, patent class, and objects). For a computational-effective handling of a large number of classes using LVLM, we propose a novel tournament-style classification strategy that leverages a series of multiple-choice questions. Experimental results and comparisons of multiple classification approaches based on LVLMs and Convolutional Neural Networks (CNNs) in few-shot settings show the feasibility of the proposed approaches.

[Arxiv](https://arxiv.org/abs/2501.12751)
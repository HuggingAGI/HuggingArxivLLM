# 理解通过逻辑达成直接偏好对齐的逻辑

发布时间：2024年12月23日

`LLM理论` `人工智能` `语言模型`

> Understanding the Logic of Direct Preference Alignment through Logic

# 摘要

> 近期，像 DPO 这样的直接偏好对齐算法（DPA）在让大型语言模型契合人类偏好方面展现出极大的潜力。尽管这推动了原始 DPO 损失的众多新变体的开发，然而，鉴于缺乏有关这些算法底层语义的技术和概念框架，要理解这些新提案之间的差异以及开发新的 DPA 损失函数，仍然颇具难度。在本文中，我们试图通过依据离散推理问题将 DPA 损失形式化来解决这一问题。具体而言，我们提出：对于现有的 DPA 损失，我们能否系统性地推导出能表征其语义的符号表达式？两种损失的语义之间存在怎样的关联？我们为基于单模型和参考模型的方法提出了一种用于表征偏好损失的新形式，并确定了许多常用 DPA 变体的符号形式。此外，我们展示了这种偏好学习的形式化观点如何为 DPA 损失的格局在规模和结构上带来新的启发，不仅能够严谨地刻画近期损失提案之间的关系，还能从基本原理出发系统性地探索格局并推导出新的损失函数。我们期望我们的框架和发现能为致力于人类人工智能对齐的工作者提供有益的指导。

> Recent direct preference alignment algorithms (DPA), such as DPO, have shown great promise in aligning large language models to human preferences. While this has motivated the development of many new variants of the original DPO loss, understanding the differences between these recent proposals, as well as developing new DPA loss functions, remains difficult given the lack of a technical and conceptual framework for reasoning about the underlying semantics of these algorithms. In this paper, we attempt to remedy this by formalizing DPA losses in terms of discrete reasoning problems. Specifically, we ask: Given an existing DPA loss, can we systematically derive a symbolic expression that characterizes its semantics? How do the semantics of two losses relate to each other? We propose a novel formalism for characterizing preference losses for single model and reference model based approaches, and identify symbolic forms for a number of commonly used DPA variants. Further, we show how this formal view of preference learning sheds new light on both the size and structure of the DPA loss landscape, making it possible to not only rigorously characterize the relationships between recent loss proposals but also to systematically explore the landscape and derive new loss functions from first principles. We hope our framework and findings will help provide useful guidance to those working on human AI alignment.

[Arxiv](https://arxiv.org/abs/2412.17696)
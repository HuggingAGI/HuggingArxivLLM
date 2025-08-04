# MCeT：基于大型语言模型的行为模型正确性评估

发布时间：2025年08月01日

`LLM应用` `系统工程` `软件工程`

> MCeT: Behavioral Model Correctness Evaluation using Large Language Models

# 摘要

> 行为模型图（如序列图）是系统工程师根据需求文档设计的重要文档形式，通常由人工或借助设计工具完成。随着大型语言模型（LLMs）作为AI建模助手的广泛应用，生成这些图表的过程将引入更多自动化。这推动了对自动模型正确性评估工具的需求。这种工具可用于评估人工和AI自动生成的模型；为系统工程师提供反馈；并使AI助手能够自我评估和自我改进其生成的模型。

    在本文中，我们提出了MCeT，这是首个完全自动化的工具，用于评估行为模型（特别是序列图）与其对应需求文本的正确性，并生成模型存在的问题列表。我们利用LLMs进行正确性评估，因为它们在自然语言理解方面表现出色。然而，我们发现直接要求LLMs将图表与需求进行比较只能发现经验丰富的工程师可以发现的不到35%的问题。为此，我们提出了一种更细致、多角度的补充方法：将图表拆分为不可分割的原子交互，将需求文本拆分为自洽的原子项。我们逐一将图表与原子需求进行对比，并将每个图表原子与需求进行对比。此外，我们还提出了一种结合多角度的自洽性检查方法，以缓解LLMs生成的虚假问题。我们的综合方法在真实需求数据集上将直接方法的精度从0.58提升至0.81。此外，该方法比直接方法多发现了90%经验丰富的工程师发现的问题，并且每个图表平均报告了6个新问题。

> Behavioral model diagrams, e.g., sequence diagrams, are an essential form of documentation that are typically designed by system engineers from requirements documentation, either fully manually or assisted by design tools. With the growing use of Large Language Models (LLM) as AI modeling assistants, more automation will be involved in generating diagrams. This necessitates the advancement of automatic model correctness evaluation tools. Such a tool can be used to evaluate both manually and AI automatically generated models; to provide feedback to system engineers, and enable AI assistants to self-evaluate and self-enhance their generated models.
  In this paper, we propose MCeT, the first fully automated tool to evaluate the correctness of a behavioral model, sequence diagrams in particular, against its corresponding requirements text and produce a list of issues that the model has. We utilize LLMs for the correctness evaluation tasks as they have shown outstanding natural language understanding ability. However, we show that directly asking an LLM to compare a diagram to requirements finds less than 35% of issues that experienced engineers can find. We propose to supplement the direct check with a fine-grained, multi-perspective approach; we split the diagram into atomic, non-divisible interactions, and split the requirements text into atomic, self-contained items. We compare the diagram with atomic requirements and each diagram-atom with the requirements. We also propose a self-consistency checking approach that combines perspectives to mitigate LLM hallucinated issues. Our combined approach improves upon the precision of the direct approach from 0.58 to 0.81 in a dataset of real requirements. Moreover, the approach finds 90% more issues that the experienced engineers found than the direct approach, and reports an average of 6 new issues per diagram.

[Arxiv](https://arxiv.org/abs/2508.00630)
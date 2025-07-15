# 加速自动程序修复：基于大语言模型的双重检索增强微调与补丁生成

发布时间：2025年07月14日

`LLM应用` `软件工程`

> Accelerating Automatic Program Repair with Dual Retrieval-Augmented Fine-Tuning and Patch Generation on Large Language Models

# 摘要

> 自动化程序修复（APR）在保障软件可靠性和质量的同时，还能提升效率并减轻开发人员的工作负担。尽管基于规则和学习的APR方法已展现其有效性，但它们的性能受限于修复缺陷类型、训练数据质量和模型规模。近年来，大型语言模型（LLMs）与检索增强生成（RAG）的结合在APR任务中得到广泛应用。然而，现有代码LLMs和RAG设计未能完全解决代码修复任务，也未充分考虑代码特性。为此，我们提出SelRepair，一种将微调LLM与新型双RAG模块结合的新型APR方法。该方法利用错误修复配对数据集进行微调，并通过RAG选择门引入语义和句法/结构相似性信息。这种设计确保高效检索相关信息，从而缩短token长度并减少推理时间。在Java数据集上的评估显示，SelRepair超越其他APR方法，在不同数据集上分别以26.29%和17.64%的精确匹配（EM）成绩领先，同时在控制输入长度的情况下，推理时间减少至少6.42%。

> Automated Program Repair (APR) is essential for ensuring software reliability and quality while enhancing efficiency and reducing developers' workload. Although rule-based and learning-based APR methods have demonstrated their effectiveness, their performance was constrained by the defect type of repair, the quality of training data, and the size of model parameters. Recently, Large Language Models (LLMs) combined with Retrieval-Augmented-Generation (RAG) have been increasingly adopted in APR tasks. However, current code LLMs and RAG designs neither fully address code repair tasks nor consider code-specific features. To overcome these limitations, we propose SelRepair, a novel APR approach with integration of a fine-tuned LLM with a newly-designed dual RAG module. This approach uses a bug-fix pair dataset for fine-tuning and incorporates semantic and syntactic/structural similarity information through an RAG selection gate. This design ensures relevant information is retrieved efficiently, thereby reducing token length and inference time. Evaluations on Java datasets show SelRepair outperforms other APR methods, achieving 26.29% and 17.64% in terms of exact match (EM) on different datasets while reducing inference time by at least 6.42% with controlled input lengths.

[Arxiv](https://arxiv.org/abs/2507.10103)
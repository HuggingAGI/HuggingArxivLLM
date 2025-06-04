# Cell-o1：训练大型语言模型，借助强化学习解决单细胞推理难题

发布时间：2025年06月03日

`LLM应用

理由：这篇论文探讨了如何利用大型语言模型（LLM）来解决细胞类型注释问题，展示了LLM在生物医学领域的实际应用。作者提出了一个新的任务和模型，并在特定的基准测试中验证了其有效性，属于LLM的实际应用范畴。` `生物医学` `单细胞测序`

> Cell-o1: Training LLMs to Solve Single-Cell Reasoning Puzzles with Reinforcement Learning

# 摘要

> 细胞类型注释是分析单细胞RNA测序数据异质性的关键任务。尽管基模型已实现自动化，但它们独立注释细胞，不考虑批量级别上下文或提供解释。人类专家则基于专业知识为不同细胞群分配类型。为模拟这一过程，我们提出CellPuzzles任务，目标是为一批细胞分配唯一类型。该基准涵盖多种组织、疾病和供体，需跨批量上下文推理以确保唯一性。现有LLMs在CellPuzzles上表现不佳，最佳基线o1仅19%准确率。为此，我们提出Cell-o1，一个70亿参数LLM，通过监督微调和强化学习训练，性能提升73%，泛化良好。分析显示其具备类似专家推理能力。代码和数据在GitHub上可获取。

> Cell type annotation is a key task in analyzing the heterogeneity of single-cell RNA sequencing data. Although recent foundation models automate this process, they typically annotate cells independently, without considering batch-level cellular context or providing explanatory reasoning. In contrast, human experts often annotate distinct cell types for different cell clusters based on their domain knowledge. To mimic this workflow, we introduce the CellPuzzles task, where the objective is to assign unique cell types to a batch of cells. This benchmark spans diverse tissues, diseases, and donor conditions, and requires reasoning across the batch-level cellular context to ensure label uniqueness. We find that off-the-shelf large language models (LLMs) struggle on CellPuzzles, with the best baseline (OpenAI's o1) achieving only 19.0% batch-level accuracy. To fill this gap, we propose Cell-o1, a 7B LLM trained via supervised fine-tuning on distilled reasoning traces, followed by reinforcement learning with batch-level rewards. Cell-o1 achieves state-of-the-art performance, outperforming o1 by over 73% and generalizing well across contexts. Further analysis of training dynamics and reasoning behaviors provides insights into batch-level annotation performance and emergent expert-like reasoning. Code and data are available at https://github.com/ncbi-nlp/cell-o1.

[Arxiv](https://arxiv.org/abs/2506.02911)
# 基于大型语言模型与优先深度优先搜索的本体匹配

发布时间：2025年01月20日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来改进本体匹配（OM）任务，特别是通过“检索-提示”管道和优先深度优先搜索（PDFS）策略来优化性能。虽然涉及到一些检索和嵌入的技术，但核心关注点是如何应用LLMs来解决具体的实际问题（即本体匹配），并且论文的重点在于如何通过LLMs的应用来提高任务的准确性和效率。因此，这篇论文应归类为“LLM应用”。` `生物医学` `数据互操作性`

> Ontology Matching with Large Language Models and Prioritized Depth-First Search

# 摘要

> # 摘要
本体匹配（OM）在数据互操作性和知识共享中扮演着关键角色，但由于需要大量训练数据且机器学习方法在词汇处理上存在局限，OM仍面临挑战。近年来，基于大型语言模型（LLMs）的方法在OM中展现出巨大潜力，尤其是通过“检索-提示”管道。该方法首先检索相关目标实体，随后利用它们提示LLM预测最终匹配。尽管潜力巨大，这些系统仍存在性能有限和计算开销高的问题。为解决这些问题，我们提出了MILA，一种将“检索-识别-提示”管道嵌入优先深度优先搜索（PDFS）策略的新方法。该方法高效识别大量语义对应关系，准确率高，且仅在最边缘情况下调用LLM。我们通过2023年和2024年本体对齐评估倡议中的生物医学挑战对MILA进行了评估。结果显示，MILA在五个无监督任务中的四个中取得了最高的F-Measure，比现有OM系统高出17%，表现优于或与领先的有监督OM系统相当。此外，MILA展现了任务无关的稳定性，显著减少了LLM调用。这些结果表明，高性能的基于LLM的OM可以通过编程（PDFS）、学习（嵌入向量）和提示启发式方法的结合实现，无需依赖领域特定的启发式方法或微调。

> Ontology matching (OM) plays a key role in enabling data interoperability and knowledge sharing, but it remains challenging due to the need for large training datasets and limited vocabulary processing in machine learning approaches. Recently, methods based on Large Language Model (LLMs) have shown great promise in OM, particularly through the use of a retrieve-then-prompt pipeline. In this approach, relevant target entities are first retrieved and then used to prompt the LLM to predict the final matches. Despite their potential, these systems still present limited performance and high computational overhead. To address these issues, we introduce MILA, a novel approach that embeds a retrieve-identify-prompt pipeline within a prioritized depth-first search (PDFS) strategy. This approach efficiently identifies a large number of semantic correspondences with high accuracy, limiting LLM requests to only the most borderline cases. We evaluated MILA using the biomedical challenge proposed in the 2023 and 2024 editions of the Ontology Alignment Evaluation Initiative. Our method achieved the highest F-Measure in four of the five unsupervised tasks, outperforming state-of-the-art OM systems by up to 17%. It also performed better than or comparable to the leading supervised OM systems. MILA further exhibited task-agnostic performance, remaining stable across all tasks and settings, while significantly reducing LLM requests. These findings highlight that high-performance LLM-based OM can be achieved through a combination of programmed (PDFS), learned (embedding vectors), and prompting-based heuristics, without the need of domain-specific heuristics or fine-tuning.

[Arxiv](https://arxiv.org/abs/2501.11441)
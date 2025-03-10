# RocketEval：基于评分清单的高效LLM自动化评估方案

发布时间：2025年03月06日

`LLM应用

摘要主要讨论了如何利用轻量级大型语言模型（LLM）作为评估者，提出了一种自动化评估方法RocketEval。该方法旨在解决传统评估方法的高成本、隐私与安全担忧以及可重复性问题。论文通过重新定义评估任务和引入基于检查列表的评分流程，展示了轻量级LLM在评估任务中的应用效果，并提供了显著的成本节约。这些内容属于LLM的实际应用和评估方法的改进，因此归类为“LLM应用”。` `人工智能`

> RocketEval: Efficient Automated LLM Evaluation via Grading Checklist

# 摘要

> # 摘要
在多样且具有挑战性的场景中评估大型语言模型（LLMs）对于使其与人类偏好保持一致至关重要。为了缓解高昂的人工评估成本，利用强大的LLM作为评估者已成为一种受欢迎的方法。然而，这种方法仍然面临诸多挑战，包括高昂的成本、隐私与安全担忧以及可重复性问题。

本文中，我们提出了一种名为RocketEval的简单、可重复且精确的自动化评估方法，通过采用轻量级LLM作为评估者。首先，我们发现轻量级和强大LLM在评估任务中的性能差异主要源于它们进行综合性分析的能力，而这种能力难以通过链式推理等技术得到显著提升。

通过将评估任务重新定义为基于实例特定检查列表的多维度问答，我们证明了轻量级LLM评估准确性有限的主要原因在于高度的不确定性以及位置偏见。为了解决这些挑战，我们引入了一种基于检查列表评分的自动化评估流程，该流程旨在适应各种场景和问题。这一流程包括创建检查列表、利用轻量级LLM对检查列表进行评分，以及重新调整检查列表项的权重以匹配监督标注。

我们在自动化评估基准数据集MT-Bench和WildBench上的实验表明，当使用Gemma-2-2B作为评估者时，RocketEval与人类偏好达到了高度相关性（0.965），与GPT-4相当。此外，RocketEval在大规模评估和比较场景中提供了超过50倍的成本节约。我们的代码可在https://github.com/Joinn99/RocketEval-ICLR获取。

> Evaluating large language models (LLMs) in diverse and challenging scenarios is essential to align them with human preferences. To mitigate the prohibitive costs associated with human evaluations, utilizing a powerful LLM as a judge has emerged as a favored approach. Nevertheless, this methodology encounters several challenges, including substantial expenses, concerns regarding privacy and security, and reproducibility. In this paper, we propose a straightforward, replicable, and accurate automated evaluation method by leveraging a lightweight LLM as the judge, named RocketEval. Initially, we identify that the performance disparity between lightweight and powerful LLMs in evaluation tasks primarily stems from their ability to conduct comprehensive analyses, which is not easily enhanced through techniques such as chain-of-thought reasoning. By reframing the evaluation task as a multi-faceted Q&A using an instance-specific checklist, we demonstrate that the limited judgment accuracy of lightweight LLMs is largely attributes to high uncertainty and positional bias. To address these challenges, we introduce an automated evaluation process grounded in checklist grading, which is designed to accommodate a variety of scenarios and questions. This process encompasses the creation of checklists, the grading of these checklists by lightweight LLMs, and the reweighting of checklist items to align with the supervised annotations. Our experiments carried out on the automated evaluation benchmarks, MT-Bench and WildBench datasets, reveal that RocketEval, when using Gemma-2-2B as the judge, achieves a high correlation (0.965) with human preferences, which is comparable to GPT-4o. Moreover, RocketEval provides a cost reduction exceeding 50-fold for large-scale evaluation and comparison scenarios. Our code is available at https://github.com/Joinn99/RocketEval-ICLR .

[Arxiv](https://arxiv.org/abs/2503.05142)
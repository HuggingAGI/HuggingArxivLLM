# SC4ANM: 发现学术论文自动新颖性预测的最优章节组合方案

发布时间：2025年05月22日

`LLM应用

摘要分析：这篇论文主要探讨了如何利用语言模型（LLMs）来评估学术论文的创新性。研究者通过分析论文的不同章节（如引言、方法、结果和讨论）的组合，利用LLMs进行创新性评分预测。虽然论文涉及自然语言处理技术，但其核心在于应用语言模型来解决特定问题，因此归类为LLM应用。` `学术研究`

> SC4ANM: Identifying Optimal Section Combinations for Automated Novelty Prediction in Academic Papers

# 摘要

> 创新性是学术论文的灵魂，对其评估也有多种解读方式。现有的方法通常聚焦于词汇或实体的组合，但这种思路提供的见解有限。论文中的创新性相关内容往往散落在引言、方法论和结果等不同核心部分。因此，探索评估论文创新性的最优章节组合对于推动自动化创新性评估具有重要意义。本文通过将学术论文的不同章节组合作为输入，驱动语言模型进行创新性评分预测。随后，我们深入分析结果，以确定最适合预测创新性得分的章节组合。首先，我们运用自然语言处理技术识别学术论文的章节结构，将其分为引言、方法、结果和讨论（IMRaD）。接着，我们选取这些章节的不同组合（例如引言和方法）作为预训练语言模型（PLMs）和大型语言模型（LLMs）的输入，采用人类专家评审提供的创新性评分作为真实标签，从而获得预测结果。研究发现，使用引言、结果和讨论部分最适合评估论文的创新性，而使用整篇文本并未带来显著效果。此外，基于PLMs和LLMs的结果，引言和结果部分似乎是创新性评分预测任务中最重要的章节。本文的代码和数据集可在https://github.com/njust-winchy/SC4ANM获取。

> Novelty is a core component of academic papers, and there are multiple perspectives on the assessment of novelty. Existing methods often focus on word or entity combinations, which provide limited insights. The content related to a paper's novelty is typically distributed across different core sections, e.g., Introduction, Methodology and Results. Therefore, exploring the optimal combination of sections for evaluating the novelty of a paper is important for advancing automated novelty assessment. In this paper, we utilize different combinations of sections from academic papers as inputs to drive language models to predict novelty scores. We then analyze the results to determine the optimal section combinations for novelty score prediction. We first employ natural language processing techniques to identify the sectional structure of academic papers, categorizing them into introduction, methods, results, and discussion (IMRaD). Subsequently, we used different combinations of these sections (e.g., introduction and methods) as inputs for pretrained language models (PLMs) and large language models (LLMs), employing novelty scores provided by human expert reviewers as ground truth labels to obtain prediction results. The results indicate that using introduction, results and discussion is most appropriate for assessing the novelty of a paper, while the use of the entire text does not yield significant results. Furthermore, based on the results of the PLMs and LLMs, the introduction and results appear to be the most important section for the task of novelty score prediction. The code and dataset for this paper can be accessed at https://github.com/njust-winchy/SC4ANM.

[Arxiv](https://arxiv.org/abs/2505.16330)
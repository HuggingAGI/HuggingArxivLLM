# 借助大型语言模型实现高效代码审查

发布时间：2025年02月05日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来优化代码审查数据集的质量，并评估其对自动化评论生成和代码改进任务的影响。虽然论文涉及数据集的整理和评估，但其核心应用场景是使用LLM来提升代码审查的自动化水平，因此应归类为“LLM应用”。` `软件开发` `代码审查`

> Harnessing Large Language Models for Curated Code Reviews

# 摘要

> 在代码审查中，生成结构清晰且相关的评论对于识别代码问题和推动准确的代码修改至关重要，从而确保高效的审查流程。精心设计的评论不仅能简化审查过程，还对后续任务（如代码改进）大有裨益，这些任务需要根据审查评论对代码进行调整。尽管已有多种基于AI的方法尝试自动化评论生成，但其效果仍受限于训练数据的质量。现有的代码审查数据集往往存在噪声且未经优化，限制了AI模型的学习潜力，阻碍了自动化进程。
    为应对这些挑战，我们提出了一套整理流程，旨在提升最大公开代码审查数据集的质量。我们首先构建了一个评估框架，结合特定标准和类别，对数据集的初始质量进行实证研究。随后，我们采用基于大型语言模型（LLM）的方法，应用整理流程对数据集进行优化。基于同一评估框架，我们对新整理的数据集进行了对比分析，结果显示评论的清晰度和简洁性显著提升。此外，我们还评估了整理数据集对自动化下游任务（特别是评论生成和代码改进）的影响。研究发现，整理后的数据集显著提升了模型生成评论的准确性，且这些评论在代码改进中也更具实用性。

> In code review, generating structured and relevant comments is crucial for identifying code issues and facilitating accurate code changes that ensure an efficient code review process. Well-crafted comments not only streamline the code review itself but are also essential for subsequent tasks like code refinement, where the code is modified to satisfy the input review comment. Although various AI-based approaches aimed to automate comment generation, their effectiveness remains limited by the quality of the training data. Existing code review datasets are often noisy and unrefined, posing limitations to the learning potential of AI models and hindering the automation process.
  To address these challenges, we propose a curation pipeline designed to enhance the quality of the largest publicly available code review dataset. We begin by establishing an evaluation framework, incorporating specific criteria and categories to empirically study the initial quality of the dataset. Using a large language model (LLM)-driven approach, we then apply our curation pipeline to refine the dataset. A comparative analysis of the newly curated dataset, based on the same evaluation framework, demonstrates substantial improvements in the clarity and conciseness of the comments. Additionally, we assess the impact of the curated dataset on automating downstream tasks, specifically comment generation and code refinement. Our findings show that the curated dataset leads to enhanced model performance in generating more accurate comments. Curated comments are also more useful as they lead to more accurate code refinement.

[Arxiv](https://arxiv.org/abs/2502.03425)
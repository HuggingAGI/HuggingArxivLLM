# TablePilot：基于大型语言模型，推荐更符合人类偏好的表格数据分析

发布时间：2025年03月17日

`LLM应用` `数据科学` `数据分析`

> TablePilot; Recommending Human-Preferred Tabular Data Analysis with Large Language Models

# 摘要

> 在众多场景中，表格数据分析至关重要。然而，如何高效地识别新表格中最相关的数据分析查询和结果仍是一个重大挑战。面对表格数据的复杂性、多样的分析操作以及对高质量分析的需求，这一过程显得尤为繁琐。为解决这些问题，我们致力于为表格数据分析工作流推荐针对新表格的查询-代码-结果三元组。本文中，我们介绍了TablePilot——一个开创性的表格数据分析框架。该框架利用大型语言模型，无需依赖用户画像或历史交互记录，即可自主生成全面且优质的分析结果。通过在分析准备和分析优化中的关键设计，TablePilot显著提升了准确性。此外，我们提出了Rec-Align——一种新颖的方法，旨在进一步提升推荐质量，并更好地与人类偏好相契合。在专门用于全面表格数据分析推荐的DART数据集上的实验，验证了我们框架的有效性。基于GPT-4o的调优版本，TablePilot在top-5推荐召回率上达到了77.0%。通过人类评估，我们进一步凸显了其在优化表格数据分析工作流方面的有效性。

> Tabular data analysis is crucial in many scenarios, yet efficiently identifying the most relevant data analysis queries and results for a new table remains a significant challenge. The complexity of tabular data, diverse analytical operations, and the demand for high-quality analysis make the process tedious. To address these challenges, we aim to recommend query-code-result triplets tailored for new tables in tabular data analysis workflows. In this paper, we present TablePilot, a pioneering tabular data analysis framework leveraging large language models to autonomously generate comprehensive and superior analytical results without relying on user profiles or prior interactions. The framework incorporates key designs in analysis preparation and analysis optimization to enhance accuracy. Additionally, we propose Rec-Align, a novel method to further improve recommendation quality and better align with human preferences. Experiments on DART, a dataset specifically designed for comprehensive tabular data analysis recommendation, demonstrate the effectiveness of our framework. Based on GPT-4o, the tuned TablePilot achieves 77.0% top-5 recommendation recall. Human evaluations further highlight its effectiveness in optimizing tabular data analysis workflows.

[Arxiv](https://arxiv.org/abs/2503.13262)
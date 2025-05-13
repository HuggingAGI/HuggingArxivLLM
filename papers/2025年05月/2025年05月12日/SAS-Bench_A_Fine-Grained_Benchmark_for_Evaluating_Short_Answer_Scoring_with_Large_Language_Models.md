# SAS-Bench：评估大模型短答案评分的精细基准测试

发布时间：2025年05月12日

`LLM应用` `评估系统`

> SAS-Bench: A Fine-Grained Benchmark for Evaluating Short Answer Scoring with Large Language Models

# 摘要

> 主观答案评分（SAG）在教育、标准化考试和自动化评估系统中扮演着关键角色，特别是在简答评分（SAS）任务中对短篇回答的评估。然而，现有方法通常评分较为粗放，且缺乏详细的推理过程。尽管大型语言模型（LLMs）已展现出作为零-shot 评估器的潜力，但它们仍然容易受到偏见的影响，与人类判断存在不一致，并且在评分决策中缺乏透明度。为了解决这些问题，我们推出了SAS-Bench——一个专为基于LLM的SAS任务设计的基准。SAS-Bench提供细粒度的逐步评分、专家标注的错误类别，以及从真实世界学科考试中衍生出的多样化问题类型。该基准能够深入评估模型的推理过程和可解释性。我们还开源了一个包含1,030个问题和4,109个学生回答的数据集，每个回答均由领域专家标注。此外，我们对多种LLMs进行了全面实验，发现了在评分科学相关问题方面的重大挑战，并证明了Few-shot提示在提升评分准确性方面的有效性。这项研究为构建更强大、公平且教育意义深远的基于LLM的评估系统提供了重要参考。


> Subjective Answer Grading (SAG) plays a crucial role in education, standardized testing, and automated assessment systems, particularly for evaluating short-form responses in Short Answer Scoring (SAS). However, existing approaches often produce coarse-grained scores and lack detailed reasoning. Although large language models (LLMs) have demonstrated potential as zero-shot evaluators, they remain susceptible to bias, inconsistencies with human judgment, and limited transparency in scoring decisions. To overcome these limitations, we introduce SAS-Bench, a benchmark specifically designed for LLM-based SAS tasks. SAS-Bench provides fine-grained, step-wise scoring, expert-annotated error categories, and a diverse range of question types derived from real-world subject-specific exams. This benchmark facilitates detailed evaluation of model reasoning processes and explainability. We also release an open-source dataset containing 1,030 questions and 4,109 student responses, each annotated by domain experts. Furthermore, we conduct comprehensive experiments with various LLMs, identifying major challenges in scoring science-related questions and highlighting the effectiveness of few-shot prompting in improving scoring accuracy. Our work offers valuable insights into the development of more robust, fair, and educationally meaningful LLM-based evaluation systems.

[Arxiv](https://arxiv.org/abs/2505.07247)
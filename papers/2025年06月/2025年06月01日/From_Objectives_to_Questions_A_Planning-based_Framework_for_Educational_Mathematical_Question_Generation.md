# 基于规划的教育数学问题生成框架：从目标到问题的转变

发布时间：2025年06月01日

`LLM应用` `教育技术` `数学教育`

> From Objectives to Questions: A Planning-based Framework for Educational Mathematical Question Generation

# 摘要

> 在基于NLP的教育技术中，自动生成符合教育目标的高质量数学问题是一项关键任务。然而，传统生成方法仅关注文本质量，忽视了教育目标，并且只能处理单一维度的简单问题生成，无法满足复杂多面的教育需求。为了解决这些问题，我们构建了包含1.6万个具有多维教育目标的数学问题数据集EduMath，并开发了EQGEVAL评估工具，该工具包含三个评估维度，用于评估模型生成教育问题的能力。受教师设计问题过程的启发，我们提出了基于“规划-评估-优化”方法的教育数学问题生成方法—— Educational Question Planning with self-Reflection (EQPR)。该方法通过结合基于蒙特卡洛树搜索的规划算法与大型语言模型的生成能力，利用迭代反馈不断优化问题。这种自我优化机制确保生成的问题既符合教育背景，又能战略性地实现特定的基本教育目标。通过基于EQGEVAL的广泛实验，我们证明了EQPR在生成符合多维教育目标的问题方面取得了显著改进。

> Automatically generating high-quality mathematical problems that align with educational objectives is a crucial task in NLP-based educational technology. Traditional generation methods focus primarily on textual quality, but they often overlook educational objectives. Moreover, these methods address only single-dimensional, simple question generation, failing to meet complex, multifaceted educational requirements. To address these challenges, we constructed and annotated EduMath, a dataset of 16k mathematical questions with multi-dimensional educational objectives. Based on this dataset, we developed EQGEVAL, which incorporates three evaluation dimensions and is designed to assess the ability of models to generate educational questions. Drawing inspiration from teachers' problem design processes, we propose the Educational Question Planning with self-Reflection (EQPR) method for educational mathematical question generation, following a "plan-evaluate-optimize" approach. Specifically, by combining planning algorithm based on Monte Carlo Tree Search with the generative capabilities of Large Language Models, we continuously optimize questions through iterative feedback. This self-optimization mechanism ensures that the generated questions both fit the educational context and strategically achieve specific basic educational objectives. Through extensive experiments based on EQGEVAL, we have demonstrated that EQPR achieves significant improvements in generating questions that meet multi-dimensional educational objectives.

[Arxiv](https://arxiv.org/abs/2506.00963)
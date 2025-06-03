# 从目标到问题：基于规划的教育数学题目生成框架

发布时间：2025年06月01日

`LLM应用` `教育技术`

> From Objectives to Questions: A Planning-based Framework for Educational Mathematical Question Generation

# 摘要

> 在基于自然语言处理的教育技术领域，自动生成与教育目标相契合的高质量数学问题是一项关键任务。传统生成方法虽然主要关注文本质量，却往往忽视教育目标的实现。此外，这些方法仅限于处理单一维度的简单问题生成，无法满足复杂、多维度的教育需求。为解决这些问题，我们构建并标注了EduMath数据集，包含16,000道具有多维度教育目标的数学问题。基于该数据集，我们开发了EQGEVAL评估框架，它包含三个评估维度，旨在全面衡量模型生成教育问题的能力。受教师设计问题过程的启发，我们提出了教育问题规划与自省（EQPR）方法，用于教育数学问题生成，采用"规划-评估-优化"的迭代流程。具体而言，我们通过将基于蒙特卡洛树搜索的规划算法与大型语言模型的生成能力相结合，利用迭代反馈持续优化问题。这种自我优化机制确保生成的问题既符合教育背景，又能有效实现特定的基础教育目标。通过基于EQGEVAL的大量实验，我们证明了EQPR在生成符合多维度教育目标的问题方面取得了显著改进。

> Automatically generating high-quality mathematical problems that align with educational objectives is a crucial task in NLP-based educational technology. Traditional generation methods focus primarily on textual quality, but they often overlook educational objectives. Moreover, these methods address only single-dimensional, simple question generation, failing to meet complex, multifaceted educational requirements. To address these challenges, we constructed and annotated EduMath, a dataset of 16k mathematical questions with multi-dimensional educational objectives. Based on this dataset, we developed EQGEVAL, which incorporates three evaluation dimensions and is designed to assess the ability of models to generate educational questions. Drawing inspiration from teachers' problem design processes, we propose the Educational Question Planning with self-Reflection (EQPR) method for educational mathematical question generation, following a "plan-evaluate-optimize" approach. Specifically, by combining planning algorithm based on Monte Carlo Tree Search with the generative capabilities of Large Language Models, we continuously optimize questions through iterative feedback. This self-optimization mechanism ensures that the generated questions both fit the educational context and strategically achieve specific basic educational objectives. Through extensive experiments based on EQGEVAL, we have demonstrated that EQPR achieves significant improvements in generating questions that meet multi-dimensional educational objectives.

[Arxiv](https://arxiv.org/abs/2506.00963)
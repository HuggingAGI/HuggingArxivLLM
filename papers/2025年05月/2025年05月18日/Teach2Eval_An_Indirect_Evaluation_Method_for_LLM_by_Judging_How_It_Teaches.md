# # Teach2Eval：一种通过评估LLM的教学能力来实现间接评估的方法

发布时间：2025年05月18日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的评估方法，提出了一个新的评估框架Teach2Eval。它主要关注模型能力的评估和衡量，属于模型性能和能力的理论研究，因此归类为LLM理论。` `人工智能` `评估方法`

> Teach2Eval: An Indirect Evaluation Method for LLM by Judging How It Teaches

# 摘要

> 近期，大型语言模型（LLMs）的进步速度已超过有效评估方法的发展。传统评估基准依赖任务特定指标和静态数据集，常面临公平性、扩展性和数据污染问题。本文提出Teach2Eval，一个受费曼技巧启发的间接评估框架。不同于直接测试LLMs在预定义任务上的表现，Teach2Eval通过评估模型能否教授较弱的学生模型有效完成任务，来衡量其综合能力。通过将开放性任务转化为教师生成反馈的标准多项选择题（MCQs），Teach2Eval实现了可扩展、自动化和多维度的评估。此方法不仅避免了数据泄露和记忆问题，还捕捉到了与现有基准正交的广泛认知能力。在26个领先LLMs上的实验结果与现有基于人类和模型的动态排名高度一致，同时为训练指导提供了额外的可解释性。

> Recent progress in large language models (LLMs) has outpaced the development of effective evaluation methods. Traditional benchmarks rely on task-specific metrics and static datasets, which often suffer from fairness issues, limited scalability, and contamination risks. In this paper, we introduce Teach2Eval, an indirect evaluation framework inspired by the Feynman Technique. Instead of directly testing LLMs on predefined tasks, our method evaluates a model's multiple abilities to teach weaker student models to perform tasks effectively. By converting open-ended tasks into standardized multiple-choice questions (MCQs) through teacher-generated feedback, Teach2Eval enables scalable, automated, and multi-dimensional assessment. Our approach not only avoids data leakage and memorization but also captures a broad range of cognitive abilities that are orthogonal to current benchmarks. Experimental results across 26 leading LLMs show strong alignment with existing human and model-based dynamic rankings, while offering additional interpretability for training guidance.

[Arxiv](https://arxiv.org/abs/2505.12259)
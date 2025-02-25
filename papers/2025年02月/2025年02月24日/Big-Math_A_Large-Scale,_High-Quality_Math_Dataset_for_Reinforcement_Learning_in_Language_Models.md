# # Big-Math：面向语言模型强化学习的高质量大规模数学数据集

发布时间：2025年02月24日

`LLM应用` `数学推理` `数据集`

> Big-Math: A Large-Scale, High-Quality Math Dataset for Reinforcement Learning in Language Models

# 摘要

> 数学推理模型的热度持续攀升，但现有的数学数据集往往面临质量与数量难以兼得的困境。为解决这一问题，我们推出了Big-Math，一个专为强化学习打造的高质量数学题库，包含超过25万道可验证答案的数学题。我们通过严格筛选和人工验证，确保每道题目都符合三个核心标准：(1) 解答唯一且可验证，(2) 问题具有开放性，(3) 具有闭合形式解。此外，我们通过系统性重构算法，将47,000道封闭式问题转化为开放性问题，形成Big-Math-Reformulated。与GSM8k和MATH等常用数据集相比，Big-Math不仅规模大了一个数量级，而且在问题多样性和难度覆盖上表现更为出色，为不同能力和训练需求的模型提供了丰富且高质量的训练材料。通过填补数据质量与数量的鸿沟，Big-Math为提升大型语言模型的推理能力奠定了坚实基础。

> Increasing interest in reasoning models has led math to become a prominent testing ground for algorithmic and methodological improvements. However, existing open math datasets either contain a small collection of high-quality, human-written problems or a large corpus of machine-generated problems of uncertain quality, forcing researchers to choose between quality and quantity. In this work, we present Big-Math, a dataset of over 250,000 high-quality math questions with verifiable answers, purposefully made for reinforcement learning (RL). To create Big-Math, we rigorously filter, clean, and curate openly available datasets, extracting questions that satisfy our three desiderata: (1) problems with uniquely verifiable solutions, (2) problems that are open-ended, (3) and problems with a closed-form solution. To ensure the quality of Big-Math, we manually verify each step in our filtering process. Based on the findings from our filtering process, we introduce 47,000 new questions with verified answers, Big-Math-Reformulated: closed-ended questions (i.e. multiple choice questions) that have been reformulated as open-ended questions through a systematic reformulation algorithm. Compared to the most commonly used existing open-source datasets for math reasoning, GSM8k and MATH, Big-Math is an order of magnitude larger, while our rigorous filtering ensures that we maintain the questions most suitable for RL. We also provide a rigorous analysis of the dataset, finding that Big-Math contains a high degree of diversity across problem domains, and incorporates a wide range of problem difficulties, enabling a wide range of downstream uses for models of varying capabilities and training requirements. By bridging the gap between data quality and quantity, Big-Math establish a robust foundation for advancing reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2502.17387)
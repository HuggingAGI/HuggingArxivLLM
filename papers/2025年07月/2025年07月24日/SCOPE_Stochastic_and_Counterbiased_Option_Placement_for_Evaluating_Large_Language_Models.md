# SCOPE：基于随机与反向偏差选项放置的大型语言模型评估方法

发布时间：2025年07月24日

`LLM应用`

> SCOPE: Stochastic and Counterbiased Option Placement for Evaluating Large Language Models

# 摘要

> 大型语言模型（LLMs）在多选题中可能因为选项位置或标签的固有偏见而获得虚高的分数，而不是真正理解问题。本文介绍了一种名为SCOPE的评估框架，旨在以数据集无关的方式测量和缓解这种选择偏见。通过反复调用缺乏语义内容的空提示，SCOPE估计每个模型独特的位置偏见分布。然后根据反向偏见分布重新分配答案位置，从而平衡“运气率”，即随机选择正确答案的概率。此外，它还防止语义相近的干扰项与答案相邻，从而阻止基于浅层接近线索的近失猜测。在多次基准实验中，SCOPE在稳定性能提升方面始终优于现有去偏方法，并且在正确选项上显示出更清晰的信心分布。因此，该框架为提高LLM评估的公平性和可靠性提供了一种新标准。

> Large Language Models (LLMs) can achieve inflated scores on multiple-choice tasks by exploiting inherent biases in option positions or labels, rather than demonstrating genuine understanding. This study introduces SCOPE, an evaluation framework designed to measure and mitigate such selection bias in a dataset-independent manner. By repeatedly invoking a null prompt that lacks semantic content, SCOPE estimates each model's unique position-bias distribution. It then redistributes the answer slot according to the inverse-bias distribution, thereby equalizing the lucky-rate, the probability of selecting the correct answer by chance. Furthermore, it prevents semantically similar distractors from being placed adjacent to the answer, thereby blocking near-miss guesses based on superficial proximity cues. Across multiple benchmark experiments, SCOPE consistently outperformed existing debiasing methods in terms of stable performance improvements and showed clearer confidence distributions over correct options. This framework thus offers a new standard for enhancing the fairness and reliability of LLM evaluations.

[Arxiv](https://arxiv.org/abs/2507.18182)
# 大型语言模型的力量之源：定律法则的奥秘

发布时间：2025年02月24日

`LLM理论`

> How Do Large Language Monkeys Get Their Power (Laws)?

# 摘要

> 近期研究在数学问题解决、证明辅助编程和多模态越狱领域发现了一个引人注目的现象：当（多模态）语言模型对一系列任务进行多次尝试（只要有一次成功即算完成）时，平均成功率的负对数与尝试次数呈现幂律关系。然而，一个简单的数学计算表明，每个问题的失败率应随尝试次数呈指数级下降。我们通过实证验证了这一预测，进而提出一个有趣的问题：整体幂律关系从何而来？

我们发现，如果单次尝试的成功概率分布具有重尾特性（即一小部分任务的成功概率极低），那么每个问题的成功概率呈指数级增长，但整体成功率趋势会被这些任务拉低为幂律关系。即使每个问题本身的成功率呈指数级增长，这种分布特性仍会导致整体成功率呈现幂律关系。这一发现揭示了成功概率分布对整体趋势的深远影响。

我们进一步证明，这种分布视角可以解释之前观察到的偏离幂律关系的现象，并提供了一种相对误差降低一个数量级（或等效地，推理计算量减少约2-4个数量级）的简单方法来预测幂律指数。总体而言，我们的研究有助于更好地理解神经语言模型性能如何随着推理计算量的增加而提升，以及如何为（多模态）语言模型开发可预测的扩展评估方法。

> Recent research across mathematical problem solving, proof assistant programming and multimodal jailbreaking documents a striking finding: when (multimodal) language model tackle a suite of tasks with multiple attempts per task -- succeeding if any attempt is correct -- then the negative log of the average success rate scales a power law in the number of attempts. In this work, we identify an apparent puzzle: a simple mathematical calculation predicts that on each problem, the failure rate should fall exponentially with the number of attempts. We confirm this prediction empirically, raising a question: from where does aggregate polynomial scaling emerge? We then answer this question by demonstrating per-problem exponential scaling can be made consistent with aggregate polynomial scaling if the distribution of single-attempt success probabilities is heavy tailed such that a small fraction of tasks with extremely low success probabilities collectively warp the aggregate success trend into a power law - even as each problem scales exponentially on its own. We further demonstrate that this distributional perspective explains previously observed deviations from power law scaling, and provides a simple method for forecasting the power law exponent with an order of magnitude lower relative error, or equivalently, ${\sim}2-4$ orders of magnitude less inference compute. Overall, our work contributes to a better understanding of how neural language model performance improves with scaling inference compute and the development of scaling-predictable evaluations of (multimodal) language models.

[Arxiv](https://arxiv.org/abs/2502.17578)
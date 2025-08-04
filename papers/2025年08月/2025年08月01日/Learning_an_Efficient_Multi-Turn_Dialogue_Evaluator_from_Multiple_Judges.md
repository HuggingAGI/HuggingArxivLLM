# 基于多评价者学习高效多轮对话评估器

发布时间：2025年08月01日

`LLM应用

这篇论文探讨了评估大型语言模型（LLMs）对话能力的方法，属于应用层面，因为它是在实际任务中应用和优化LLM的评估过程，而不是探讨模型本身的理论或结构。` `对话系统`

> Learning an Efficient Multi-Turn Dialogue Evaluator from Multiple Judges

# 摘要

> 评估大型语言模型（LLMs）的对话能力依然是一个充满挑战的任务。目前，主流方法主要依赖“LLM作为裁判”的范式，即通过提示LLM充当评估者来衡量对话质量。然而，这些方法往往受到各种偏见的影响，导致评估结果的可靠性和一致性大打折扣。为了减轻这些偏见，近期的方法采用了多个LLM作为裁判，并整合它们的判断来选择最佳评估。尽管这种方法有效，但在推理过程中带来了显著的计算开销。本文提出了一种高效的多轮对话评估器，通过整合多个LLM裁判的偏好知识到单一模型中，捕捉其集体智慧。我们的方法保留了多裁判反馈的多样性优势，同时大幅降低了评估成本，实现了快速灵活的对话质量评估。在七个单评分和配对比较的对话评估基准上进行的广泛实验表明，我们的方法在各种场景下均优于现有基线，充分展示了其高效性和鲁棒性。

> Evaluating the conversational abilities of large language models (LLMs) remains a challenging task. Current mainstream approaches primarily rely on the ``LLM-as-a-judge" paradigm, where an LLM is prompted to serve as an evaluator to assess dialogue quality. However, such methods often suffer from various biases, which undermine the reliability and consistency of the evaluation results. To mitigate these biases, recent methods employ multiple LLMs as judges and aggregate their judgments to select the optimal assessment. Although effective, this multi-judge approach incurs significant computational overhead during inference. In this paper, we propose an efficient multi-turn dialogue evaluator that captures the collective wisdom of multiple LLM judges by aggregating their preference knowledge into a single model. Our approach preserves the advantages of diverse multi-judge feedback while drastically reducing the evaluation cost, enabling fast and flexible dialogue quality assessment. Extensive experiments on seven single rating and pairwise comparison dialogue evaluation benchmarks demonstrate that our method outperforms existing baselines across diverse scenarios, showcasing its efficiency and robustness.

[Arxiv](https://arxiv.org/abs/2508.00454)
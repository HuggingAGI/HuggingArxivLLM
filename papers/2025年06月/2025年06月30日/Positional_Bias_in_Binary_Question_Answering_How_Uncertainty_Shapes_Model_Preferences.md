# 二元问答中的位置偏差：不确定性如何影响模型偏好

发布时间：2025年06月30日

`LLM应用` `问答系统`

> Positional Bias in Binary Question Answering: How Uncertainty Shapes Model Preferences

# 摘要

> 在二元问题回答中，模型可能因选项呈现顺序而产生位置偏差。本研究对五个大型语言模型在不同答案不确定性条件下的位置偏差进行了量化分析。我们基于SQuAD-it数据集，通过增加错误答案并调整上下文，创建了从低到高不确定性的多个数据集版本。此外，我们还评估了两个高不确定性基准：（1）WebGPT - 具有不等质量评分的问题对，以及（2）Winning Arguments - 预测Reddit讨论中更具说服力观点的任务。在每个数据集中，我们将正确或更具说服力的选项位置系统性翻转，计算偏好公平性和位置一致性。结果显示，低不确定性条件下位置偏差几乎不存在，但当答案难以判断时，偏差呈指数级增长。

> Positional bias in binary question answering occurs when a model systematically favors one choice over another based solely on the ordering of presented options. In this study, we quantify and analyze positional bias across five large language models under varying degrees of answer uncertainty. We re-adapted the SQuAD-it dataset by adding an extra incorrect answer option and then created multiple versions with progressively less context and more out-of-context answers, yielding datasets that range from low to high uncertainty. Additionally, we evaluate two naturally higher-uncertainty benchmarks: (1) WebGPT - question pairs with unequal human-assigned quality scores, and (2) Winning Arguments - where models predict the more persuasive argument in Reddit's r/ChangeMyView exchanges. Across each dataset, the order of the "correct" (or higher-quality/persuasive) option is systematically flipped (first placed in position 1, then in position 2) to compute both Preference Fairness and Position Consistency. We observe that positional bias is nearly absent under low-uncertainty conditions, but grows exponentially when it becomes doubtful to decide which option is correct.

[Arxiv](https://arxiv.org/abs/2506.23743)
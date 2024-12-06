# 若无法使用，那就回收：大规模优化合并能缓解性能的权衡问题

发布时间：2024年12月05日

`LLM应用` `模型开发` `语言处理`

> If You Can't Use Them, Recycle Them: Optimizing Merging at Scale Mitigates Performance Tradeoffs

# 摘要

> 模型合并在结合专家模型方面展现出极大潜力，然而在合并众多任务训练出的“通才”模型时，其益处尚不明确。我们于大型（$\sim100$B）模型的情境下，通过“回收”在不同任务间呈现权衡的检查点来探索合并。这类检查点常在开发前沿模型时产生，许多次优的通常会被舍弃。给定从不同训练运行（如不同阶段、目标、超参数和数据混合）获取的模型检查点池，它们在不同语言能力（如指令遵循对比代码生成）间自然呈现出权衡，我们探究合并能否将这些次优模型转化为帕累托最优模型。我们的优化算法调整线性组合中每个检查点的权重，从而得到优于单个模型和基于合并的基线的帕累托最优模型。进一步分析表明，良好的合并几乎都会包含所有具有非零权重的检查点，这意味着即使看似不佳的初始检查点也能为良好的最终合并贡献力量。

> Model merging has shown great promise at combining expert models, but the benefit of merging is unclear when merging ``generalist'' models trained on many tasks. We explore merging in the context of large ($\sim100$B) models, by \textit{recycling} checkpoints that exhibit tradeoffs among different tasks. Such checkpoints are often created in the process of developing a frontier model, and many suboptimal ones are usually discarded. Given a pool of model checkpoints obtained from different training runs (e.g., different stages, objectives, hyperparameters, and data mixtures), which naturally show tradeoffs across different language capabilities (e.g., instruction following vs. code generation), we investigate whether merging can recycle such suboptimal models into a Pareto-optimal one. Our optimization algorithm tunes the weight of each checkpoint in a linear combination, resulting in a Pareto-optimal models that outperforms both individual models and merge-based baselines. Further analysis shows that good merges tend to include almost all checkpoints with with non-zero weights, indicating that even seemingly bad initial checkpoints can contribute to good final merges.

[Arxiv](https://arxiv.org/abs/2412.04144)
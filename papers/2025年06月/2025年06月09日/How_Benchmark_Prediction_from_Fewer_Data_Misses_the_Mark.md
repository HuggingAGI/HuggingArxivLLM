# 用更少数据做基准预测为何总是差强人意

发布时间：2025年06月09日

`LLM理论` `人工智能` `模型评估`

> How Benchmark Prediction from Fewer Data Misses the Mark

# 摘要

> 大语言模型（LLM）的评估成本不断攀升，推动了通过缩减基准数据集来加速评估的研究。基准预测（也称高效LLM评估）的目标是选取少量评估点，通过这些点预测整体基准性能。本文系统性地评估了11种基准预测方法在19个多样化基准上的表现与局限。

首先，我们发现了一个极具竞争力的基线方法：从数据集中随机采样，然后在样本上拟合回归模型以预测缺失的条目。这一基线方法超越了大多数现有方法，挑战了“基准预测需要精心选择子集”的传统假设。

其次，我们发现所有现有方法都严重依赖于模型相似性。它们在插值相似模型的分数时表现最佳。然而，当新模型的准确性高于之前见过的模型时，基准预测的效果会急剧下降。在这种外推情况下，没有任何一种现有方法能稳定地超越随机样本的简单平均。

为了超越样本平均，我们引入了一种基于增强逆倾向加权的新方法。该方法在插值时始终优于随机样本平均，即使是在外推情况下也是如此。然而，其性能仍然依赖于模型相似性，总体增益相对有限。这表明，基准预测恰恰在最需要它的时候失败了：在评估前沿，目标是评估具有未知能力的新模型。


> Large language model (LLM) evaluation is increasingly costly, prompting interest in methods that speed up evaluation by shrinking benchmark datasets. Benchmark prediction (also called efficient LLM evaluation) aims to select a small subset of evaluation points and predict overall benchmark performance from that subset. In this paper, we systematically assess the strengths and limitations of 11 benchmark prediction methods across 19 diverse benchmarks. First, we identify a highly competitive baseline: Take a random sample and fit a regression model on the sample to predict missing entries. Outperforming most existing methods, this baseline challenges the assumption that careful subset selection is necessary for benchmark prediction. Second, we discover that all existing methods crucially depend on model similarity. They work best when interpolating scores among similar models. The effectiveness of benchmark prediction sharply declines when new models have higher accuracy than previously seen models. In this setting of extrapolation, none of the previous methods consistently beat a simple average over random samples. To improve over the sample average, we introduce a new method inspired by augmented inverse propensity weighting. This method consistently outperforms the random sample average even for extrapolation. However, its performance still relies on model similarity and the gains are modest in general. This shows that benchmark prediction fails just when it is most needed: at the evaluation frontier, where the goal is to evaluate new models of unknown capabilities.

[Arxiv](https://arxiv.org/abs/2506.07673)
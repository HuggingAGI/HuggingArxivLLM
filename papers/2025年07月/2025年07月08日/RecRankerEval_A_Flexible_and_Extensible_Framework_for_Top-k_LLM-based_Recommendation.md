# RecRankerEval：一个灵活可扩展的基于大语言模型的Top-k推荐框架

发布时间：2025年07月08日

`LLM应用` `推荐系统` `信息检索`

> RecRankerEval: A Flexible and Extensible Framework for Top-k LLM-based Recommendation

# 摘要

> 最近，一种名为RecRanker的基于大型语言模型（LLM）的推荐模型在top-k推荐任务中表现优异。该模型通过聚类采样用户，利用初始推荐模型生成排名列表，并通过混合指令调优微调LLM以推断用户偏好。然而，其核心组件的贡献尚未被充分研究。本研究旨在检验RecRanker的可复现性，并深入分析其各组件的影响。我们通过实现其所有关键组件，成功复现了RecRanker的流程。实验结果表明，成对比较和列表排序方法的性能与原论文相当。然而，点式方法的性能异常高，原因是数据泄露——原论文在提示中包含了真实信息。为实现对基于LLM的top-k推荐的全面评估，我们提出了RecRankerEval框架，涵盖用户采样策略、初始推荐模型、LLM主干、数据集选择和指令调优方法五个维度。通过该框架，我们发现RecRanker的原始结果可以在ML-100K、ML-1M和Amazon-Music数据集上复现，但无法在BookCrossing上复现，因为原论文中缺乏时间戳信息。此外，我们还发现，通过采用替代用户采样方法、更强的初始推荐器和更强大的LLM，可以显著提升RecRanker的性能。

> A recent Large language model (LLM)-based recommendation model, called RecRanker, has demonstrated a superior performance in the top-k recommendation task compared to other models. In particular, RecRanker samples users via clustering, generates an initial ranking list using an initial recommendation model, and fine-tunes an LLM through hybrid instruction tuning to infer user preferences. However, the contribution of each core component remains underexplored. In this work, we inspect the reproducibility of RecRanker, and study the impact and role of its various components. We begin by reproducing the RecRanker pipeline through the implementation of all its key components. Our reproduction shows that the pairwise and listwise methods achieve a performance comparable to that reported in the original paper. For the pointwise method, while we are also able to reproduce the original paper's results, further analysis shows that the performance is abnormally high due to data leakage from the inclusion of ground-truth information in the prompts. To enable a fair and comprehensive evaluation of LLM-based top-k recommendations, we propose RecRankerEval, an extensible framework that covers five key dimensions: user sampling strategy, initial recommendation model, LLM backbone, dataset selection, and instruction tuning method. Using the RecRankerEval framework, we show that the original results of RecRanker can be reproduced on the ML-100K and ML-1M datasets, as well as the additional Amazon-Music dataset, but not on BookCrossing due to the lack of timestamp information in the original RecRanker paper. Furthermore, we demonstrate that RecRanker's performance can be improved by employing alternative user sampling methods, stronger initial recommenders, and more capable LLMs.

[Arxiv](https://arxiv.org/abs/2507.05880)
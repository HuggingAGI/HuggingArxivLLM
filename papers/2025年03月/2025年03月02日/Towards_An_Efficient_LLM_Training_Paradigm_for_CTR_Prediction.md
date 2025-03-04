# 构建高效LLM训练范式，用于点击率预测

发布时间：2025年03月02日

`LLM应用` `推荐系统` `电子商务`

> Towards An Efficient LLM Training Paradigm for CTR Prediction

# 摘要

> 大型语言模型 (LLMs) 作为下一代基于排序的推荐系统，展现出巨大的潜力。近期研究表明，LLMs 在点击率 (CTR) 预测方面显著优于传统方法。然而，现有训练范式的低效性使得在大规模数据集上训练用于推荐任务的 LLMs 面临巨大挑战。为了训练用于 CTR 预测的 LLMs，现有研究主要采用“滑动窗口”范式。具体而言，给定长度为 $m$ 的用户交互序列，通过将每个交互指定为预测目标，并将其前面的 $n$ 个交互作为上下文，从而为每个交互构建独特的训练提示。然而，滑动窗口范式的复杂度为 $O(mn^2)$，与交互长度呈线性增长关系。这使得直接采用该策略训练 LLMs 的成本随着交互长度增加而急剧上升。为解决这一问题，我们提出了一种新型训练范式——动态目标隔离 (DTI)，该方法能够对 $k$ 个（$k >> 1$）目标交互进行结构化并行训练。此外，我们识别出隐藏状态泄露和位置偏见过拟合两大瓶颈，这些瓶颈限制了 DTI 仅能扩展到较小的 $k$ 值（例如 5）。针对这些问题，我们提出了一种计算高效的解决方案。通过在三个广泛采用的公共 CTR 数据集上的大量实验，我们实证表明，DTI 将训练时间平均减少了 $	extbf{92\%}$（例如，从 $70.5$ 小时减少到 $5.31$ 小时），同时保持了 CTR 预测性能。

> Large Language Models (LLMs) have demonstrated tremendous potential as the next-generation ranking-based recommendation system. Many recent works have shown that LLMs can significantly outperform conventional click-through-rate (CTR) prediction approaches. Despite such promising results, the computational inefficiency inherent in the current training paradigm makes it particularly challenging to train LLMs for ranking-based recommendation tasks on large datasets. To train LLMs for CTR prediction, most existing studies adopt the prevalent ''sliding-window'' paradigm. Given a sequence of $m$ user interactions, a unique training prompt is constructed for each interaction by designating it as the prediction target along with its preceding $n$ interactions serving as context. In turn, the sliding-window paradigm results in an overall complexity of $O(mn^2)$ that scales linearly with the length of user interactions. Consequently, a direct adoption to train LLMs with such strategy can result in prohibitively high training costs as the length of interactions grows. To alleviate the computational inefficiency, we propose a novel training paradigm, namely Dynamic Target Isolation (DTI), that structurally parallelizes the training of $k$ (where $k >> 1$) target interactions. Furthermore, we identify two major bottlenecks - hidden-state leakage and positional bias overfitting - that limit DTI to only scale up to a small value of $k$ (e.g., 5) then propose a computationally light solution to effectively tackle each. Through extensive experiments on three widely adopted public CTR datasets, we empirically show that DTI reduces training time by an average of $\textbf{92%}$ (e.g., from $70.5$ hrs to $5.31$ hrs), without compromising CTR prediction performance.

[Arxiv](https://arxiv.org/abs/2503.01001)
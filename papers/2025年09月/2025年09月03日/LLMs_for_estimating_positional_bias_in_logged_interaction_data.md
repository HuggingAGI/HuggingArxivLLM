# 用于估计日志交互数据中位置偏差的大型语言模型（LLMs）

发布时间：2025年09月03日

`LLM应用` `零售与电商`

> LLMs for estimating positional bias in logged interaction data

# 摘要

> 推荐与搜索系统通常借助用户交互日志训练排序学习模型，依据预测相关性对项目排序。但这类交互数据常受位置偏差干扰：用户更倾向于点击排名靠前的项目，与其实际相关性无关。因此，新训练的模型可能继承并放大先前排序模型的偏差，而非真正提升相关性。缓解位置偏差的标准方法是逆倾向评分（IPS）：用倾向函数的倒数对模型损失加权，而倾向函数即给定位置项目被查看概率的估计。但准确估计倾向值颇具挑战，尤其在复杂非线性布局的界面中。本文提出一种新方法：利用大型语言模型（LLMs）处理用户交互日志数据，以估计位置偏差。该方法为在线实验提供了经济高效的替代方案。实验表明，我们提出的“LLM评判者”方法所估计的倾向在分数桶中稳定性良好，还能捕捉到Viator网格布局的行列效应——这是简单启发式方法所忽略的。基于这些倾向训练的IPS加权重排序器，在标准NDCG@10上与生产模型性能相当，同时将加权NDCG@10提升约2%。我们将在后续实时流量实验中验证这些离线增益。

> Recommender and search systems commonly rely on Learning To Rank models trained on logged user interactions to order items by predicted relevance. However, such interaction data is often subject to position bias, as users are more likely to click on items that appear higher in the ranking, regardless of their actual relevance. As a result, newly trained models may inherit and reinforce the biases of prior ranking models rather than genuinely improving relevance. A standard approach to mitigate position bias is Inverse Propensity Scoring (IPS), where the model's loss is weighted by the inverse of a propensity function, an estimate of the probability that an item at a given position is examined. However, accurate propensity estimation is challenging, especially in interfaces with complex non-linear layouts. In this paper, we propose a novel method for estimating position bias using Large Language Models (LLMs) applied to logged user interaction data. This approach offers a cost-effective alternative to online experimentation. Our experiments show that propensities estimated with our LLM-as-a-judge approach are stable across score buckets and reveal the row-column effects of Viator's grid layout that simpler heuristics overlook. An IPS-weighted reranker trained with these propensities matches the production model on standard NDCG@10 while improving weighted NDCG@10 by roughly 2%. We will verify these offline gains in forthcoming live-traffic experiments.

[Arxiv](https://arxiv.org/abs/2509.03696)
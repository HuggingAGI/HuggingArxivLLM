# # 概率无误：精细粒度条件概率估计

发布时间：2025年05月02日

`LLM理论` `人工智能` `统计学`

> Always Tell Me The Odds: Fine-grained Conditional Probability Estimation

# 摘要

> 我们提出了一种先进的模型，用于在给定上下文的情况下对命题进行细粒度的概率估计。大型语言模型（LLMs）在推理能力上的显著提升，特别是在信息完整、定义明确的任务上表现突出。然而，面对不确定性或信息不全的情况，LLMs仍然难以做出准确且校准良好的概率预测。尽管将不确定性纳入模型预测通常能提升性能，但如何可靠地估计这种不确定性仍是一个未被充分研究的领域。特别是，LLMs的概率估计往往比较粗略，且偏向于更频繁出现的数字。通过结合人工和合成数据的创建与评估，扩展到更大的模型，以及更好的监督，我们提出了一组强大且精确的概率估计模型。我们在依赖条件概率估计的任务上进行了系统评估，结果显示，我们的方法在很大程度上优于现有的微调和基于提示的方法。

> We present a state-of-the-art model for fine-grained probability estimation of propositions conditioned on context. Recent advances in large language models (LLMs) have significantly enhanced their reasoning capabilities, particularly on well-defined tasks with complete information. However, LLMs continue to struggle with making accurate and well-calibrated probabilistic predictions under uncertainty or partial information. While incorporating uncertainty into model predictions often boosts performance, obtaining reliable estimates of that uncertainty remains understudied. In particular, LLM probability estimates tend to be coarse and biased towards more frequent numbers. Through a combination of human and synthetic data creation and assessment, scaling to larger models, and better supervision, we propose a set of strong and precise probability estimation models. We conduct systematic evaluations across tasks that rely on conditional probability estimation and show that our approach consistently outperforms existing fine-tuned and prompting-based methods by a large margin.

[Arxiv](https://arxiv.org/abs/2505.01595)
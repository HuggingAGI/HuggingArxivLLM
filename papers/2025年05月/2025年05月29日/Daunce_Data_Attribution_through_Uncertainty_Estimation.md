# Daunce：通过不确定性估计实现数据归属分析

发布时间：2025年05月29日

`LLM应用` `数据科学` `人工智能`

> Daunce: Data Attribution through Uncertainty Estimation

# 摘要

> 训练数据归属（TDA）方法旨在识别哪些训练样本对模型在特定测试数据上的预测影响最大。通过量化这些影响，TDA支持关键应用如数据调试、整理和评估。基于梯度的TDA方法依赖于梯度和二阶信息，限制了它们在大规模应用中的适用性。尽管最近基于随机投影的方法提高了可扩展性，但它们通常会因归属精度下降而受到影响。受不确定性与影响函数之间联系的启发，我们引入了Daunce——一种通过不确定性估计实现数据归属的简单而有效的方法。我们的方法通过微调一组扰动模型，并计算这些模型中每个样本损失的协方差作为归属分数来运作。Daunce适用于大型语言模型（LLMs），与现有的TDA方法相比，它实现了更准确的归属。我们在从视觉任务到LLM微调的各种任务上验证了Daunce，并进一步展示了其与黑盒模型访问的兼容性。应用于OpenAI的GPT模型，据我们所知，我们的方法实现了专有LLMs上的首次数据归属实例。

> Training data attribution (TDA) methods aim to identify which training examples influence a model's predictions on specific test data most. By quantifying these influences, TDA supports critical applications such as data debugging, curation, and valuation. Gradient-based TDA methods rely on gradients and second-order information, limiting their applicability at scale. While recent random projection-based methods improve scalability, they often suffer from degraded attribution accuracy. Motivated by connections between uncertainty and influence functions, we introduce Daunce - a simple yet effective data attribution approach through uncertainty estimation. Our method operates by fine-tuning a collection of perturbed models and computing the covariance of per-example losses across these models as the attribution score. Daunce is scalable to large language models (LLMs) and achieves more accurate attribution compared to existing TDA methods. We validate Daunce on tasks ranging from vision tasks to LLM fine-tuning, and further demonstrate its compatibility with black-box model access. Applied to OpenAI's GPT models, our method achieves, to our knowledge, the first instance of data attribution on proprietary LLMs.

[Arxiv](https://arxiv.org/abs/2505.23223)
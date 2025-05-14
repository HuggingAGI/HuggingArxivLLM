# 多模态LLM与Kolmogorov Arnold网络结合的符号回归

发布时间：2025年05月12日

`LLM应用` `科学计算` `符号回归`

> Symbolic Regression with Multimodal Large Language Models and Kolmogorov Arnold Networks

# 摘要

> 我们提出了一种基于视觉能力大型语言模型（LLMs）和Google DeepMind Funsearch思想的新型符号回归方法。该方法通过给定单变量函数图像，由LLM生成试探解（ansatz），并利用标准数值优化器拟合参数。这些试探解构成遗传算法种群。与传统方法不同，本方法无需预先设定回归函数集，而是通过精心设计的提示工程灵活控制生成过程。借助Kolmogorov Arnold网络（KANs），我们证明单变量函数足以完成符号回归任务，并通过在训练好的KAN各边学习单变量函数，成功将方法扩展至多变量函数。最后，语言模型进一步简化组合表达式，提升结果简洁性。

> We present a novel approach to symbolic regression using vision-capable large language models (LLMs) and the ideas behind Google DeepMind's Funsearch. The LLM is given a plot of a univariate function and tasked with proposing an ansatz for that function. The free parameters of the ansatz are fitted using standard numerical optimisers, and a collection of such ansätze make up the population of a genetic algorithm. Unlike other symbolic regression techniques, our method does not require the specification of a set of functions to be used in regression, but with appropriate prompt engineering, we can arbitrarily condition the generative step. By using Kolmogorov Arnold Networks (KANs), we demonstrate that ``univariate is all you need'' for symbolic regression, and extend this method to multivariate functions by learning the univariate function on each edge of a trained KAN. The combined expression is then simplified by further processing with a language model.

[Arxiv](https://arxiv.org/abs/2505.07956)
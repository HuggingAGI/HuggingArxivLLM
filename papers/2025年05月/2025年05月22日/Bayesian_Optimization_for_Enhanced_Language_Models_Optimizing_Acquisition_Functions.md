# 贝叶斯优化提升语言模型性能：优化获取函数

发布时间：2025年05月22日

`LLM应用

理由：这篇论文探讨了在微调大型语言模型时，通过优化超参数选择来提升模型性能的方法。它提出了一种结合贝叶斯优化和模型融合的策略，以提高下游任务中的泛化能力。这属于将大型语言模型应用于特定任务并优化其性能的范畴，因此归类为LLM应用。` `超参数调优`

> Bayesian Optimization for Enhanced Language Models: Optimizing Acquisition Functions

# 摘要

> 随着语言模型架构的多样化发展，微调在下游任务中的重要性日益凸显。然而，模型复杂性增加导致寻找合适的微调超参数变得更具挑战性。尽管贝叶斯优化（BO）被用于超参数调优，但现有方法往往忽视了BO对获取函数选择的依赖性。获取函数作为BO的核心组件，决定了优化过程中探索与利用的平衡；不同获取函数对训练损失和验证性能的敏感度存在显著差异；现有方法通常不加选择地应用某一获取函数，而未考虑其对训练和验证性能的敏感性。为此，我们提出了{Bilevel - BO - SWA}，一种结合双层BO策略的模型融合方法，旨在提升大型语言模型的微调效果。通过将EI和UCB等获取函数进行混合，并嵌入到嵌套优化循环中，其中内循环负责最小化训练损失，而外循环则根据验证指标进行优化。实验结果表明，在使用RoBERTA-base进行的GLUE任务中，采用EI和UCB的混合策略可提升模型的泛化能力，微调效果最多可提高2.7%。

> With the rise of different language model architecture, fine-tuning is becoming even more important for down stream tasks Model gets messy, finding proper hyperparameters for fine-tuning. Although BO has been tried for hyperparameter tuning, most of the existing methods are oblivious to the fact that BO relies on careful choices of acquisition functions, which are essential components of BO that guide how much to explore versus exploit during the optimization process; Different acquisition functions have different levels of sensitivity towards training loss and validation performance; existing methods often just apply an acquisition function no matter if the training and validation performance are sensitive to the acquisition function or not. This work introduces{Bilevel - BO - SWA}, a model fusion approach coupled with a bilevel BO strategy to improve the fine - tunning of large language models. Our work on mixture of acquisition functions like EI and UCB into nested opt loops, where inner loop perform minimization of training loss while outer loops optimized w.r.t. val metric. Experiments on GLUE tasks using RoBERTA - base show that when using EI and UCB, there is an improvement in generalization, and fine - tuning can be improved by up to 2.7%.

[Arxiv](https://arxiv.org/abs/2505.17151)
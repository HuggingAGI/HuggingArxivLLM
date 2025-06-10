# 语言模型鲁棒性审核的统计假设检验方法

发布时间：2025年06月09日

`LLM理论` `人工智能` `软件工程`

> Statistical Hypothesis Testing for Auditing Robustness in Language Models

# 摘要

> 考虑这样一个问题：测试大型语言模型（LLM）系统在任意干预（如输入扰动或更改模型变体）下的输出是否发生变化。我们不能简单地比较两个LLM输出，因为它们可能因系统的随机性而不同，也无法比较整个输出分布，因为计算上不可行。虽然现有的文本输出分析方法存在，但它们关注的是本质上不同的问题，例如衡量偏见或公平性。为此，我们引入了基于分布的扰动分析框架，将LLM扰动分析重新表述为一种频率主义假设检验问题。我们通过蒙特卡洛采样在低维语义相似性空间中构建经验的原假设和备择假设输出分布，从而实现无需严格分布假设的可处理推理。该框架具有以下特点：(i) 模型无关；(ii) 支持对任何黑盒LLM的任意输入扰动进行评估；(iii) 生成可解释的p值；(iv) 通过控制错误率支持多个扰动；(v) 提供标量效应量。我们通过多个案例研究展示了该框架的实用性，展示了如何量化响应变化、测量真实/虚假阳性率以及评估与参考模型的一致性。最重要的是，我们认为这是一个可靠的频率主义假设检验框架，适用于LLM审核。

> Consider the problem of testing whether the outputs of a large language model (LLM) system change under an arbitrary intervention, such as an input perturbation or changing the model variant. We cannot simply compare two LLM outputs since they might differ due to the stochastic nature of the system, nor can we compare the entire output distribution due to computational intractability. While existing methods for analyzing text-based outputs exist, they focus on fundamentally different problems, such as measuring bias or fairness. To this end, we introduce distribution-based perturbation analysis, a framework that reformulates LLM perturbation analysis as a frequentist hypothesis testing problem. We construct empirical null and alternative output distributions within a low-dimensional semantic similarity space via Monte Carlo sampling, enabling tractable inference without restrictive distributional assumptions. The framework is (i) model-agnostic, (ii) supports the evaluation of arbitrary input perturbations on any black-box LLM, (iii) yields interpretable p-values; (iv) supports multiple perturbations via controlled error rates; and (v) provides scalar effect sizes. We demonstrate the usefulness of the framework across multiple case studies, showing how we can quantify response changes, measure true/false positive rates, and evaluate alignment with reference models. Above all, we see this as a reliable frequentist hypothesis testing framework for LLM auditing.

[Arxiv](https://arxiv.org/abs/2506.07947)
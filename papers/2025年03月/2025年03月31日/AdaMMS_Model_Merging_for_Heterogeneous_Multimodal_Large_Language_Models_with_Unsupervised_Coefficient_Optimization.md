# # AdaMMS：异构多模态大语言模型的模型融合与无监督系数优化

发布时间：2025年03月31日

`LLM应用` `模型合并`

> AdaMMS: Model Merging for Heterogeneous Multimodal Large Language Models with Unsupervised Coefficient Optimization

# 摘要

> 模型合并方法近期在结合多个大型语言模型（LLMs）的各种任务能力方面展现了强大的能力。然而，传统方法主要针对同构模型，而面对架构差异和参数空间不对称的多模态大语言模型（MLLMs）时往往力不从心。为解决这一难题，我们提出了AdaMMS——首个专为异构MLLMs设计的模型合并方法。AdaMMS通过三步策略：映射、合并和搜索，成功克服了异构模型的合并挑战。首先，我们设计跨模型的映射函数，使架构各异的MLLMs能够顺利合并；其次，通过线性插值主动适应模型间的参数不对称性；最后，我们创新性地提出了无监督超参数选择方法，进一步优化合并效果。实验证明，AdaMMS在多种视觉语言基准测试中显著超越传统方法，展现了其强大的跨模型融合能力。

> Recently, model merging methods have demonstrated powerful strengths in combining abilities on various tasks from multiple Large Language Models (LLMs). While previous model merging methods mainly focus on merging homogeneous models with identical architecture, they meet challenges when dealing with Multimodal Large Language Models (MLLMs) with inherent heterogeneous property, including differences in model architecture and the asymmetry in the parameter space. In this work, we propose AdaMMS, a novel model merging method tailored for heterogeneous MLLMs. Our method tackles the challenges in three steps: mapping, merging and searching. Specifically, we first design mapping function between models to apply model merging on MLLMs with different architecture. Then we apply linear interpolation on model weights to actively adapt the asymmetry in the heterogeneous MLLMs. Finally in the hyper-parameter searching step, we propose an unsupervised hyper-parameter selection method for model merging. As the first model merging method capable of merging heterogeneous MLLMs without labeled data, extensive experiments on various model combinations demonstrated that AdaMMS outperforms previous model merging methods on various vision-language benchmarks.

[Arxiv](https://arxiv.org/abs/2503.23733)
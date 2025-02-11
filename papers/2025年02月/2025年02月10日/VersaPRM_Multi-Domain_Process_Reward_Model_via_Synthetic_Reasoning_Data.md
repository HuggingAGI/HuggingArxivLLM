# VersaPRM：基于合成推理数据的多领域流程奖励模型

发布时间：2025年02月10日

`LLM应用` `人工智能`

> VersaPRM: Multi-Domain Process Reward Model via Synthetic Reasoning Data

# 摘要

> 过程奖励模型（PRMs）通过增加推理时的计算量，已被证明能有效提升大型语言模型（LLMs）的数学推理能力。但它们主要基于数学数据进行训练，对于非数学领域的泛化能力尚未得到严格研究。针对这一问题，本研究首先表明当前的PRMs在其他领域表现欠佳。为解决这一局限，我们引入了VersaPRM，这是一种基于合成推理数据训练的多领域PRM，这些数据通过我们新颖的数据生成和标注方法获得。VersaPRM在各类领域中均实现了性能提升。例如，在MMLU-Pro法律类别中，VersaPRM通过加权多数投票法，相比多数投票基线模型，实现了7.9%的性能提升——超越了Qwen2.5-Math-PRM的1.3%增益。我们进一步为社区做出贡献，开源了VersaPRM的所有数据、代码和模型。

> Process Reward Models (PRMs) have proven effective at enhancing mathematical reasoning for Large Language Models (LLMs) by leveraging increased inference-time computation. However, they are predominantly trained on mathematical data and their generalizability to non-mathematical domains has not been rigorously studied. In response, this work first shows that current PRMs have poor performance in other domains. To address this limitation, we introduce VersaPRM, a multi-domain PRM trained on synthetic reasoning data generated using our novel data generation and annotation method. VersaPRM achieves consistent performance gains across diverse domains. For instance, in the MMLU-Pro category of Law, VersaPRM via weighted majority voting, achieves a 7.9% performance gain over the majority voting baseline -- surpassing Qwen2.5-Math-PRM's gain of 1.3%. We further contribute to the community by open-sourcing all data, code and models for VersaPRM.

[Arxiv](https://arxiv.org/abs/2502.06737)
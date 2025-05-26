# LLM 携手决策树，探索表格数据新天地

发布时间：2025年05月23日

`LLM应用` `表格数据处理` `决策树增强`

> LLM Meeting Decision Trees on Tabular Data

# 摘要

> 表格数据在医疗、金融等多个现实领域中发挥着关键作用。随着大型语言模型（LLMs）的成功，人们开始尝试将LLMs扩展到表格数据领域。大多数基于LLM的方法通常会先将表格数据序列化为自然语言描述，然后对LLMs进行微调或直接在这些序列化数据上进行推理。然而，这些方法在两个关键方面存在固有问题：(i) 数据角度：现有的数据序列化方法缺乏对结构化表格数据的通用适用性，并可能通过直接文本暴露带来隐私风险；(ii) 模型角度：LLM微调方法在处理表格数据时表现不佳，且上下文学习的可扩展性受限于输入长度约束（适用于少量样本学习）。本研究探索了一种将LLMs与逻辑决策树规则相结合的新方向，提出了一种基于LLM生成规则的表格预测决策树增强器DeLTa。该方法避免了表格数据的序列化，并可以在不进行LLM微调的情况下应用于全数据学习场景。具体来说，我们利用LLMs的推理能力，根据给定的决策树规则重新设计改进后的规则。此外，我们通过LLM生成的新规则提供了一种校准原始决策树的方法，该方法通过近似误差修正向量，引导原始决策树的预测结果朝着减少“错误”的方向调整。最后，我们在多样化的表格基准数据集上进行了大量实验，结果表明我们的方法达到了最先进的性能。

> Tabular data have been playing a vital role in diverse real-world fields, including healthcare, finance, etc. With the recent success of Large Language Models (LLMs), early explorations of extending LLMs to the domain of tabular data have been developed. Most of these LLM-based methods typically first serialize tabular data into natural language descriptions, and then tune LLMs or directly infer on these serialized data. However, these methods suffer from two key inherent issues: (i) data perspective: existing data serialization methods lack universal applicability for structured tabular data, and may pose privacy risks through direct textual exposure, and (ii) model perspective: LLM fine-tuning methods struggle with tabular data, and in-context learning scalability is bottle-necked by input length constraints (suitable for few-shot learning). This work explores a novel direction of integrating LLMs into tabular data throughough logical decision tree rules as intermediaries, proposes a decision tree enhancer with LLM-derived rule for tabular prediction, DeLTa. The proposed DeLTa avoids tabular data serialization, and can be applied to full data learning setting without LLM fine-tuning. Specifically, we leverage the reasoning ability of LLMs to redesign an improved rule given a set of decision tree rules. Furthermore, we provide a calibration method for original decision trees via new generated rule by LLM, which approximates the error correction vector to steer the original decision tree predictions in the direction of ``errors'' reducing. Finally, extensive experiments on diverse tabular benchmarks show that our method achieves state-of-the-art performance.

[Arxiv](https://arxiv.org/abs/2505.17918)
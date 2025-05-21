# 特征关键：一种轻量级LLM增强方法应用于点击率预测

发布时间：2025年05月20日

`LLM应用` `推荐系统` `人工智能`

> Field Matters: A lightweight LLM-enhanced Method for CTR Prediction

# 摘要

> 点击率（CTR）预测是现代推荐系统的核心任务。近年来，大型语言模型（LLMs）的引入为传统CTR方法带来了显著提升。然而，现有结合LLM的方法往往需要处理大规模实例或用户/物品的详细文本描述，导致计算开销过高。为解决这一问题，我们提出了LLaCTR，一种创新且轻量化的LLM增强型CTR方法，采用基于字段级别的增强范式。具体而言，LLaCTR通过自监督字段特征微调，利用LLMs从小规模特征字段中提取关键且轻量的语义知识。随后，它利用这些语义知识来优化特征表示和特征交互。实验中，我们将LLaCTR与四个数据集上的六种代表性CTR模型进行了集成，结果表明，LLaCTR在有效性和效率方面均优于现有LLM增强方法。我们的代码可在https://anonymous.4open.science/r/LLaCTR-EC46获取。

> Click-through rate (CTR) prediction is a fundamental task in modern recommender systems. In recent years, the integration of large language models (LLMs) has been shown to effectively enhance the performance of traditional CTR methods. However, existing LLM-enhanced methods often require extensive processing of detailed textual descriptions for large-scale instances or user/item entities, leading to substantial computational overhead. To address this challenge, this work introduces LLaCTR, a novel and lightweight LLM-enhanced CTR method that employs a field-level enhancement paradigm. Specifically, LLaCTR first utilizes LLMs to distill crucial and lightweight semantic knowledge from small-scale feature fields through self-supervised field-feature fine-tuning. Subsequently, it leverages this field-level semantic knowledge to enhance both feature representation and feature interactions. In our experiments, we integrate LLaCTR with six representative CTR models across four datasets, demonstrating its superior performance in terms of both effectiveness and efficiency compared to existing LLM-enhanced methods. Our code is available at https://anonymous.4open.science/r/LLaCTR-EC46.

[Arxiv](https://arxiv.org/abs/2505.14057)
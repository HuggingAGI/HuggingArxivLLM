# LLM-Ensemble 是一种针对电商领域的产品属性值抽取任务设计出的最优大型语言模型集成方案。

发布时间：2024年02月29日

`LLM应用`

> LLM-Ensemble: Optimal Large Language Model Ensemble Method for E-commerce Product Attribute Value Extraction

# 摘要

> 在NLP与电商领域，产品属性值提取扮演着核心角色，其精确性直接影响推荐质量与客户满意度。新兴的大型语言模型（LLMs）不依赖特定领域数据，却在多项属性提取任务中表现出色。不过，各异的数据来源、架构设计和超参数配置导致各类LLMs各有所长也各有短板。因此，如何整合并充分利用这些模型的优势互补成为了一个亟待解决的问题。为此，本研究创新性地提出了LLM-ensemble算法，将不同LLMs的输出融合，共同完成属性值提取任务。该算法通过迭代学习为每个LLM动态赋予权重，并据此加权融合各个模型的预测结果，以确定最终属性值。理论分析表明此方法具有最优性，且兼顾高效运算、快速收敛与安全部署。我们采用包括Llama2-13B、Llama2-70B、PaLM-2、GPT-3.5以及GPT-4在内的多种顶级LLMs，在沃尔玛内部数据集上展开了深入实验。实验证据充分展示了LLM-ensemble方法在沃尔玛内部数据上的优越性，超越了所有单独顶级LLMs的表现。目前，此方法已成功应用于多个生产模型中，有力提升了GMV、CTR、CVR和加入购物车率等关键业务指标。

> Product attribute value extraction is a pivotal component in Natural Language Processing (NLP) and the contemporary e-commerce industry. The provision of precise product attribute values is fundamental in ensuring high-quality recommendations and enhancing customer satisfaction. The recently emerging Large Language Models (LLMs) have demonstrated state-of-the-art performance in numerous attribute extraction tasks, without the need for domain-specific training data. Nevertheless, varying strengths and weaknesses are exhibited by different LLMs due to the diversity in data, architectures, and hyperparameters. This variation makes them complementary to each other, with no single LLM dominating all others. Considering the diverse strengths and weaknesses of LLMs, it becomes necessary to develop an ensemble method that leverages their complementary potentials. In this paper, we propose a novel algorithm called LLM-ensemble to ensemble different LLMs' outputs for attribute value extraction. We iteratively learn the weights for different LLMs to aggregate the labels with weights to predict the final attribute value. Not only can our proposed method be proven theoretically optimal, but it also ensures efficient computation, fast convergence, and safe deployment. We have also conducted extensive experiments with various state-of-the-art LLMs, including Llama2-13B, Llama2-70B, PaLM-2, GPT-3.5, and GPT-4, on Walmart's internal data. Our offline metrics demonstrate that the LLM-ensemble method outperforms all the state-of-the-art single LLMs on Walmart's internal dataset. This method has been launched in several production models, leading to improved Gross Merchandise Volume (GMV), Click-Through Rate (CTR), Conversion Rate (CVR), and Add-to-Cart Rate (ATC).

[Arxiv](https://arxiv.org/abs/2403.00863)
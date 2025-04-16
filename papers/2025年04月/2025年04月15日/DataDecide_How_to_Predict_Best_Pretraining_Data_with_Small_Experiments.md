# # DataDecide：用小实验预测最佳预训练数据的方法

发布时间：2025年04月15日

`LLM应用` `人工智能` `机器学习`

> DataDecide: How to Predict Best Pretraining Data with Small Experiments

# 摘要

> 由于预训练大型语言模型成本高昂，通过小规模实验来选择数据集对于降低成本至关重要。哪些基准测试和从小规模实验中制定决策的方法最能准确预测生成最佳大型模型的数据集？我们通过 DataDecide 工具包支持这一问题的开放探索，这是研究数据和规模差异的最全面开放工具包。我们跨25个语料库进行了受控预训练实验，这些语料库具有不同的来源、去重和过滤方法，规模高达1000亿个token，模型规模高达10亿个参数，并使用了3个随机种子。我们发现，模型在单一、小规模（例如1.5亿个参数）下的排名是预测我们在更大目标规模（10亿个参数）下最佳模型的有力基准（约80%的比较正确）。在8个基线中，没有一种缩放定律方法能够超越单一规模预测的计算决策边界，但 DataDecide 可以衡量未来缩放定律的改进。我们还发现，在小规模实验中使用连续似然度指标作为代理，可以使包括 MMLU、ARC、HellaSwag、MBPP 和 HumanEval 在内的基准测试在目标 10 亿个参数规模下仅使用 0.01% 的计算量即可实现 >80% 的可预测性。

> Because large language models are expensive to pretrain on different datasets, using smaller-scale experiments to decide on data is crucial for reducing costs. Which benchmarks and methods of making decisions from observed performance at small scale most accurately predict the datasets that yield the best large models? To empower open exploration of this question, we release models, data, and evaluations in DataDecide -- the most extensive open suite of models over differences in data and scale. We conduct controlled pretraining experiments across 25 corpora with differing sources, deduplication, and filtering up to 100B tokens, model sizes up to 1B parameters, and 3 random seeds. We find that the ranking of models at a single, small size (e.g., 150M parameters) is a strong baseline for predicting best models at our larger target scale (1B) (~80% of com parisons correct). No scaling law methods among 8 baselines exceed the compute-decision frontier of single-scale predictions, but DataDecide can measure improvement in future scaling laws. We also identify that using continuous likelihood metrics as proxies in small experiments makes benchmarks including MMLU, ARC, HellaSwag, MBPP, and HumanEval >80% predictable at the target 1B scale with just 0.01% of the compute.

[Arxiv](https://arxiv.org/abs/2504.11393)
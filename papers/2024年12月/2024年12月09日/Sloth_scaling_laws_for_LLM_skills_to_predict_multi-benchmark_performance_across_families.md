# Sloth：预测跨家族多基准性能的 LLM 技能缩放定律

发布时间：2024年12月09日

`LLM理论` `语言模型` `基准测试`

> Sloth: scaling laws for LLM skills to predict multi-benchmark performance across families

# 摘要

> 大型语言模型（LLMs）的缩放定律依据像规模和训练数据之类的参数来预测模型性能。然而，不同模型家族在训练配置和数据处理上的差别致使基准性能有显著变化，单一缩放定律难以通用于所有LLMs。另一方面，为每个家族训练特定的缩放定律就得为其训练不同规模的模型。在本项工作中，我们提出了技能缩放定律（SSLaws，读音为“Sloth”），这一新颖的缩放定律利用公开可得的基准数据，假定LLM性能由低维潜在技能驱动，比如推理和遵循指令。这些潜在技能受模型规模和训练标记等计算资源影响，但在不同模型家族中的效率各异。Sloth借助基准之间的相关性提供更精准且可解释的预测，同时减少了每个家族训练多个LLMs的需求。我们给出了关于参数识别的理论成果以及在12个重要基准（来自Open LLM Leaderboard v1/v2）上的实证评估，表明Sloth能高效预测LLM性能，并为诸如编码和情商应用等下游任务的缩放行为提供见解。

> Scaling laws for large language models (LLMs) predict model performance based on parameters like size and training data. However, differences in training configurations and data processing across model families lead to significant variations in benchmark performance, making it difficult for a single scaling law to generalize across all LLMs. On the other hand, training family-specific scaling laws requires training models of varying sizes for every family. In this work, we propose Skills Scaling Laws (SSLaws, pronounced as Sloth), a novel scaling law that leverages publicly available benchmark data and assumes LLM performance is driven by low-dimensional latent skills, such as reasoning and instruction following. These latent skills are influenced by computational resources like model size and training tokens but with varying efficiencies across model families. Sloth exploits correlations across benchmarks to provide more accurate and interpretable predictions while alleviating the need to train multiple LLMs per family. We present both theoretical results on parameter identification and empirical evaluations on 12 prominent benchmarks, from Open LLM Leaderboard v1/v2, demonstrating that Sloth predicts LLM performance efficiently and offers insights into scaling behaviors for downstream tasks such as coding and emotional intelligence applications.

[Arxiv](https://arxiv.org/abs/2412.06540)
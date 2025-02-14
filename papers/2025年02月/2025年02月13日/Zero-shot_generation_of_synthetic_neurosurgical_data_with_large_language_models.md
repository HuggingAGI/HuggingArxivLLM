# 基于大型语言模型的零样本合成神经外科数据生成

发布时间：2025年02月13日

`LLM应用` `神经外科` `临床研究`

> Zero-shot generation of synthetic neurosurgical data with large language models

# 摘要

> # 摘要
临床数据是推动神经外科研究的基础，但受限于数据可用性、样本量小、隐私法规以及资源密集型的预处理和去识别化流程，获取临床数据常常面临诸多挑战。合成数据为解决与真实世界数据 (RWD) 获取和使用相关的挑战提供了一种潜在的解决方案。本研究旨在通过与条件表格生成对抗网络 (CTGAN) 进行基准比较，评估大型语言模型 (LLM) GPT-4o 零-shot 生成合成神经外科数据的能力。合成数据集与真实世界神经外科数据进行了比较，以评估保真度（均值、比例、分布和二元相关性）、效用（基于 RWD 的 ML 分类器性能）以及隐私（从 RWD 中复制记录）。尽管 GPT-4o 未进行微调或使用 RWD 进行预训练，其生成的数据集在保真度上与 CTGAN 相当或更优。数据集在不直接暴露任何真实患者记录的情况下，对 RWD 的单变量和二变量保真度表现优异，即使在放大样本量时也是如此。在 GPT-4o 生成的数据上训练 ML 分类器，并在 RWD 上进行二元预测任务测试，结果显示 F1 分数为 0.706，与在 CTGAN 数据上训练（F1 分数 0.705）相比，对术后功能状态恶化的预测性能相当。GPT-4o 展现了生成高保真合成神经外科数据的潜力。这些发现还表明，使用 GPT-4o 合成的数据可以有效补充样本量较小的临床数据，并用于训练 ML 模型以预测神经外科手术结果。需要进一步研究以改进对分布特性的保留并提升分类器性能。


> Clinical data is fundamental to advance neurosurgical research, but access is often constrained by data availability, small sample sizes, privacy regulations, and resource-intensive preprocessing and de-identification procedures. Synthetic data offers a potential solution to challenges associated with accessing and using real-world data (RWD). This study aims to evaluate the capability of zero-shot generation of synthetic neurosurgical data with a large language model (LLM), GPT-4o, by benchmarking with the conditional tabular generative adversarial network (CTGAN). Synthetic datasets were compared to real-world neurosurgical data to assess fidelity (means, proportions, distributions, and bivariate correlations), utility (ML classifier performance on RWD), and privacy (duplication of records from RWD). The GPT-4o-generated datasets matched or exceeded CTGAN performance, despite no fine-tuning or access to RWD for pre-training. Datasets demonstrated high univariate and bivariate fidelity to RWD without directly exposing any real patient records, even at amplified sample size. Training an ML classifier on GPT-4o-generated data and testing on RWD for a binary prediction task showed an F1 score (0.706) with comparable performance to training on the CTGAN data (0.705) for predicting postoperative functional status deterioration. GPT-4o demonstrated a promising ability to generate high-fidelity synthetic neurosurgical data. These findings also indicate that data synthesized with GPT-4o can effectively augment clinical data with small sample sizes, and train ML models for prediction of neurosurgical outcomes. Further investigation is necessary to improve the preservation of distributional characteristics and boost classifier performance.

[Arxiv](https://arxiv.org/abs/2502.09566)
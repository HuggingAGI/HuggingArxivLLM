# # 仅解码器的大型语言模型中稀疏与密集检索的扩展

发布时间：2025年02月21日

`LLM理论` `信息检索` `问答系统`

> Scaling Sparse and Dense Retrieval in Decoder-Only LLMs

# 摘要

> # 摘要  
大型语言模型（LLMs）的扩展为提升检索模型性能带来了巨大潜力。然而，过去的研究主要聚焦于基于对比损失（CL）训练的密集检索，而对其他检索范式（如稀疏检索）和优化技术（如知识蒸馏（KD））的扩展行为关注较少。本研究系统性地探讨了不同检索范式（稀疏与密集）和微调目标（CL与KD及其组合）如何影响模型在不同规模下的检索性能。我们采用MS MARCO文档作为训练数据集，基于解码器的LLMs（Llama-3系列：1B、3B、8B参数量），并在固定计算预算下，评估了各种训练配置在内部（MS MARCO、TREC DL）和外部（BEIR）基准上的表现。研究发现：（1）只有在对比损失（CL）的训练下，模型的扩展行为才会显著体现出来，更大规模的模型能够获得显著的性能提升，而知识蒸馏（KD）训练的模型则几乎无改进，不同规模（1B、3B、8B）下的表现相似。（2）稀疏检索模型在内部（MS MARCO、TREC DL）和外部（BEIR）基准上均优于密集检索模型，并且对不完美的监督信号表现出更强的鲁棒性。（3）我们成功地在8B参数规模下将稀疏检索模型与对比损失（CL）和知识蒸馏（KD）损失相结合，取得了所有评估数据集上的最优性能（SOTA）。

> Scaling large language models (LLMs) has shown great potential for improving retrieval model performance; however, previous studies have mainly focused on dense retrieval trained with contrastive loss (CL), neglecting the scaling behavior of other retrieval paradigms and optimization techniques, such as sparse retrieval and knowledge distillation (KD). In this work, we conduct a systematic comparative study on how different retrieval paradigms (sparse vs. dense) and fine-tuning objectives (CL vs. KD vs. their combination) affect retrieval performance across different model scales. Using MSMARCO passages as the training dataset, decoder-only LLMs (Llama-3 series: 1B, 3B, 8B), and a fixed compute budget, we evaluate various training configurations on both in-domain (MSMARCO, TREC DL) and out-of-domain (BEIR) benchmarks. Our key findings reveal that: (1) Scaling behaviors emerge clearly only with CL, where larger models achieve significant performance gains, whereas KD-trained models show minimal improvement, performing similarly across the 1B, 3B, and 8B scales. (2) Sparse retrieval models consistently outperform dense retrieval across both in-domain (MSMARCO, TREC DL) and out-of-domain (BEIR) benchmarks, and they demonstrate greater robustness to imperfect supervised signals. (3) We successfully scale sparse retrieval models with the combination of CL and KD losses at 8B scale, achieving state-of-the-art (SOTA) results in all evaluation sets.

[Arxiv](https://arxiv.org/abs/2502.15526)
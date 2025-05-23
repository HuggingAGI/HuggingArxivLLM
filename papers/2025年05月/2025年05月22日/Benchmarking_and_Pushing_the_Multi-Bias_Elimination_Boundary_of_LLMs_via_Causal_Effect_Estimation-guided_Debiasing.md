# # 基准测试与优化
利用因果效应估计引导的去偏方法，我们对大型语言模型（LLMs）进行了基准测试，并致力于消除多偏见的边界。

发布时间：2025年05月22日

`LLM理论` `人工智能`

> Benchmarking and Pushing the Multi-Bias Elimination Boundary of LLMs via Causal Effect Estimation-guided Debiasing

# 摘要

> 尽管大型语言模型（LLMs）取得了显著进展，但近期研究表明，LLMs在推理过程中可能仍然利用偏见，导致其泛化能力不足。目前的研究通常通过包含一种受控偏见的数据来评估LLMs的泛化能力，但在实际应用中，一条数据可能包含多种偏见。为了解决这一问题，我们提出了一种多偏见基准，每条数据包含五种类型的偏见。评估结果显示，现有LLMs和去偏方法的表现不尽如人意，表明同时消除多种偏见极具挑战性。为应对这一挑战，我们提出了一种基于因果效应估计的多偏见消除方法（CMBE）。该方法首先同时估计多种偏见的因果效应，然后从推理过程中语义信息和偏见共同作用的总因果效应中消除偏见的影响。实验结果表明，CMBE能够有效同时消除多种偏见，显著提升LLMs的泛化能力。

> Despite significant progress, recent studies have indicated that current large language models (LLMs) may still utilize bias during inference, leading to the poor generalizability of LLMs. Some benchmarks are proposed to investigate the generalizability of LLMs, with each piece of data typically containing one type of controlled bias. However, a single piece of data may contain multiple types of biases in practical applications. To bridge this gap, we propose a multi-bias benchmark where each piece of data contains five types of biases. The evaluations conducted on this benchmark reveal that the performance of existing LLMs and debiasing methods is unsatisfying, highlighting the challenge of eliminating multiple types of biases simultaneously. To overcome this challenge, we propose a causal effect estimation-guided multi-bias elimination method (CMBE). This method first estimates the causal effect of multiple types of biases simultaneously. Subsequently, we eliminate the causal effect of biases from the total causal effect exerted by both the semantic information and biases during inference. Experimental results show that CMBE can effectively eliminate multiple types of bias simultaneously to enhance the generalizability of LLMs.

[Arxiv](https://arxiv.org/abs/2505.16522)
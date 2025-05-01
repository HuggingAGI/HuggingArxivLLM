# 大语言模型评估中的信心：基于贝叶斯方法的小样本挑战解决方案

发布时间：2025年04月30日

`LLM理论` `模型评估` `模型测试`

> Confidence in Large Language Model Evaluation: A Bayesian Approach to Limited-Sample Challenges

# 摘要

> 大型语言模型 (LLMs) 具有概率输出特性，而传统评估框架依赖于确定性的标量指标。本研究提出了一种基于贝叶斯方法的 LLM 能力评估框架，通过概率推理整合先验知识，从而在小样本场景下克服了传统方法的局限性。我们将模型能力视为潜在变量，并利用经过筛选的查询集来引发区分性响应，从而将模型排名形式化为一个关于互斥能力区间的贝叶斯假设检验问题。实验评估表明，与传统评估方法相比，本方法在 GPT 系列模型上实现了更优的区分能力。结果表明，即使在样本量减少的情况下，该方法仍能保持统计上的稳健性，并提供可操作的见解，例如关于模型超越特定基线的可能性的概率陈述。这项工作通过将贝叶斯推理与实际部署场景中的现实约束相结合，推动了 LLM 评估方法的发展。

> Large language models (LLMs) exhibit probabilistic output characteristics, yet conventional evaluation frameworks rely on deterministic scalar metrics. This study introduces a Bayesian approach for LLM capability assessment that integrates prior knowledge through probabilistic inference, addressing limitations under limited-sample regimes. By treating model capabilities as latent variables and leveraging a curated query set to induce discriminative responses, we formalize model ranking as a Bayesian hypothesis testing problem over mutually exclusive capability intervals. Experimental evaluations with GPT-series models demonstrate that the proposed method achieves superior discrimination compared to conventional evaluation methods. Results indicate that even with reduced sample sizes, the approach maintains statistical robustness while providing actionable insights, such as probabilistic statements about a model's likelihood of surpassing specific baselines. This work advances LLM evaluation methodologies by bridging Bayesian inference with practical constraints in real-world deployment scenarios.

[Arxiv](https://arxiv.org/abs/2504.21303)
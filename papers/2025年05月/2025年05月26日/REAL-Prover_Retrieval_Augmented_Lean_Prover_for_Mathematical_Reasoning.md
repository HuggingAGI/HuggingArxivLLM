# REAL证明器：检索增强的精简证明器，用于数学推理

发布时间：2025年05月26日

`LLM应用` `形式化定理证明器`

> REAL-Prover: Retrieval Augmented Lean Prover for Mathematical Reasoning

# 摘要

> 当前，形式化定理证明器在高中及竞赛级别的数学领域取得了显著进展，但向更高等数学领域的推广却鲜有突破。本文介绍的 REAL-Prover 是一个为 Lean 4 开发的新开源分步定理证明器，旨在拓展这一技术边界。该证明器结合了我们微调的大型语言模型（REAL-Prover-v1）与检索系统（Leansearch-PS），在解决大学水平数学问题时表现出色。为了训练 REAL-Prover-v1，我们开发了 HERALD-AF 数据提取管道，用于将自然语言数学问题转化为正式陈述，并创建了开源 Lean 4 交互环境（Jixia-interactive）以支持合成数据收集。实验结果显示，仅通过监督微调，我们的证明器在 ProofNet 数据集上取得了 23.7% 的成功率（Pass@64），与当前最优模型（SOTA）持平。为评估其性能，我们推出了专注于代数问题的新基准 FATE-M，我们的证明器在该基准上达到了 56.7% 的成功率（Pass@64），创下了当前最优记录。

> Nowadays, formal theorem provers have made monumental progress on high-school and competition-level mathematics, but few of them generalize to more advanced mathematics. In this paper, we present REAL-Prover, a new open-source stepwise theorem prover for Lean 4 to push this boundary. This prover, based on our fine-tuned large language model (REAL-Prover-v1) and integrated with a retrieval system (Leansearch-PS), notably boosts performance on solving college-level mathematics problems. To train REAL-Prover-v1, we developed HERALD-AF, a data extraction pipeline that converts natural language math problems into formal statements, and a new open-source Lean 4 interactive environment (Jixia-interactive) to facilitate synthesis data collection. In our experiments, our prover using only supervised fine-tune achieves competitive results with a 23.7% success rate (Pass@64) on the ProofNet dataset-comparable to state-of-the-art (SOTA) models. To further evaluate our approach, we introduce FATE-M, a new benchmark focused on algebraic problems, where our prover achieves a SOTA success rate of 56.7% (Pass@64).

[Arxiv](https://arxiv.org/abs/2505.20613)
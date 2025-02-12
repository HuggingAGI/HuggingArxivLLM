# Goedel-Prover：一个前沿开源自动定理证明模型

发布时间：2025年02月11日

`LLM应用` `形式化证明`

> Goedel-Prover: A Frontier Model for Open-Source Automated Theorem Proving

# 摘要

> 我们很高兴推出Goedel-Prover，一个开源大型语言模型（LLM），在数学问题的自动化形式化证明生成领域达到了当前最优性能。面对形式化数学陈述和证明稀缺这一关键挑战，我们采取了以下创新方法。首先，我们训练了陈述形式化器，将Numina中的自然语言数学问题转化为形式语言（Lean 4），构建了一个包含164万个形式化陈述的数据集。通过LLMs验证这些形式化陈述是否忠实保留了原始自然语言问题的核心内容。接着，我们迭代训练了一系列证明器，逐步构建了一个庞大的形式化证明数据集。每个新证明器都能攻克前一个证明器无法解决的难题，这些新增的证明被纳入下一个证明器的训练素材。最终，Goedel-Prover在整体证明生成能力上超越了所有现有的开源模型。在miniF2F基准测试中，其成功率达到了57.6%（Pass@32），比之前的最佳开源模型高出7.6%。在PutnamBench上，Goedel-Prover成功解决了7个问题（Pass@512），荣登排行榜榜首。此外，它为LeanWorkbook问题生成了29.7万个形式化证明，几乎是早期作品15.7万的两倍。Goedel-Prover不仅在性能上取得了突破，更在形式化证明领域树立了新的标杆。

> We introduce Goedel-Prover, an open-source large language model (LLM) that achieves the state-of-the-art (SOTA) performance in automated formal proof generation for mathematical problems. The key challenge in this field is the scarcity of formalized math statements and proofs, which we tackle in the following ways. We train statement formalizers to translate the natural language math problems from Numina into formal language (Lean 4), creating a dataset of 1.64 million formal statements. LLMs are used to check that the formal statements accurately preserve the content of the original natural language problems. We then iteratively build a large dataset of formal proofs by training a series of provers. Each prover succeeds in proving many statements that the previous ones could not, and these new proofs are added to the training set for the next prover. The final prover outperforms all existing open-source models in whole-proof generation. On the miniF2F benchmark, it achieves a 57.6% success rate (Pass@32), exceeding the previous best open-source model by 7.6%. On PutnamBench, Goedel-Prover successfully solves 7 problems (Pass@512), ranking first on the leaderboard. Furthermore, it generates 29.7K formal proofs for Lean Workbook problems, nearly doubling the 15.7K produced by earlier works.

[Arxiv](https://arxiv.org/abs/2502.07640)
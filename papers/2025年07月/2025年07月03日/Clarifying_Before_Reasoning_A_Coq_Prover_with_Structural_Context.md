# # 先澄清，再推理：基于结构上下文的Coq证明器

发布时间：2025年07月03日

`LLM应用` `形式化方法`

> Clarifying Before Reasoning: A Coq Prover with Structural Context

# 摘要

> 本研究旨在探索提升任务清晰度能否增强大型语言模型的推理能力，特别是在Coq定理证明领域。我们提出了一个概念级别的评估指标，并发现为现代LLMs的标准输入添加结构化语义上下文，可使清晰度得分提升1.85倍（从44.5%提升至82.3%）。基于通用模型	exttt{DeepSeek-V3}，我们的方法使证明成功率提升2.1倍（从21.8%提升至45.8%），超越了先前的最先进方法	exttt{Graph2Tac}（33.2%）。我们在15个标准Coq包中随机选取的1,386个定理上进行了评估，采用了与	exttt{Graph2Tac}相同的评估协议。此外，通过在我们的结构化数据上微调较小规模的模型，可以实现更高的性能（48.6%）。我们的方法通过选择性概念展开丰富任务描述，并采用规划器--执行器架构。这些发现凸显了结构化任务表示在连接理解与推理中的关键作用。

> In this work, we investigate whether improving task clarity can enhance reasoning ability of large language models, focusing on theorem proving in Coq. We introduce a concept-level metric to evaluate task clarity and show that adding structured semantic context to the standard input used by modern LLMs, leads to a 1.85$\times$ improvement in clarity score (44.5\%~$\rightarrow$~82.3\%). Using the general-purpose model \texttt{DeepSeek-V3}, our approach leads to a 2.1$\times$ improvement in proof success (21.8\%~$\rightarrow$~45.8\%) and outperforms the previous state-of-the-art \texttt{Graph2Tac} (33.2\%). We evaluate this on 1,386 theorems randomly sampled from 15 standard Coq packages, following the same evaluation protocol as \texttt{Graph2Tac}. Furthermore, fine-tuning smaller models on our structured data can achieve even higher performance (48.6\%). Our method uses selective concept unfolding to enrich task descriptions, and employs a Planner--Executor architecture. These findings highlight the value of structured task representations in bridging the gap between understanding and reasoning.

[Arxiv](https://arxiv.org/abs/2507.02541)
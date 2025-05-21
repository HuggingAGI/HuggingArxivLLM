# JOLT-SQL: 结合混淆感知噪声模式采样的文本到SQL联合损失调优

发布时间：2025年05月20日

`LLM应用` `数据库`

> JOLT-SQL: Joint Loss Tuning of Text-to-SQL with Confusion-aware Noisy Schema Sampling

# 摘要

> 文本到SQL（Text-to-SQL）借助大型语言模型（LLMs）的最新发展取得了长足进步。尽管LLMs为这一任务提供了多种方法，包括提示工程和监督微调（SFT），但SFT方法仍面临复杂多阶段管道和对噪声模式信息鲁棒性差的挑战。为解决这些问题，我们提出了JOLT-SQL，这是一个经过精简的单阶段SFT框架，通过统一损失函数同时优化模式关联和SQL生成。JOLT-SQL采用判别式模式关联，并通过局部双向注意力机制进行增强，同时结合一种混淆感知的噪声模式采样策略，通过选择性注意力机制提升噪声模式条件下的鲁棒性。在Spider和BIRD基准测试上的实验表明，与同规模开源模型相比，JOLT-SQL在执行精度上达到前沿水平，同时显著提升了训练和推理效率。

> Text-to-SQL, which maps natural language to SQL queries, has benefited greatly from recent advances in Large Language Models (LLMs). While LLMs offer various paradigms for this task, including prompting and supervised fine-tuning (SFT), SFT approaches still face challenges such as complex multi-stage pipelines and poor robustness to noisy schema information. To address these limitations, we present JOLT-SQL, a streamlined single-stage SFT framework that jointly optimizes schema linking and SQL generation via a unified loss. JOLT-SQL employs discriminative schema linking, enhanced by local bidirectional attention, alongside a confusion-aware noisy schema sampling strategy with selective attention to improve robustness under noisy schema conditions. Experiments on the Spider and BIRD benchmarks demonstrate that JOLT-SQL achieves state-of-the-art execution accuracy among comparable-size open-source models, while significantly improving both training and inference efficiency.

[Arxiv](https://arxiv.org/abs/2505.14305)
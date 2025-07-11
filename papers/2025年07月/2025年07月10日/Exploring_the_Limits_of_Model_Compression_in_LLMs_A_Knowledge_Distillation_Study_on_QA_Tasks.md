# 探索 LLM 模型压缩的极限：基于知识蒸馏的问答任务研究

发布时间：2025年07月10日

`LLM应用` `知识图谱` `问答系统`

> Exploring the Limits of Model Compression in LLMs: A Knowledge Distillation Study on QA Tasks

# 摘要

> <翻译失败>

> Large Language Models (LLMs) have demonstrated outstanding performance across a range of NLP tasks, however, their computational demands hinder their deployment in real-world, resource-constrained environments. This work investigates the extent to which LLMs can be compressed using Knowledge Distillation (KD) while maintaining strong performance on Question Answering (QA) tasks. We evaluate student models distilled from the Pythia and Qwen2.5 families on two QA benchmarks, SQuAD and MLQA, under zero-shot and one-shot prompting conditions. Results show that student models retain over 90% of their teacher models' performance while reducing parameter counts by up to 57.1%. Furthermore, one-shot prompting yields additional performance gains over zero-shot setups for both model families. These findings underscore the trade-off between model efficiency and task performance, demonstrating that KD, combined with minimal prompting, can yield compact yet capable QA systems suitable for resource-constrained applications.

[Arxiv](https://arxiv.org/abs/2507.07630)
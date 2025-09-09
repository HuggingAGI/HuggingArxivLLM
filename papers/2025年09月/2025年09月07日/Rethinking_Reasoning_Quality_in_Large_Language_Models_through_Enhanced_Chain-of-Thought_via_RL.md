# # 通过强化学习（RL）增强思维链重新审视大型语言模型的推理质量

发布时间：2025年09月07日

`强化学习` `基础理论`

> Rethinking Reasoning Quality in Large Language Models through Enhanced Chain-of-Thought via RL

# 摘要

> 强化学习（RL）如今已成为提升大型语言模型（LLMs）推理能力的主流方法。然而，在数学或编程基准测试中，常用的基于规则的奖励函数仅关注答案的格式与正确性，却无法判断诱导出的思维链（CoT）是否真的提升了答案质量。此外，这种任务特定的训练对逻辑深度的调控能力有限，因而难以展现模型真实的推理水平。为此，我们提出动态推理效率奖励（DRER）——一个即插即用的强化学习奖励框架，能够同时重塑奖励信号与优势信号。（i）推理质量奖励会为那些能显著提高正确答案概率的推理链赋予细粒度的奖励，直接激励包含有益CoT标记的推理路径。（ii）动态长度优势则会削弱长度偏离验证阈值的响应的优势，以此稳定训练过程。为支持严格评估，我们还发布了Logictree数据集——一个动态构建的演绎推理数据集，既可作为强化学习的训练数据，也可充当综合基准。实验结果验证了DRER的有效性：我们的7B模型仅需400步训练，就在Logictree上达到了GPT-o3-mini的性能水平，且CoT增强答案的平均置信度提升了30%。该模型还能在多种逻辑推理数据集及数学基准AIME24上展现出良好的泛化性能。这些结果揭示了强化学习如何塑造CoT行为，并为提升大型语言模型的形式推理能力提供了切实可行的方案。所有代码与数据已开源至仓库https://github.com/Henryhe09/DRER。

> Reinforcement learning (RL) has recently become the dominant paradigm for strengthening the reasoning abilities of large language models (LLMs). Yet the rule-based reward functions commonly used on mathematical or programming benchmarks assess only answer format and correctness, providing no signal as to whether the induced Chain-of-Thought (CoT) actually improves the answer. Furthermore, such task-specific training offers limited control over logical depth and therefore may fail to reveal a model's genuine reasoning capacity. We propose Dynamic Reasoning Efficiency Reward (DRER) -- a plug-and-play RL reward framework that reshapes both reward and advantage signals. (i) A Reasoning Quality Reward assigns fine-grained credit to those reasoning chains that demonstrably raise the likelihood of the correct answer, directly incentivising the trajectories with beneficial CoT tokens. (ii) A Dynamic Length Advantage decays the advantage of responses whose length deviates from a validation-derived threshold, stabilising training. To facilitate rigorous assessment, we also release Logictree, a dynamically constructed deductive reasoning dataset that functions both as RL training data and as a comprehensive benchmark. Experiments confirm the effectiveness of DRER: our 7B model attains GPT-o3-mini level performance on Logictree with 400 trianing steps, while the average confidence of CoT-augmented answers rises by 30%. The model further exhibits generalisation across diverse logical-reasoning datasets, and the mathematical benchmark AIME24. These results illuminate how RL shapes CoT behaviour and chart a practical path toward enhancing formal-reasoning skills in large language models. All code and data are available in repository https://github.com/Henryhe09/DRER.

[Arxiv](https://arxiv.org/abs/2509.06024)
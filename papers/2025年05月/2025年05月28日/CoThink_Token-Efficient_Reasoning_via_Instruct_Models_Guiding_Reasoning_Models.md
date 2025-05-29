# CoThink：通过指令模型引导推理模型实现高效利用Token的推理

发布时间：2025年05月28日

`LLM理论` `人工智能`

> CoThink: Token-Efficient Reasoning via Instruct Models Guiding Reasoning Models

# 摘要

> 大型语言模型（LLMs）在推理时的性能扩展现象中受益，这一现象被称为推理时的缩放现象。然而，推理优化的模型在处理简单问题时常常陷入过度思考，生成冗长的输出，导致token效率低下。通过对比同等规模的指令模型，我们发现导致这种冗长现象的两个关键原因：（1）强化学习降低了正向推理的信息密度，（2）反向链式思维训练鼓励冗余且通常不必要的验证步骤。由于LLMs无法判断问题难度，它们往往在所有任务中都采用相同的谨慎推理策略，导致低效的过度思考。为了解决这一问题，我们提出了CoThink，一个极为简单的管道：指令模型首先起草高级解决方案大纲，推理模型随后详细解决。我们发现，CoThink可以根据输入难度动态调整推理深度。在DAPO、DeepSeek-R1和QwQ三个推理模型上，使用GSM8K、MATH500和AIME24三个数据集进行评估，CoThink在平均通过@1准确率仅下降0.42%的情况下，将总生成token数减少了22.3%。与指令模型相比，我们正式定义了推理效率，并在LLMs中观察到潜在的推理效率扩展定律。

> Large language models (LLMs) benefit from increased test-time compute, a phenomenon known as test-time scaling. However, reasoning-optimized models often overthink even simple problems, producing excessively verbose outputs and leading to low token efficiency. By comparing these models with equally sized instruct models, we identify two key causes of this verbosity: (1) reinforcement learning reduces the information density of forward reasoning, and (2) backward chain-of thought training encourages redundant and often unnecessary verification steps. Since LLMs cannot assess the difficulty of a given problem, they tend to apply the same cautious reasoning strategy across all tasks, resulting in inefficient overthinking. To address this, we propose CoThink, an embarrassingly simple pipeline: an instruct model first drafts a high-level solution outline; a reasoning model then works out the solution. We observe that CoThink enables dynamic adjustment of reasoning depth based on input difficulty. Evaluated with three reasoning models DAPO, DeepSeek-R1, and QwQ on three datasets GSM8K, MATH500, and AIME24, CoThink reduces total token generation by 22.3% while maintaining pass@1 accuracy within a 0.42% margin on average. With reference to the instruct model, we formally define reasoning efficiency and observe a potential reasoning efficiency scaling law in LLMs.

[Arxiv](https://arxiv.org/abs/2505.22017)
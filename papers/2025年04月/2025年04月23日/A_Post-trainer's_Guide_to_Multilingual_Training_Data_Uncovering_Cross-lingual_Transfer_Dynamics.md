# 多语言训练数据指南：后训练视角下的跨语言迁移机制探秘

发布时间：2025年04月23日

`LLM理论` `机器翻译`

> A Post-trainer's Guide to Multilingual Training Data: Uncovering Cross-lingual Transfer Dynamics

# 摘要

> 为了让大型语言模型在全球范围内发挥作用，它们根据多语言数据进行了微调以遵循指令。尽管这种后训练微调普遍存在，但跨语言迁移的动态机制仍然不明确。本研究探讨了跨语言迁移（CLT）在现实后训练设置中的动态机制。我们研究了两个模型家族，参数规模高达350亿，这些模型在精心控制的多语言数据混合上进行训练，并在摘要、遵循指令和数学推理这三个复杂程度不同的生成任务中进行测试，涵盖单任务和多任务指令微调设置。总体而言，跨语言迁移和多语言性能的动态机制无法通过孤立变量解释，而是取决于后训练设置的组合。最后，我们确定了在实际中实现有效跨语言迁移的条件。

> In order for large language models to be useful across the globe, they are fine-tuned to follow instructions on multilingual data. Despite the ubiquity of such post-training, a clear understanding of the dynamics that enable cross-lingual transfer remains elusive. This study examines cross-lingual transfer (CLT) dynamics in realistic post-training settings. We study two model families of up to 35B parameters in size trained on carefully controlled mixtures of multilingual data on three generative tasks with varying levels of complexity (summarization, instruction following, and mathematical reasoning) in both single-task and multi-task instruction tuning settings. Overall, we find that the dynamics of cross-lingual transfer and multilingual performance cannot be explained by isolated variables, varying depending on the combination of post-training settings. Finally, we identify the conditions that lead to effective cross-lingual transfer in practice.

[Arxiv](https://arxiv.org/abs/2504.16677)
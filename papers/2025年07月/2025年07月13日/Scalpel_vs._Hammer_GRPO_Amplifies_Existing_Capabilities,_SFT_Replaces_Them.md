# 手术刀 vs. 锤子：GRPO 增强现有能力，SFT 取代它们

发布时间：2025年07月13日

`LLM理论

理由：该论文探讨了强化学习（RL）和监督微调（SFT）对大型语言模型（LLM）推理能力的影响，分析了模型参数的变化及其对不同任务表现的影响。研究属于对LLM训练方法和机制的理论分析，因此归类为LLM理论。` `学术研究`

> Scalpel vs. Hammer: GRPO Amplifies Existing Capabilities, SFT Replaces Them

# 摘要

> 数学和代码数据集的引入使LLM的推理能力训练成为后训练阶段的重要研究方向。在众多方法中，强化学习（RL）和监督微调（SFT）备受关注，但它们的训练动态仍待深入研究。我们采用相同模型架构和相似超参数，对同一数学问题进行了RL和SFT的对比分析。研究发现，RL在数学任务中带来轻微性能提升，但在MMLU等知识密集型基准测试中表现略有下降，而SFT的这些趋势则更加显著。通过分析模型参数的变化，我们发现两种算法均主要修改了查询和键权重，同时SFT展现出更大的参数更新幅度，并对中间层MLP产生更大影响，这可能导致了其在知识密集型任务中的性能下降。因此，我们探索了在训练过程中冻结部分模型参数是否能缓解这一问题，但实验结果尚不明确，仅在GPQA:Diamond基准测试中观察到性能提升，而在其他基准测试中则出现性能下降。综上所述，我们的研究结果初步揭示了为何RL能够放大现有能力，而SFT则倾向于用新技能取代旧技能。

> Training large language models (LLMs) for reasoning via maths and code datasets has become a major new focus in LLM post-training. Two particularly popular approaches are reinforcement learning (RL) and supervised fine-tuning (SFT), but their training dynamics are poorly understood. We present a comparative analysis of RL and SFT on the same maths problems with the same model and similar hyperparameters. We find that RL yields minor in-domain gains on maths and slight degradation on knowledge-intensive benchmarks like MMLU, while both trends are more pronounced in SFT. We also analyse model parameters across checkpoints, observing that both algorithms modify query and key weights the most. Meanwhile, SFT exhibits greater updates and also affects mid-layer MLPs more, leading us to hypothesise that this may have caused the out-of-domain degradation. We therefore investigate whether freezing parts of the model during training can mitigate the reduced performance on knowledge-intensive benchmarks. However, our results are inconclusive, with benefits on GPQA:Diamond and degradation on other benchmarks. Taken together, our observations provide a preliminary indication for why RL amplifies existing capabilities, while SFT replaces old skills with new ones.

[Arxiv](https://arxiv.org/abs/2507.10616)
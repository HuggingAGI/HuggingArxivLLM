# 本研究聚焦于深入分析并有效缓解参数高效微调过程中的灾难性遗忘现象。

发布时间：2024年02月29日

`LLM理论`

> Analyzing and Reducing Catastrophic Forgetting in Parameter Efficient Tuning

# 摘要

> 研究显示，LLMs在语义解析与生成上展现非凡实力，但当它们不断针对复杂多元的特定领域下游任务进行微调时，对过往任务的推断能力会出现戏剧性下滑，这就是著名的灾难性遗忘问题。在此背景下，学习的灵活性与记忆稳定性间需寻得一种微妙平衡。尽管已有多项研究尝试使用如记忆回放、正则化及参数隔离等策略解决这个问题，但在LLMs连续微调过程中各类邻近极小值之间的几何关联却鲜有深入探讨。本工作创新性地通过模式连通性的透镜，揭示了不同极小值可通过低损失谷相互连接的几何关系。经大规模实验证明，在LLMs持续学习情境下确实存在模式连通现象，这种现象有助于实现灵活与稳定间的和谐共生。基于上述发现，我们创新提出了简洁高效的I-LoRA方法，该方法利用LoRA参数插值技术构造出双重内存经验回放框架。在八大特定领域的CL基准测试中，I-LoRA展现出稳健且显著的性能提升，较之前最先进的方法提升了高达$11\%$的性能，从而为后续大型语言模型持续学习问题的研究树立了坚实基线，并提供了富有洞察力的方向。您可访问网址<https://github.com/which47/LLMCL>获取我们的源代码。

> Existing research has shown that large language models (LLMs) exhibit remarkable performance in language understanding and generation. However, when LLMs are continuously fine-tuned on complex and diverse domain-specific downstream tasks, the inference performance on historical tasks decreases dramatically, which is known as a catastrophic forgetting problem. A trade-off needs to be kept between learning plasticity and memory stability. Plenty of existing works have explored strategies like memory replay, regularization and parameter isolation, but little is known about the geometric connection of various adjacent minima in the continual LLMs fine-tuning scenarios. In this work, we investigate the geometric connections of different minima through the lens of mode connectivity, which means different minima can be connected by a low-loss valley. Through extensive experiments, we uncover the mode connectivity phenomenon in the LLMs continual learning scenario and find that it can strike a balance between plasticity and stability. Building upon these findings, we propose a simple yet effective method called Interpolation-based LoRA (I-LoRA), which constructs a dual-memory experience replay framework based on LoRA parameter interpolations. Extensive experiments and analysis on eight domain-specific CL benchmarks demonstrate that I-LoRA consistently show significant improvement over the previous state-of-the-art approaches with up to $11\%$ performance gains, providing a strong baseline and insights for future research on the large language model continual learning problem. Our code is available at \url{https://github.com/which47/LLMCL}.

[Arxiv](https://arxiv.org/abs/2402.18865)
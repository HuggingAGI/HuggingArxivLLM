# AdaR1：通过双层自适应推理优化，从长链思维到混合思维

发布时间：2025年04月30日

`LLM应用` `人工智能`

> AdaR1: From Long-CoT to Hybrid-CoT via Bi-Level Adaptive Reasoning Optimization

# 摘要

> 近年来，长思考推理模型在复杂推理任务中表现出色，但效率问题也随之而来。我们的研究发现，Long-CoT模型的效果因问题而异：某些问题需要复杂推理，而另一些问题则无明显提升，甚至准确率下降。这促使我们开发了一种自适应推理策略，根据输入调整推理深度。然而，现有研究主要集中在减少长推理路径内的冗余，限制了更高效策略的探索。为此，我们提出了一种新型两阶段框架，用于自适应和高效的推理。首先，我们构建了一个混合推理模型，通过合并长推理和短推理的CoT模型，支持多样化的推理风格。其次，我们应用双级偏好训练，指导模型在组级别选择合适的推理风格，并在每个风格组内偏好简洁且正确的推理。实验结果表明，与其它基线方法相比，我们的方法显著降低了推理成本，同时保持了性能。值得注意的是，在五个数学数据集上，推理的平均长度减少了50%以上，充分展现了自适应策略在优化大型语言模型推理效率方面的潜力。我们的代码即将发布在https://github.com/StarDewXXX/AdaR1

> Recently, long-thought reasoning models achieve strong performance on complex reasoning tasks, but often incur substantial inference overhead, making efficiency a critical concern. Our empirical analysis reveals that the benefit of using Long-CoT varies across problems: while some problems require elaborate reasoning, others show no improvement, or even degraded accuracy. This motivates adaptive reasoning strategies that tailor reasoning depth to the input. However, prior work primarily reduces redundancy within long reasoning paths, limiting exploration of more efficient strategies beyond the Long-CoT paradigm. To address this, we propose a novel two-stage framework for adaptive and efficient reasoning. First, we construct a hybrid reasoning model by merging long and short CoT models to enable diverse reasoning styles. Second, we apply bi-level preference training to guide the model to select suitable reasoning styles (group-level), and prefer concise and correct reasoning within each style group (instance-level). Experiments demonstrate that our method significantly reduces inference costs compared to other baseline approaches, while maintaining performance. Notably, on five mathematical datasets, the average length of reasoning is reduced by more than 50%, highlighting the potential of adaptive strategies to optimize reasoning efficiency in large language models. Our code is coming soon at https://github.com/StarDewXXX/AdaR1

[Arxiv](https://arxiv.org/abs/2504.21659)
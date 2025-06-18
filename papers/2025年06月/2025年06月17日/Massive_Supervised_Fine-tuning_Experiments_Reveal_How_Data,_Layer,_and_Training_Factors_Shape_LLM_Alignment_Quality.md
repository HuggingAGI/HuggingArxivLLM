# 大规模监督微调实验揭示数据、层和训练因素如何塑造LLM对齐质量

发布时间：2025年06月17日

`LLM理论` `人工智能`

> Massive Supervised Fine-tuning Experiments Reveal How Data, Layer, and Training Factors Shape LLM Alignment Quality

# 摘要

> 监督微调（SFT）是将大型语言模型（LLMs）与人类指令和价值观对齐的关键步骤，但其许多方面仍不为人知。我们在代码生成、数学推理和通用领域任务等多样化数据集上训练了多种基模型，在受控条件下得到了1,000多个SFT模型。我们发现，某些训练任务协同作用在所有模型中普遍存在，而另一些则因模型而异，凸显了制定模型特定策略的重要性。此外，我们发现困惑度（perplexity）是预测SFT有效性的可靠指标，且中间层权重变化与性能提升的相关性最强。我们将开放这些SFT模型和基准测试结果，以推动进一步研究。

> Supervised fine-tuning (SFT) is a critical step in aligning large language models (LLMs) with human instructions and values, yet many aspects of SFT remain poorly understood. We trained a wide range of base models on a variety of datasets including code generation, mathematical reasoning, and general-domain tasks, resulting in 1,000+ SFT models under controlled conditions. We then identified the dataset properties that matter most and examined the layer-wise modifications introduced by SFT. Our findings reveal that some training-task synergies persist across all models while others vary substantially, emphasizing the importance of model-specific strategies. Moreover, we demonstrate that perplexity consistently predicts SFT effectiveness--often surpassing superficial similarity between trained data and benchmark--and that mid-layer weight changes correlate most strongly with performance gains. We will release these 1,000+ SFT models and benchmark results to accelerate further research.

[Arxiv](https://arxiv.org/abs/2506.14681)
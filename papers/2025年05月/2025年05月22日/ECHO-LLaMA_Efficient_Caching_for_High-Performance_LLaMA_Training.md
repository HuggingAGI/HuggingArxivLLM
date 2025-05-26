# ECHO-LLaMA：用于高性能 LLaMA 训练的高效缓存

发布时间：2025年05月22日

`LLM应用` `人工智能` `云计算`

> ECHO-LLaMA: Efficient Caching for High-Performance LLaMA Training

# 摘要

> 本文推出了ECHO-LLaMA，一种高效的LLaMA架构，旨在在不牺牲学习能力的前提下，显著提升LLaMA模型的训练速度和推理吞吐量。ECHO-LLaMA通过将模型转换为跨层共享KV缓存的方式，显著降低了KV计算复杂度，同时保持或提升了语言性能。实验数据显示，ECHO-LLaMA在训练过程中，每秒处理的token数量比基线提升了77%，模型FLOPs利用率（MFU）提升了16%，且在相同训练数据量下，损失降低了14%。此外，在1.1B模型中，ECHO-LLaMA的测试吞吐量比基线高出约7%。通过引入一种计算高效的自适应机制，ECHO-LLaMA为大型语言模型的预训练和微调提供了一种可扩展且经济高效的解决方案，使训练过程更快、资源消耗更低，同时保持了性能不妥协。

> This paper introduces ECHO-LLaMA, an efficient LLaMA architecture designed to improve both the training speed and inference throughput of LLaMA architectures while maintaining its learning capacity. ECHO-LLaMA transforms LLaMA models into shared KV caching across certain layers, significantly reducing KV computational complexity while maintaining or improving language performance. Experimental results demonstrate that ECHO-LLaMA achieves up to 77\% higher token-per-second throughput during training, up to 16\% higher Model FLOPs Utilization (MFU), and up to 14\% lower loss when trained on an equal number of tokens. Furthermore, on the 1.1B model, ECHO-LLaMA delivers approximately 7\% higher test-time throughput compared to the baseline. By introducing a computationally efficient adaptation mechanism, ECHO-LLaMA offers a scalable and cost-effective solution for pretraining and finetuning large language models, enabling faster and more resource-efficient training without compromising performance.

[Arxiv](https://arxiv.org/abs/2505.17331)
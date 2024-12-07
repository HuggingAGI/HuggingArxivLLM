# 预训练、对齐与解耦：借助大型语言模型为序列推荐增添动力

发布时间：2024年12月05日

`LLM应用` `推荐系统`

> Pre-train, Align, and Disentangle: Empowering Sequential Recommendation with Large Language Models

# 摘要

> 顺序推荐（SR）旨在对用户历史交互中的顺序依赖关系进行建模，从而更好地捕捉其不断变化的兴趣。然而，现有的 SR 方法主要依赖协作数据，这就带来了像冷启动问题和性能欠佳等局限。同时，尽管大型语言模型（LLMs）成果斐然，但它们在工业推荐系统中的应用却因高推理延迟、无法捕获全部分布统计数据以及灾难性遗忘而受阻。为此，我们提出了一种全新的预训练、对齐和解缠（PAD）范式，为推荐模型赋予 LLMs 的能力。具体而言，我们先对 SR 和 LLM 模型进行预训练，获取协作和文本嵌入。接着，利用带有高斯核的多核最大均值差异提出了一种以特征推荐为锚定的对齐损失。最后，由对齐和特定模态的专家构成的具有解缠嵌入的三重专家架构以频率感知的方式进行微调。在三个公共数据集上开展的实验证实了 PAD 的有效性，展现出显著的提升，并与各类 SR 骨干模型兼容，在冷项目上尤其如此。实现代码和数据集将会公开。

> Sequential recommendation (SR) aims to model the sequential dependencies in users' historical interactions to better capture their evolving interests. However, existing SR approaches primarily rely on collaborative data, which leads to limitations such as the cold-start problem and sub-optimal performance. Meanwhile, despite the success of large language models (LLMs), their application in industrial recommender systems is hindered by high inference latency, inability to capture all distribution statistics, and catastrophic forgetting. To this end, we propose a novel Pre-train, Align, and Disentangle (PAD) paradigm to empower recommendation models with LLMs. Specifically, we first pre-train both the SR and LLM models to get collaborative and textual embeddings. Next, a characteristic recommendation-anchored alignment loss is proposed using multi-kernel maximum mean discrepancy with Gaussian kernels. Finally, a triple-experts architecture, consisting aligned and modality-specific experts with disentangled embeddings, is fine-tuned in a frequency-aware manner. Experiments conducted on three public datasets demonstrate the effectiveness of PAD, showing significant improvements and compatibility with various SR backbone models, especially on cold items. The implementation code and datasets will be publicly available.

[Arxiv](https://arxiv.org/abs/2412.04107)
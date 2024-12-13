# 表征是否重要？探寻大型语言模型里的中间层

发布时间：2024年12月12日

`LLM理论` `模型架构`

> Does Representation Matter? Exploring Intermediate Layers in Large Language Models

# 摘要

> 理解大型语言模型（LLMs）中良好表示的定义，对于理论理解和实际应用都至关重要。在本文中，我们探究了包括 Transformer 和状态空间模型（SSMs）等各种 LLM 架构中的中间表示质量。我们发现，中间层往往比最终层能为下游任务提供更具信息量的表示。为衡量表示质量，我们改编并应用了一系列指标，如提示熵、曲率和增强不变性等，这些指标最初是在其他情境中提出的。我们的实证研究揭示了显著的架构差异、表示在整个训练过程中的演变情况，以及输入随机性和提示长度等因素对每一层的影响。尤为值得注意的是，我们在某些中间层的熵中观察到了双峰模式，并思考了与训练数据相关的潜在解释。总体而言，我们的研究结果阐明了 LLM 的内部机制，为架构优化和训练策略提供了指导。

> Understanding what defines a good representation in large language models (LLMs) is fundamental to both theoretical understanding and practical applications. In this paper, we investigate the quality of intermediate representations in various LLM architectures, including Transformers and State Space Models (SSMs). We find that intermediate layers often yield more informative representations for downstream tasks than the final layers. To measure the representation quality, we adapt and apply a suite of metrics - such as prompt entropy, curvature, and augmentation-invariance - originally proposed in other contexts. Our empirical study reveals significant architectural differences, how representations evolve throughout training, and how factors like input randomness and prompt length affect each layer. Notably, we observe a bimodal pattern in the entropy of some intermediate layers and consider potential explanations tied to training data. Overall, our results illuminate the internal mechanics of LLMs and guide strategies for architectural optimization and training.

[Arxiv](https://arxiv.org/abs/2412.09563)
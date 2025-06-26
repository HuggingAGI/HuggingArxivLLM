# 扩展模型规模的第四维度——维度四：模型规模的扩展维度

发布时间：2025年06月22日

`LLM理论` `人工智能`

> The 4th Dimension for Scaling Model Size

# 摘要

> 大型语言模型的扩展通常涉及三个维度：深度、宽度和参数数量。本研究引入了第四个维度——虚拟逻辑深度（VLD），它通过复用模型内部参数来提升有效算法深度，而无需改变总体参数量。尽管参数复用并非新概念，但其在模型扩展中的潜力和特性尚未得到充分研究。通过精心设计的控制实验，我们关于VLD扩展得出了以下关键发现：
    - VLD扩展使模型的知识容量几乎恒定，仅发生微小变化。
    - VLD扩展能够在正确实施方法时显著提升推理能力。
    - 参数数量与知识容量相关，但与推理能力无关。在某些条件下，无需增加参数数量即可增强推理能力。
    这些发现适用于多种模型配置，并在我们的实验范围内很可能普遍成立。

> Scaling the size of large language models typically involves three dimensions: depth, width, and the number of parameters. In this work, we explore a fourth dimension, virtual logical depth (VLD), which increases the effective algorithmic depth without changing the overall parameter count by reusing parameters within the model. Although parameter reuse is not a new concept, its potential and characteristics in model scaling have not been thoroughly studied. Through carefully designed controlled experiments, we make the following key discoveries regarding VLD scaling:
  VLD scaling forces the knowledge capacity of the model to remain almost constant, with only minor variations.
  VLD scaling enables a significant improvement in reasoning capability, provided the scaling method is properly implemented.
  The number of parameters correlates with knowledge capacity, but not with reasoning capability. Under certain conditions, it is not necessary to increase the parameter count to enhance reasoning.
  These findings are consistent across various model configurations and are likely to be generally valid within the scope of our experiments.

[Arxiv](https://arxiv.org/abs/2506.18233)
# 高效构建模型族：通过渐进式训练实现模型扩展

发布时间：2025年04月01日

`LLM理论

理由：这篇论文讨论了大型语言模型（LLMs）的训练方法，特别是如何通过渐进式训练构建模型家族，以提高计算效率和模型性能。研究的重点在于模型训练策略和计算效率，属于LLM的理论研究，因此归类为LLM理论。` `模型训练` `计算效率`

> Efficient Construction of Model Family through Progressive Training Using Model Expansion

# 摘要

> 随着大型语言模型（LLMs）在实际应用中的普及，构建不同参数规模的模型家族已成为满足多样化计算需求的标准做法。传统上，每个模型家族中的模型都是独立训练的，导致计算成本随着模型数量的增加而呈累加式增长。我们提出了一种通过渐进式训练构建模型家族的高效方法，其中较小的模型逐步扩展到更大的规模，从而形成一个完整的模型家族。通过使用从10亿到80亿参数范围的模型家族进行的广泛实验，我们证明了我们的方法能够将计算成本降低约25%，同时保持与独立训练模型相当的性能。此外，通过根据模型规模战略性地调整最大学习率，我们的方法在各种指标上都优于独立训练。除了性能提升，我们的方法还带来了额外的优势：我们家族中的模型在不同规模下往往表现出更一致的行为。

> As Large Language Models (LLMs) gain widespread practical application, providing the model family of different parameter sizes has become standard practice to address diverse computational requirements. Conventionally, each model in a family is trained independently, resulting in computational costs that scale additively with the number of models. We propose an efficient method for constructing the model family through progressive training, where smaller models are incrementally expanded to larger sizes to create a complete model family. Through extensive experiments with a model family ranging from 1B to 8B parameters, we demonstrate that our method reduces computational costs by approximately 25% while maintaining comparable performance to independently trained models. Furthermore, by strategically adjusting maximum learning rates based on model size, our method outperforms the independent training across various metrics. Beyond performance gains, our approach offers an additional advantage: models in our family tend to yield more consistent behavior across different model sizes.

[Arxiv](https://arxiv.org/abs/2504.00623)
# PaPaformer：基于预训练并行路径的语言模型

发布时间：2025年08月01日

`LLM理论` `人工智能` `模型优化`

> PaPaformer: Language Model from Pre-trained Paraller Paths

# 摘要

> 现代大型语言模型的训练需要日益增长的计算资源和时间投入。即使是小型语言模型（SLMs），在理想情况下也需要几天时间完成训练，通常还需依赖多块GPU。本文提出了一种全新的方法，旨在将基于解码器-only Transformer的语言模型训练时间从数天/数周大幅缩短至数小时。我们推出了一种名为	extit{PaPaformer}的解码器-only Transformer架构，通过整合低维并行路径构建更大规模的模型。研究发现，这些低维路径可分别采用不同类型的训练数据进行独立训练，随后整合成一个完整的大模型。这种创新方法不仅能够减少模型参数量和训练时间，还能显著提升模型性能。此外，通过并行路径结构，我们能够灵活定制模型路径以满足特定任务的需求，这一特性为模型优化提供了广阔的可能性。

> The training of modern large-language models requires an increasingly amount of computation power and time. Even smaller variants, such as small-language models (SLMs), take several days to train in the best-case scenarios, often requiring multiple GPUs. This paper explores methods to train and evaluate decoder-only transformer-based language models in hours instead of days/weeks. We introduces \textit{PaPaformer}, a decoder-only transformer architecture variant, whose lower-dimensional parallel paths are combined into larger model. The paper shows that these lower-dimensional paths can be trained individually with different types of training data and then combined into one larger model. This method gives the option to reduce the total number of model parameters and the training time with increasing performance. Moreover, the use of parallel path structure opens interesting possibilities to customize paths to accommodate specific task requirements.

[Arxiv](https://arxiv.org/abs/2508.00544)
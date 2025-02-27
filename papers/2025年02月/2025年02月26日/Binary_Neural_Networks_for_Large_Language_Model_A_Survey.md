# 针对大型语言模型的二值神经网络研究综述

发布时间：2025年02月26日

`LLM理论

理由：这篇论文讨论了大型语言模型（LLMs）的低比特量化技术，特别是二进制量化方法，属于模型优化和训练方法的范畴。它探讨了量化技术在LLMs中的应用，属于LLM的理论和技术层面。` `计算机科学` `量化技术`

> Binary Neural Networks for Large Language Model: A Survey

# 摘要

> 大型语言模型（LLMs）在自然语言处理（NLP）领域广泛应用，例如GPT-4和Llama。然而，随着模型参数规模的指数级增长，LLMs带来了显著的资源开销。低比特量化作为一种关键技术，通过减少模型参数、激活和梯度的位宽，降低了内存使用和计算需求。

此前针对LLMs的量化方法主要采用Post-Training Quantization (PTQ)和Quantization-Aware Training (QAT)。PTQ不需要对原始模型进行任何重新训练，而QAT则在训练过程中优化精度以达到最佳量化参数。BitNet团队提出了一种截然不同的方法，即从模型训练一开始就进行量化，利用低精度二进制权重进行训练过程。这种方法催生了许多针对大型语言模型的二进制量化技术。

本文对这些二进制量化技术进行了全面综述。具体来说，我们将介绍深度神经网络中的二进制量化技术，并进一步探讨其在LLMs中的应用，回顾它们的各种贡献、实现和应用场景。


> Large language models (LLMs) have wide applications in the field of natural language processing(NLP), such as GPT-4 and Llama. However, with the exponential growth of model parameter sizes, LLMs bring significant resource overheads. Low-bit quantization, as a key technique, reduces memory usage and computational demands by decreasing the bit-width of model parameters, activations, and gradients. Previous quantization methods for LLMs have largely employed Post-Training Quantization (PTQ) and Quantization-Aware Training (QAT). PTQ does not require any retraining of the original model, while QAT involves optimizing precision during training to achieve the best quantization parameters. The BitNet team proposed a radically different approach, where quantization is performed from the start of model training, utilizing low-precision binary weights during the training process. This approach has led to the emergence of many binary quantization techniques for large language models. This paper provides a comprehensive review of these binary quantization techniques. Specifically, we will introduce binary quantization techniques in deep neural networks and further explore their application to LLMs, reviewing their various contributions, implementations, and applications.

[Arxiv](https://arxiv.org/abs/2502.19008)
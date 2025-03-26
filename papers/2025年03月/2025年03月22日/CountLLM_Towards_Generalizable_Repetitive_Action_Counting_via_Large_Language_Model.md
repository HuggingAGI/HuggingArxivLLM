# CountLLM：探索通过大型语言模型实现通用重复动作计数的方法

发布时间：2025年03月22日

`LLM应用` `视频分析`

> CountLLM: Towards Generalizable Repetitive Action Counting via Large Language Model

# 摘要

> 重复动作计数旨在对视频中的周期性动作进行计数，这对视频分析应用（如健身监测）具有重要价值。然而，现有方法主要依赖于回归网络，其表达能力有限，这限制了它们准确捕捉多变周期模式的能力。此外，现有方法在狭窄且有限的训练集上进行监督学习，导致过拟合，限制了它们在不同场景下的泛化能力。为了解决这些挑战，我们提出了CountLLM，这是第一个基于大型语言模型（LLM）的框架，它将视频数据和周期性文本提示作为输入，并输出所需的计数结果。CountLLM利用显式文本指令中的丰富线索和预训练LLM的强大表达能力来进行重复动作计数。为了有效引导CountLLM，我们开发了一种基于周期性的结构化模板，描述周期性属性，并实现了标准化答案格式，以确保一致性。此外，我们还提出了一种渐进式多模态训练范式，以增强LLM对周期性的感知能力。在广泛认可的基准测试中的实证评估表明，CountLLM在性能和泛化能力方面表现出色，特别是在处理与训练数据显著不同的新动作和领域外动作时，为重复动作计数提供了一个有前途的解决方案。

> Repetitive action counting, which aims to count periodic movements in a video, is valuable for video analysis applications such as fitness monitoring. However, existing methods largely rely on regression networks with limited representational capacity, which hampers their ability to accurately capture variable periodic patterns. Additionally, their supervised learning on narrow, limited training sets leads to overfitting and restricts their ability to generalize across diverse scenarios. To address these challenges, we propose CountLLM, the first large language model (LLM)-based framework that takes video data and periodic text prompts as inputs and outputs the desired counting value. CountLLM leverages the rich clues from explicit textual instructions and the powerful representational capabilities of pre-trained LLMs for repetitive action counting. To effectively guide CountLLM, we develop a periodicity-based structured template for instructions that describes the properties of periodicity and implements a standardized answer format to ensure consistency. Additionally, we propose a progressive multimodal training paradigm to enhance the periodicity-awareness of the LLM. Empirical evaluations on widely recognized benchmarks demonstrate CountLLM's superior performance and generalization, particularly in handling novel and out-of-domain actions that deviate significantly from the training data, offering a promising avenue for repetitive action counting.

[Arxiv](https://arxiv.org/abs/2503.17690)
# 快速静默-STaR：无需思考令牌的思考方式

发布时间：2025年05月23日

`LLM应用

摘要中提到的研究重点在于改进大型语言模型的推理能力，通过优化推理框架和训练策略，提升模型的效率和性能。这属于对LLM的实际应用和优化，因此归类为LLM应用。` `人工智能`

> Fast Quiet-STaR: Thinking Without Thought Tokens

# 摘要

> 大型语言模型（LLMs）在自然语言处理任务中展现了卓越的表现。然而，近期的进展表明，要在复杂推理任务中实现进一步突破，仅仅扩大模型规模或增加训练数据是不够的。一个有前景的方向是让模型在推理过程中进行思考。最近，Quiet STaR通过生成基于token的思考轨迹显著提升了推理能力，但带来了较大的推理开销。在本研究中，我们提出了Fast Quiet STaR，一个更高效的推理框架，它保留了基于token推理的优势，同时降低了计算成本。我们的方法引入了一种基于课程学习的训练策略，逐步减少思考token的数量，使模型能够内化更抽象、更简洁的推理过程。我们进一步通过强化学习微调将此方法扩展到标准的下一个token预测（NTP）设置，得到了Fast Quiet-STaR NTP，它在推理过程中无需显式生成思考token。在Mistral 7B和Qwen2.5 7B模型上进行的四个基准数据集实验表明，在相同的推理时间预算下，Fast Quiet-STaR在平均准确率上始终优于Quiet-STaR。值得注意的是，Fast Quiet-STaR NTP在Mistral 7B上实现了平均准确率提升9%，在Qwen2.5 7B上提升了5.7%，同时保持相同的推理延迟。我们的代码将在https://github.com/huangwei200012/Fast-Quiet-STaR上公开发布。


> Large Language Models (LLMs) have achieved impressive performance across a range of natural language processing tasks. However, recent advances demonstrate that further gains particularly in complex reasoning tasks require more than merely scaling up model sizes or training data. One promising direction is to enable models to think during the reasoning process. Recently, Quiet STaR significantly improves reasoning by generating token-level thought traces, but incurs substantial inference overhead. In this work, we propose Fast Quiet STaR, a more efficient reasoning framework that preserves the benefits of token-level reasoning while reducing computational cost. Our method introduces a curriculum learning based training strategy that gradually reduces the number of thought tokens, enabling the model to internalize more abstract and concise reasoning processes. We further extend this approach to the standard Next Token Prediction (NTP) setting through reinforcement learning-based fine-tuning, resulting in Fast Quiet-STaR NTP, which eliminates the need for explicit thought token generation during inference. Experiments on four benchmark datasets with Mistral 7B and Qwen2.5 7B demonstrate that Fast Quiet-STaR consistently outperforms Quiet-STaR in terms of average accuracy under the same inference time budget. Notably, Fast Quiet-STaR NTP achieves an average accuracy improvement of 9\% on Mistral 7B and 5.7\% on Qwen2.5 7B, while maintaining the same inference latency. Our code will be available at https://github.com/huangwei200012/Fast-Quiet-STaR.

[Arxiv](https://arxiv.org/abs/2505.17746)
# S2SBench：语音到语音大语言模型智能退化的量化基准测试

发布时间：2025年05月20日

`LLM应用

摘要中讨论了语音大语言模型的应用，特别是其性能评估和基准测试的开发，属于LLM在特定领域的应用研究。` `语音处理`

> S2SBench: A Benchmark for Quantifying Intelligence Degradation in Speech-to-Speech Large Language Models

# 摘要

> 端到端语音大语言模型 (LLMs) 将文本模型的能力扩展至直接处理和生成音频令牌。然而，与文本输入相比，这通常会导致推理和生成性能的下降，这一现象被称为智能下降。为了系统评估这一差距，我们提出了S2SBench，这是一个专门用于量化语音LLMs性能下降的基准测试。它包含针对音频输入下的句子续写和常识推理设计的诊断数据集。我们还引入了一种基于合理样本与不合理样本困惑度差异的配对评估协议，用于衡量相对于文本输入的性能下降。我们通过S2SBench分析了Baichuan-Audio的训练过程，进一步证明了该基准测试的有效性。所有数据集和评估代码均可在https://github.com/undobug/S2SBench获取。

> End-to-end speech large language models ((LLMs)) extend the capabilities of text-based models to directly process and generate audio tokens. However, this often leads to a decline in reasoning and generation performance compared to text input, a phenomenon referred to as intelligence degradation. To systematically evaluate this gap, we propose S2SBench, a benchmark designed to quantify performance degradation in Speech LLMs. It includes diagnostic datasets targeting sentence continuation and commonsense reasoning under audio input. We further introduce a pairwise evaluation protocol based on perplexity differences between plausible and implausible samples to measure degradation relative to text input. We apply S2SBench to analyze the training process of Baichuan-Audio, which further demonstrates the benchmark's effectiveness. All datasets and evaluation code are available at https://github.com/undobug/S2SBench.

[Arxiv](https://arxiv.org/abs/2505.14438)
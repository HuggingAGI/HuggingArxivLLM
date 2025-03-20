# OpenLLM-RTL：助力LLM设计的开放RTL生成数据集与基准测试

发布时间：2025年03月19日

`LLM应用` `电子设计自动化` `电子电路设计`

> OpenLLM-RTL: Open Dataset and Benchmark for LLM-Aided Design RTL Generation

# 摘要

> 基于 LLM 和自然语言指令的 RTL 设计自动生成在敏捷电路设计中展现出巨大潜力。然而，公共领域缺乏相应数据集和基准，限制了 LLM 解决方案的发展和公平评估。本文从三个维度展示了我们在开放数据集和基准方面的最新进展：

（1）RTLLM 2.0：更新的基准，用于评估 LLM 在 RTL 设计生成方面的能力。该基准扩展至 50 个手工设计，每个设计提供设计描述、测试用例和正确 RTL 代码。

（2）AssertEval：开源基准，用于评估 LLM 在 RTL 验证中的断言生成能力。包含 18 个设计，每个设计提供规范、信号定义和正确 RTL 代码。

（3）RTLCoder-Data：扩展的开源数据集，包含 80,000 个指令-代码数据样本。

此外，我们提出了一种新的验证方法，用于验证训练数据样本的功能正确性。基于此技术，我们发布了包含 7,000 个经过验证的高质量样本的数据集。这三项研究整合到一个统一框架中，为 RTL 代码生成和验证的 LLM 开发和评估提供了开箱即用的支持。实验表明，通过扩大训练数据规模、提升数据质量和优化训练方案，可以显著提升 LLM 的性能。

> The automated generation of design RTL based on large language model (LLM) and natural language instructions has demonstrated great potential in agile circuit design. However, the lack of datasets and benchmarks in the public domain prevents the development and fair evaluation of LLM solutions. This paper highlights our latest advances in open datasets and benchmarks from three perspectives: (1) RTLLM 2.0, an updated benchmark assessing LLM's capability in design RTL generation. The benchmark is augmented to 50 hand-crafted designs. Each design provides the design description, test cases, and a correct RTL code. (2) AssertEval, an open-source benchmark assessing the LLM's assertion generation capabilities for RTL verification. The benchmark includes 18 designs, each providing specification, signal definition, and correct RTL code. (3) RTLCoder-Data, an extended open-source dataset with 80K instruction-code data samples. Moreover, we propose a new verification-based method to verify the functionality correctness of training data samples. Based on this technique, we further release a dataset with 7K verified high-quality samples. These three studies are integrated into one framework, providing off-the-shelf support for the development and evaluation of LLMs for RTL code generation and verification. Finally, extensive experiments indicate that LLM performance can be boosted by enlarging the training dataset, improving data quality, and improving the training scheme.

[Arxiv](https://arxiv.org/abs/2503.15112)
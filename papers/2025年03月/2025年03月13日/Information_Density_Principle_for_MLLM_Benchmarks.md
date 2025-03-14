# # 多语言大型语言模型基准的信息密度准则

发布时间：2025年03月13日

`LLM理论` `模型评估`

> Information Density Principle for MLLM Benchmarks

# 摘要

> 随着多模态大型语言模型（MLLMs）的兴起，人们开发了数百个基准测试以确保这些模型在下游任务中的可靠性。然而，评估机制本身可能并不可靠。对于MLLMs的开发者来说，选择合适的基准测试以及测试结果是否符合需求仍然是一个挑战。因此，我们提出了一项关键原则——信息密度原则，用于评估基准测试能为MLLMs开发提供多少洞察力。我们从四个维度对这一原则进行了描述：(1) 错误观念，(2) 难度，(3) 冗余，(4) 多样性。通过对超过10,000个样本的全面分析，我们测量了19个MLLMs基准测试的信息密度。实验表明，与之前的基准测试相比，使用最新的基准测试可以提供更多的洞察力，但它们的信息密度仍有提升空间。我们希望这一原则能够促进未来MLLMs基准测试的发展和应用。项目页面：https://github.com/lcysyzxdxc/bench4bench

> With the emergence of Multimodal Large Language Models (MLLMs), hundreds of benchmarks have been developed to ensure the reliability of MLLMs in downstream tasks. However, the evaluation mechanism itself may not be reliable. For developers of MLLMs, questions remain about which benchmark to use and whether the test results meet their requirements. Therefore, we propose a critical principle of Information Density, which examines how much insight a benchmark can provide for the development of MLLMs. We characterize it from four key dimensions: (1) Fallacy, (2) Difficulty, (3) Redundancy, (4) Diversity. Through a comprehensive analysis of more than 10,000 samples, we measured the information density of 19 MLLM benchmarks. Experiments show that using the latest benchmarks in testing can provide more insight compared to previous ones, but there is still room for improvement in their information density. We hope this principle can promote the development and application of future MLLM benchmarks. Project page: https://github.com/lcysyzxdxc/bench4bench

[Arxiv](https://arxiv.org/abs/2503.10079)
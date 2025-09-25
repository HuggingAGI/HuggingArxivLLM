# Web API集成代码生成的基准测试

发布时间：2025年09月24日

`LLM应用` `基础理论`

> Benchmarking Web API Integration Code Generation

# 摘要

> API集成是数字基础设施的核心，它让各类软件系统得以互联互通。然而，众多研究表明，编写或生成正确调用API（尤其是Web API）的代码颇具难度。尽管大型语言模型（LLMs）已在软件开发领域广泛应用，但它们在自动生成Web API集成代码方面的实际效果尚未得到验证。为此，我们构建了一个数据集和评估流程，专门用于评估LLMs生成Web API调用代码的能力。我们对多款开源LLM的实验发现，生成API调用代码面临巨大挑战，常出现端点虚构、参数误用等问题。所有接受评估的开源模型中，没有一个能完成超过40%的任务。

> API integration is a cornerstone of our digital infrastructure, enabling software systems to connect and interact. However, as shown by many studies, writing or generating correct code to invoke APIs, particularly web APIs, is challenging. Although large language models~(LLMs) have become popular in software development, their effectiveness in automating the generation of web API integration code remains unexplored. In order to address this, we present a dataset and evaluation pipeline designed to assess the ability of LLMs to generate web API invocation code. Our experiments with several open-source LLMs reveal that generating API invocations poses a significant challenge, resulting in hallucinated endpoints, incorrect argument usage, and other errors. None of the evaluated open-source models were able to solve more than 40% of the tasks.

[Arxiv](https://arxiv.org/abs/2509.20172)
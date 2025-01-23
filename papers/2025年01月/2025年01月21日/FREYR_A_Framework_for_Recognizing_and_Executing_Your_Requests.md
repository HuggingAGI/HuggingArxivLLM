# FREYR: 识别与执行请求的框架

发布时间：2025年01月21日

`Agent

理由：这篇论文主要讨论了如何通过使用工具（如可执行代码）来增强大型语言模型在对话代理领域的能力。FREYR框架的提出是为了模块化工具使用过程，从而提升性能。这涉及到对话代理（Agent）的改进和优化，因此应归类为Agent。` `对话代理` `视频游戏`

> FREYR: A Framework for Recognizing and Executing Your Requests

# 摘要

> 大型语言模型在对话代理领域表现出色，但通过使用工具（如可执行代码）可以进一步提升其能力，以增强响应准确性或应对特定领域问题。目前，启用工具使用的方法多依赖于模型特定的提示或微调模型以执行函数调用指令，但这些方法存在适应性差和资源消耗大的问题。本文提出的FREYR框架，将工具使用过程模块化，分解为独立步骤，从而在性能上超越了传统方法。我们在视频游戏设计的实际测试案例中评估了FREYR，并与Ollama API的传统工具使用进行了对比。

> Large language models excel as conversational agents, but their capabilities can be further extended through tool usage, i.e.: executable code, to enhance response accuracy or address specialized domains. Current approaches to enable tool usage often rely on model-specific prompting or fine-tuning a model for function-calling instructions. Both approaches have notable limitations, including reduced adaptability to unseen tools and high resource requirements. This paper introduces FREYR, a streamlined framework that modularizes the tool usage process into separate steps. Through this decomposition, we show that FREYR achieves superior performance compared to conventional tool usage methods. We evaluate FREYR on a set of real-world test cases specific for video game design and compare it against traditional tool usage as provided by the Ollama API.

[Arxiv](https://arxiv.org/abs/2501.12423)
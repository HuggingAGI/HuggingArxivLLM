# ComplexFuncBench: 长上下文场景下的多步骤与受限函数调用探索

发布时间：2025年01月17日

`LLM应用

理由：这篇论文主要讨论了如何通过将大型语言模型（LLMs）与实时API结合来生成更准确和实时的响应，并提出了一个复杂函数调用基准（ComplexFuncBench）和自动评估框架（ComplexEval）。这些内容属于LLM在实际应用中的优化和评估，因此归类为“LLM应用”。` `软件开发` `人工智能`

> ComplexFuncBench: Exploring Multi-Step and Constrained Function Calling under Long-Context Scenario

# 摘要

> 通过将大型语言模型（LLMs）与实时API结合，可以生成更准确和实时的响应。然而，由于数据收集和评估的复杂性，LLMs在现实场景中的函数调用能力仍未被充分研究。为此，我们推出了ComplexFuncBench，一个涵盖五个现实场景的复杂函数调用基准。与现有基准相比，ComplexFuncBench不仅支持多步骤和受约束的函数调用，还涉及长参数填写、参数值推理以及128k长上下文处理。我们还提出了ComplexEval自动评估框架，用于定量分析复杂函数调用任务。通过一系列实验，我们揭示了当前顶尖LLMs在函数调用方面的不足，并指出了未来优化的方向。相关数据和代码已开源，详见url{https://github.com/THUDM/ComplexFuncBench}。

> Enhancing large language models (LLMs) with real-time APIs can help generate more accurate and up-to-date responses. However, evaluating the function calling abilities of LLMs in real-world scenarios remains under-explored due to the complexity of data collection and evaluation. In this work, we introduce ComplexFuncBench, a benchmark for complex function calling across five real-world scenarios. Compared to existing benchmarks, ComplexFuncBench encompasses multi-step and constrained function calling, which requires long-parameter filing, parameter value reasoning, and 128k long context. Additionally, we propose an automatic framework, ComplexEval, for quantitatively evaluating complex function calling tasks. Through comprehensive experiments, we demonstrate the deficiencies of state-of-the-art LLMs in function calling and suggest future directions for optimizing these capabilities. The data and code are available at url{https://github.com/THUDM/ComplexFuncBench}.

[Arxiv](https://arxiv.org/abs/2501.10132)
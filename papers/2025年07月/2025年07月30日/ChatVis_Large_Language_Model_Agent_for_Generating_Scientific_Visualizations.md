# ChatVis：专为生成科学可视化而设计的大型语言模型智能体

发布时间：2025年07月30日

`LLM应用` `可视化`

> ChatVis: Large Language Model Agent for Generating Scientific Visualizations

# 摘要

> 大型语言模型（LLMs）的能力虽在不断提升，但在处理科学可视化等高度专业化的编程任务时仍显不足。为此，我们推出了一款名为 ChatVis 的 LLM 助手，它能协助 LLM 自动生成用于 ParaView 科学可视化任务的 Python 代码，且无需对 LLM 进行重新训练或微调。ChatVis 采用链式思维提示简化、基于文档和代码示例的向量数据库增强提示生成，以及通过迭代反馈机制进行错误检查，直至生成最终的可视化结果。我们的方法还配套了一个基准测试套件，包含典型可视化任务、ParaView 回归测试和科学用例，并配备了全面的评估指标。通过将 ChatVis 的结果与多种高性能无辅助 LLM 的结果进行对比，我们发现所有评估指标均得到了显著提升。

> Large language models (LLMs) are rapidly increasing in capability, but they still struggle with highly specialized programming tasks such as scientific visualization. We present an LLM assistant, ChatVis, that aids the LLM to generate Python code for ParaView scientific visualization tasks, without the need for retraining or fine-tuning the LLM. ChatVis employs chain-of-thought prompt simplification, retrieval-augmented prompt generation using a vector database of documentation and code examples, and error checking with iterative prompt feedback to correct errors until a visualization is produced. An integral part of our approach is a benchmark suite of canonical visualization tasks, ParaView regression tests, and scientific use cases that includes comprehensive evaluation metrics. We evaluate our visualization assistant by comparing results with a variety of top-performing unassisted LLMs. We find that all the metrics are significantly improved with ChatVis.

[Arxiv](https://arxiv.org/abs/2507.23096)
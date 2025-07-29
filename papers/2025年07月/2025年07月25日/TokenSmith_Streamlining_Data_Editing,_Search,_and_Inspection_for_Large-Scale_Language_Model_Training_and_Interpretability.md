# TokenSmith：优化大规模语言模型训练与可解释性中的数据编辑、搜索与检查

发布时间：2025年07月25日

`LLM应用` `人工智能` `数据处理`

> TokenSmith: Streamlining Data Editing, Search, and Inspection for Large-Scale Language Model Training and Interpretability

# 摘要

> 预训练过程中，理解训练数据与模型行为之间的关系至关重要。然而，现有工作流程繁琐且分散，常让研究人员难以触及。为此，我们推出TokenSmith——一个开源库，专为交互式编辑、检查和分析Megatron风格预训练框架（如GPT-NeoX、Megatron和NVIDIA NeMo）中的数据集而设计。

TokenSmith功能丰富，支持搜索、查看、导入、导出、检查和采样数据，所有操作均可通过简洁的用户界面和模块化后端轻松完成。无需修改训练代码，即可进行结构化数据编辑，极大简化了数据集调试、验证和实验过程。

TokenSmith作为现有大规模语言模型预训练流程的即插即用组件，降低了生产级数据集工具的使用门槛。它托管在GitHub1上，配备详尽文档和教程。此外，演示视频也可在YouTube上观看。


> Understanding the relationship between training data and model behavior during pretraining is crucial, but existing workflows make this process cumbersome, fragmented, and often inaccessible to researchers. We present TokenSmith, an open-source library for interactive editing, inspection, and analysis of datasets used in Megatron-style pretraining frameworks such as GPT-NeoX, Megatron, and NVIDIA NeMo. TokenSmith supports a wide range of operations including searching, viewing, ingesting, exporting, inspecting, and sampling data, all accessible through a simple user interface and a modular backend. It also enables structured editing of pretraining data without requiring changes to training code, simplifying dataset debugging, validation, and experimentation.
  TokenSmith is designed as a plug and play addition to existing large language model pretraining workflows, thereby democratizing access to production-grade dataset tooling. TokenSmith is hosted on GitHub1, with accompanying documentation and tutorials. A demonstration video is also available on YouTube.

[Arxiv](https://arxiv.org/abs/2507.19419)
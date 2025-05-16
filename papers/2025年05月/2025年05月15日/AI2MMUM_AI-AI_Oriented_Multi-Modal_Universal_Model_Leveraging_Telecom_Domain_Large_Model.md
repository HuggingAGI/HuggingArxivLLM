# AI2MMUM：利用电信领域大型模型的多模态通用模型，专为AI-AI设计

发布时间：2025年05月15日

`LLM应用

理由：这篇论文讨论了面向6G的通用模型设计，特别是结合了大型语言模型（LLM）在通信和电信领域的应用。论文提出了AI2MMUM模型，该模型结合了LLM的主干结构，并通过微调方法融入了特定领域的专业知识，用于执行物理层任务。这表明论文的重点在于将LLM应用于特定领域（即通信领域），因此属于LLM应用类别。` `无线通信`

> AI2MMUM: AI-AI Oriented Multi-Modal Universal Model Leveraging Telecom Domain Large Model

# 摘要

> 面向6G的通用模型设计已成为未来无线系统的重要目标，该模型需具备多模态数据处理和多样化空中接口任务执行能力。基于我们在通信多模态对齐和电信领域大型语言模型（LLM）的研究积累，我们提出了AI2MMUM——一种可扩展且任务感知的通用模型。它能够根据具体任务指令，灵活高效地执行各种物理层任务。AI2MMUM的LLM主干结构不仅具备强大的上下文理解与泛化能力，还通过微调方法融入了特定领域的专业知识。为了提升任务适应性，我们设计了由固定任务关键词和可学习隐式前缀提示组成的任务指令。模型采用冻结的无线模态编码器提取通用表示，并通过适配器层实现无线与语言模态的连接。此外，轻量级的任务特定头部可直接输出任务目标。实验结果表明，AI2MMUM在WAIR-D和DeepMIMO数据集的五个代表性物理环境/无线信道下游任务中达到了SOTA性能。

> Designing a 6G-oriented universal model capable of processing multi-modal data and executing diverse air interface tasks has emerged as a common goal in future wireless systems. Building on our prior work in communication multi-modal alignment and telecom large language model (LLM), we propose a scalable, task-aware artificial intelligence-air interface multi-modal universal model (AI2MMUM), which flexibility and effectively perform various physical layer tasks according to subtle task instructions. The LLM backbone provides robust contextual comprehension and generalization capabilities, while a fine-tuning approach is adopted to incorporate domain-specific knowledge. To enhance task adaptability, task instructions consist of fixed task keywords and learnable, implicit prefix prompts. Frozen radio modality encoders extract universal representations and adapter layers subsequently bridge radio and language modalities. Moreover, lightweight task-specific heads are designed to directly output task objectives. Comprehensive evaluations demonstrate that AI2MMUM achieves SOTA performance across five representative physical environment/wireless channel-based downstream tasks using the WAIR-D and DeepMIMO datasets.

[Arxiv](https://arxiv.org/abs/2505.10003)
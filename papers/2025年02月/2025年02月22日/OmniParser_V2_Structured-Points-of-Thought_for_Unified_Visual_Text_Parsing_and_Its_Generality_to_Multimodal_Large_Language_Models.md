# # **OmniParser V2：面向统一视觉文本解析的结构化思维框架及其在多模态大型语言模型中的通用性探索**

发布时间：2025年02月22日

`LLM应用

理由：这篇论文主要讨论了如何将大型语言模型应用于视觉定位文本解析（VsTP）任务，并提出了一种通用的解决方案OmniParser V2。论文的重点在于模型的应用和实际任务的处理，而不是模型本身的理论或架构改进。因此，它属于LLM应用类别。` `文档分析` `信息抽取`

> OmniParser V2: Structured-Points-of-Thought for Unified Visual Text Parsing and Its Generality to Multimodal Large Language Models

# 摘要

> 视觉定位文本解析（VsTP）领域近期取得了显著进展，这一进步主要源于对自动化文档理解日益增长的需求，以及大型语言模型处理基于文档问题能力的出现。尽管提出了多种方法来应对VsTP的复杂性，但现有解决方案往往依赖于针对特定任务的架构和目标，导致了模态隔离和复杂的处理流程，这是由于多样化的目标和异构的架构所引起的。

本文中，我们介绍了OmniParser V2，一个通用模型，它将VsTP中的典型任务（包括文本定位、关键信息抽取、表格识别和版式分析）统一到一个框架中。我们方法的核心是提出的结构化思考点（SPOT）提示框架，它通过利用统一的编码器-解码器架构、目标以及输入和输出表示，提升了模型在多样化场景下的性能。SPOT消除了对任务特定架构和损失函数的需求，极大地简化了处理流程。

我们在八种不同数据集上对四个任务进行了广泛的评估，结果表明OmniParser V2在VsTP中达到了目前最先进的水平或具有竞争力。此外，我们还探索了将SPOT整合到多模态大型语言模型结构中，进一步增强了文本定位和识别能力，从而验证了SPOT提示技术的通用性。代码可在\href{https://github.com/AlibabaResearch/AdvancedLiterateMachinery}{AdvancedLiterateMachinery}获取。

> Visually-situated text parsing (VsTP) has recently seen notable advancements, driven by the growing demand for automated document understanding and the emergence of large language models capable of processing document-based questions. While various methods have been proposed to tackle the complexities of VsTP, existing solutions often rely on task-specific architectures and objectives for individual tasks. This leads to modal isolation and complex workflows due to the diversified targets and heterogeneous schemas. In this paper, we introduce OmniParser V2, a universal model that unifies VsTP typical tasks, including text spotting, key information extraction, table recognition, and layout analysis, into a unified framework. Central to our approach is the proposed Structured-Points-of-Thought (SPOT) prompting schemas, which improves model performance across diverse scenarios by leveraging a unified encoder-decoder architecture, objective, and input\&output representation. SPOT eliminates the need for task-specific architectures and loss functions, significantly simplifying the processing pipeline. Our extensive evaluations across four tasks on eight different datasets show that OmniParser V2 achieves state-of-the-art or competitive results in VsTP. Additionally, we explore the integration of SPOT within a multimodal large language model structure, further enhancing text localization and recognition capabilities, thereby confirming the generality of SPOT prompting technique. The code is available at \href{https://github.com/AlibabaResearch/AdvancedLiterateMachinery}{AdvancedLiterateMachinery}.

[Arxiv](https://arxiv.org/abs/2502.16161)
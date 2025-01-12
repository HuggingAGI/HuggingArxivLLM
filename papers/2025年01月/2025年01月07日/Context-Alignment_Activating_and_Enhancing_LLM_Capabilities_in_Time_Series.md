# 上下文对齐：激活并增强LLM在时间序列中的能力

发布时间：2025年01月07日

`LLM应用

理由：这篇论文主要讨论了如何利用预训练的大型语言模型（LLMs）来处理时间序列（TS）任务，并提出了一种新的范式Context-Alignment来增强LLMs的能力。论文的核心在于如何将LLMs应用于特定的任务（时间序列处理），并通过实验验证了其有效性。因此，这篇论文属于LLM应用类别。` `时间序列分析`

> Context-Alignment: Activating and Enhancing LLM Capabilities in Time Series

# 摘要

> # 摘要
最近，利用预训练的大型语言模型（LLMs）处理时间序列（TS）任务逐渐成为热点，其核心在于激活和增强LLMs的能力。现有方法大多通过token级别的对齐来激活LLMs，却忽略了LLMs在自然语言处理中的核心优势——对语言逻辑和结构的深层理解，而非简单的嵌入处理。为此，我们提出了Context-Alignment，一种新范式，将TS与LLMs熟悉的语言环境中的语言组件对齐，使LLMs能够理解并情境化TS数据，从而激活其能力。具体而言，这种上下文对齐包括结构对齐和逻辑对齐，通过双尺度上下文对齐图神经网络（DSCA-GNNs）实现。结构对齐利用双尺度节点描述TS-语言的层次结构，使LLMs能够将长TS数据视为一个整体语言组件，同时保留token特征。逻辑对齐则通过有向边引导逻辑关系，确保上下文语义的连贯性。基于DSCA-GNNs框架，我们构建了基于示范示例的上下文对齐（DECA）。DECA可灵活集成到预训练LLMs的各个层中，提升其对逻辑和结构的感知能力，从而优化性能。大量实验验证了DECA的有效性，并证明了Context-Alignment在少样本和零样本预测等任务中的重要性，表明其为上下文提供了强大的先验知识。

> Recently, leveraging pre-trained Large Language Models (LLMs) for time series (TS) tasks has gained increasing attention, which involves activating and enhancing LLMs' capabilities. Many methods aim to activate LLMs' capabilities based on token-level alignment but overlook LLMs' inherent strength on natural language processing -- their deep understanding of linguistic logic and structure rather than superficial embedding processing. We propose Context-Alignment, a new paradigm that aligns TS with a linguistic component in the language environments familiar to LLMs to enable LLMs to contextualize and comprehend TS data, thereby activating their capabilities. Specifically, such context-level alignment comprises structural alignment and logical alignment, which is achieved by a Dual-Scale Context-Alignment GNNs (DSCA-GNNs) applied to TS-language multimodal inputs. Structural alignment utilizes dual-scale nodes to describe hierarchical structure in TS-language, enabling LLMs treat long TS data as a whole linguistic component while preserving intrinsic token features. Logical alignment uses directed edges to guide logical relationships, ensuring coherence in the contextual semantics. Demonstration examples prompt are employed to construct Demonstration Examples based Context-Alignment (DECA) following DSCA-GNNs framework. DECA can be flexibly and repeatedly integrated into various layers of pre-trained LLMs to improve awareness of logic and structure, thereby enhancing performance. Extensive experiments show the effectiveness of DECA and the importance of Context-Alignment across tasks, particularly in few-shot and zero-shot forecasting, confirming that Context-Alignment provide powerful prior knowledge on context.

[Arxiv](https://arxiv.org/abs/2501.03747)
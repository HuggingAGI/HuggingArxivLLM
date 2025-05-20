# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年05月18日

`LLM应用

摘要讨论了模型编辑的目标和现有的挑战，并提出了一个统一的LLM编辑基准UniEdit。该基准旨在通过全面的知识领域覆盖和多样化的评估来提升LLM的性能。因此，它属于LLM应用，因为它专注于LLM的实际应用和改进。` `开放领域知识` `知识图谱`

> UniEdit: A Unified Knowledge Editing Benchmark for Large Language Models

# 摘要

> 模型编辑的目标是通过高效调整大型语言模型（LLMs）的内部参数来提升其准确性和可靠性。然而，现有的大多数LLM编辑数据集局限于狭窄的知识领域，且编辑评估范围有限，往往忽视了编辑需求的广泛性以及编辑引发的多样化连锁效应。为此，我们提出了一个基于开放领域知识的统一LLM编辑基准——UniEdit。首先，我们从五个主要类别中的25个常见领域中选择实体来构建编辑样本，利用开放领域知识图谱中丰富的三元组知识，确保全面覆盖知识领域。为了解决编辑中的通用性和局部性问题，我们设计了一种Neighborhood Multi-hop Chain Sampling（NMCS）算法，通过基于给定知识片段采样子图以引发全面连锁效应，从而进行综合评估。最后，我们采用专有LLMs将采样的知识子图转换为自然语言文本，确保语法准确性和句法多样性。统计分析表明，我们的UniEdit基准在规模、全面性和多样性方面表现突出。通过在多个LLMs和编辑器上进行的全面实验，我们分析了其性能，揭示了在开放知识领域和各种评估标准下的编辑优势与不足，为未来的研究工作提供了有价值的见解。

> Model editing aims to enhance the accuracy and reliability of large language models (LLMs) by efficiently adjusting their internal parameters. Currently, most LLM editing datasets are confined to narrow knowledge domains and cover a limited range of editing evaluation. They often overlook the broad scope of editing demands and the diversity of ripple effects resulting from edits. In this context, we introduce UniEdit, a unified benchmark for LLM editing grounded in open-domain knowledge. First, we construct editing samples by selecting entities from 25 common domains across five major categories, utilizing the extensive triple knowledge available in open-domain knowledge graphs to ensure comprehensive coverage of the knowledge domains. To address the issues of generality and locality in editing, we design an Neighborhood Multi-hop Chain Sampling (NMCS) algorithm to sample subgraphs based on a given knowledge piece to entail comprehensive ripple effects to evaluate. Finally, we employ proprietary LLMs to convert the sampled knowledge subgraphs into natural language text, guaranteeing grammatical accuracy and syntactical diversity. Extensive statistical analysis confirms the scale, comprehensiveness, and diversity of our UniEdit benchmark. We conduct comprehensive experiments across multiple LLMs and editors, analyzing their performance to highlight strengths and weaknesses in editing across open knowledge domains and various evaluation criteria, thereby offering valuable insights for future research endeavors.

[Arxiv](https://arxiv.org/abs/2505.12345)
# UniEdit：大型语言模型统一知识编辑基准

发布时间：2025年05月18日

`LLM理论` `模型编辑` `基准测试`

> UniEdit: A Unified Knowledge Editing Benchmark for Large Language Models

# 摘要

> 模型编辑通过高效调整大型语言模型（LLMs）的内部参数，旨在提升其准确性和可靠性。然而，现有的LLM编辑数据集大多局限于狭窄的知识领域，且编辑评估范围有限。它们往往忽视了编辑需求的广泛性和由此引发的多样化连锁反应。因此，我们推出了UniEdit——一个基于开放领域知识的统一LLM编辑基准。首先，我们从涵盖五个主要类别的25个常见领域中选择实体，利用开放领域知识图谱中丰富的三元组知识构建编辑样本，确保对知识领域的全面覆盖。为了解决编辑中的普遍性和局部性问题，我们设计了Neighborhood Multi-hop Chain Sampling (NMCS)算法，基于给定知识片段采样子图，以引发全面的连锁反应，从而实现全面评估。最后，我们采用自有LLMs将采样的知识子图转换为自然语言文本，确保语法准确性和句法多样性。通过大量统计分析，我们验证了UniEdit基准在规模、全面性和多样性方面的优势。我们在多个LLMs和编辑器上进行了全面实验，分析其性能表现，揭示了在开放知识领域和各种评估标准下的编辑优缺点，为未来的研究方向提供了宝贵见解。

> Model editing aims to enhance the accuracy and reliability of large language models (LLMs) by efficiently adjusting their internal parameters. Currently, most LLM editing datasets are confined to narrow knowledge domains and cover a limited range of editing evaluation. They often overlook the broad scope of editing demands and the diversity of ripple effects resulting from edits. In this context, we introduce UniEdit, a unified benchmark for LLM editing grounded in open-domain knowledge. First, we construct editing samples by selecting entities from 25 common domains across five major categories, utilizing the extensive triple knowledge available in open-domain knowledge graphs to ensure comprehensive coverage of the knowledge domains. To address the issues of generality and locality in editing, we design an Neighborhood Multi-hop Chain Sampling (NMCS) algorithm to sample subgraphs based on a given knowledge piece to entail comprehensive ripple effects to evaluate. Finally, we employ proprietary LLMs to convert the sampled knowledge subgraphs into natural language text, guaranteeing grammatical accuracy and syntactical diversity. Extensive statistical analysis confirms the scale, comprehensiveness, and diversity of our UniEdit benchmark. We conduct comprehensive experiments across multiple LLMs and editors, analyzing their performance to highlight strengths and weaknesses in editing across open knowledge domains and various evaluation criteria, thereby offering valuable insights for future research endeavors.

[Arxiv](https://arxiv.org/abs/2505.12345)
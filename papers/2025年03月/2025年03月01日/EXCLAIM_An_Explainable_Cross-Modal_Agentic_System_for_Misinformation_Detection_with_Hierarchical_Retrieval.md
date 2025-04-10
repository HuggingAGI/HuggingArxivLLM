# EXCLAIM：基于分层检索的可解释跨模态虚假信息检测智能系统。

发布时间：2025年03月01日

`LLM应用

理由：这篇论文探讨了多模态大型语言模型在检测上下文不符虚假信息中的应用，提出了一个基于检索的框架EXCLAIM，结合多模态分析和多智能体推理来评估新闻内容的一致性。虽然涉及模型的应用，但主要聚焦于实际问题的解决，属于应用层面。`

> EXCLAIM: An Explainable Cross-Modal Agentic System for Misinformation Detection with Hierarchical Retrieval

# 摘要

> 虚假信息依然是当今信息生态系统中的重大挑战，深刻影响着公众的认知和行为。在众多表现形式中，上下文不符（OOC）虚假信息尤为隐蔽，因为它通过将真实图像与误导性文本叙述配对来扭曲信息含义。

现有的OOC虚假信息检测方法主要依赖于图像-文本对之间的粗粒度相似性度量，这些方法往往无法捕捉到细微的不一致，也难以提供有意义的可解释性。尽管多模态大型语言模型（MLLMs）在视觉推理和解释生成方面表现出色，但它们尚未展现出处理复杂、细粒度和跨模态差异的能力，而这对于 robust 的OOC检测至关重要。

为克服这些限制，我们提出了EXCLAIM，这是一个基于检索的框架，旨在通过多模态事件和实体的多粒度索引来利用外部知识。我们的方法结合了多粒度上下文分析与多智能体推理架构，系统性地评估多模态新闻内容的一致性和完整性。

全面的实验验证了EXCLAIM的有效性和鲁棒性，与现有最优方法相比，其检测OOC虚假信息的准确率高出4.3%，同时提供了可解释且可操作的见解。

> Misinformation continues to pose a significant challenge in today's information ecosystem, profoundly shaping public perception and behavior. Among its various manifestations, Out-of-Context (OOC) misinformation is particularly obscure, as it distorts meaning by pairing authentic images with misleading textual narratives. Existing methods for detecting OOC misinformation predominantly rely on coarse-grained similarity metrics between image-text pairs, which often fail to capture subtle inconsistencies or provide meaningful explainability. While multi-modal large language models (MLLMs) demonstrate remarkable capabilities in visual reasoning and explanation generation, they have not yet demonstrated the capacity to address complex, fine-grained, and cross-modal distinctions necessary for robust OOC detection. To overcome these limitations, we introduce EXCLAIM, a retrieval-based framework designed to leverage external knowledge through multi-granularity index of multi-modal events and entities. Our approach integrates multi-granularity contextual analysis with a multi-agent reasoning architecture to systematically evaluate the consistency and integrity of multi-modal news content. Comprehensive experiments validate the effectiveness and resilience of EXCLAIM, demonstrating its ability to detect OOC misinformation with 4.3% higher accuracy compared to state-of-the-art approaches, while offering explainable and actionable insights.

[Arxiv](https://arxiv.org/abs/2504.06269)
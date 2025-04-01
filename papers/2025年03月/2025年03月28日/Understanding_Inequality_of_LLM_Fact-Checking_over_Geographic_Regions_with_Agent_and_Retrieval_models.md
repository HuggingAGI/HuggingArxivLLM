# 解析大型语言模型事实核查的地理区域差异：基于智能体与检索模型

发布时间：2025年03月28日

`LLM应用` `事实核查` `地理多样性`

> Understanding Inequality of LLM Fact-Checking over Geographic Regions with Agent and Retrieval models

# 摘要

> 事实核查是大型语言模型 (LLMs) 的一项潜在有用应用，用于对抗日益泛滥的虚假信息传播。然而，LLMs 的性能在不同地理区域之间存在差异。本文评估了开源和私有模型在多种地区和场景下的事实准确性。

我们使用一个包含 600 个经过事实核查的声明的数据集，该数据集在全球六个地区保持平衡。我们研究了三种事实核查声明的实验设置：(1) 仅提供声明本身，(2) 利用一个能够访问维基百科的基于 LLM 的代理，以及 (3) 在最佳情况下，使用配备官方事实核查的检索增强生成 (RAG) 系统。我们的研究发现，无论采用哪种场景和 LLM（包括 GPT-4、Claude Sonnet 和 LLaMA），来自全球北方的声明表现明显优于全球南方的声明。此外，在基于维基百科代理的更现实情况下，这一差距进一步扩大，表明过于通用的知识库在解决地区特定细微差别方面的能力有限。这些结果强调了更好地平衡数据集和制定强大检索策略的迫切需求，以提升 LLM 的事实核查能力，特别是在地理多样性背景下。


> Fact-checking is a potentially useful application of Large Language Models (LLMs) to combat the growing dissemination of disinformation. However, the performance of LLMs varies across geographic regions. In this paper, we evaluate the factual accuracy of open and private models across a diverse set of regions and scenarios.
  Using a dataset containing 600 fact-checked statements balanced across six global regions we examine three experimental setups of fact-checking a statement: (1) when just the statement is available, (2) when an LLM-based agent with Wikipedia access is utilized, and (3) as a best case scenario when a Retrieval-Augmented Generation (RAG) system provided with the official fact check is employed. Our findings reveal that regardless of the scenario and LLM used, including GPT-4, Claude Sonnet, and LLaMA, statements from the Global North perform substantially better than those from the Global South. Furthermore, this gap is broadened for the more realistic case of a Wikipedia agent-based system, highlighting that overly general knowledge bases have a limited ability to address region-specific nuances. These results underscore the urgent need for better dataset balancing and robust retrieval strategies to enhance LLM fact-checking capabilities, particularly in geographically diverse contexts.

[Arxiv](https://arxiv.org/abs/2503.22877)
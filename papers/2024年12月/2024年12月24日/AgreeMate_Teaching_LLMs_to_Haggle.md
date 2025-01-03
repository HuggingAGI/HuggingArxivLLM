# AgreeMate: 让大型语言模型学会讨价还价

发布时间：2024年12月24日

`Agent

理由：这篇论文介绍了AgreeMate框架，该框架旨在训练大型语言模型（LLMs）作为代理进行战略性价格谈判。论文强调了LLMs在模块化谈判架构中作为代理的表现，并通过提示工程、微调和思维链提示等技术提升了模型性能。因此，这篇论文主要关注的是将LLMs作为代理应用于特定任务（即价格谈判），属于Agent分类。` `电子商务`

> AgreeMate: Teaching LLMs to Haggle

# 摘要

> 我们推出了AgreeMate框架，旨在训练大型语言模型（LLMs）通过自然语言进行战略性价格谈判。该框架将最新技术应用于谈判场景，其中买卖双方通过自然语言进行粗略的讨价还价。我们特别展示了LLMs在模块化谈判架构中作为代理的表现，并通过提示工程、微调和思维链提示显著提升了模型性能，这些性能由新颖的指标衡量。此外，我们利用注意力探测技术揭示了模型在谈判过程中对标记间语义关系的关注。

> We introduce AgreeMate, a framework for training Large Language Models (LLMs) to perform strategic price negotiations through natural language. We apply recent advances to a negotiation setting where two agents (i.e. buyer or seller) use natural language to bargain on goods using coarse actions. Specifically, we present the performance of Large Language Models when used as agents within a decoupled (modular) bargaining architecture. We demonstrate that using prompt engineering, fine-tuning, and chain-of-thought prompting enhances model performance, as defined by novel metrics. We use attention probing to show model attention to semantic relationships between tokens during negotiations.

[Arxiv](https://arxiv.org/abs/2412.18690)
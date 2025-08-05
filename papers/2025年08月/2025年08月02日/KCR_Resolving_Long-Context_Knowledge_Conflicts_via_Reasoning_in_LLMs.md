# KCR：解决 LLMs 中的长上下文知识冲突问题

发布时间：2025年08月02日

`LLM应用` `知识管理` `人工智能`

> KCR: Resolving Long-Context Knowledge Conflicts via Reasoning in LLMs

# 摘要

> 知识冲突在多种来源中普遍存在，尤其在大型语言模型（LLMs）出现后更为频繁。面对多个上下文之间的冲突（即跨上下文知识冲突），LLMs往往因冗长且矛盾的上下文而困惑。为解决这一难题，我们提出了知识冲突推理（KCR）框架，旨在提升LLMs处理相互冲突知识的能力。

KCR的核心思想是通过奖励机制训练主模型选择并坚持逻辑一致性更强的上下文，从而建立正确的推理过程。具体而言，我们首先从相互冲突的长上下文中提取推理路径，这些推理路径可以是文本或局部知识图谱。随后，我们采用强化学习来鼓励模型学习遵循正确推理路径的推理范式，而非错误的对比。这使得主模型能够真正掌握在长上下文中解决跨上下文知识冲突的能力。

实验结果表明，我们的框架显著提升了多种主模型在长上下文场景中解决知识冲突的能力，带来了显著的性能提升。

> Knowledge conflicts commonly arise across diverse sources, and their prevalence has increased with the advent of LLMs. When dealing with conflicts between multiple contexts, also known as \emph{inter-context knowledge conflicts}, LLMs are often confused by lengthy and conflicting contexts. To address this challenge, we propose the Knowledge Conflict Reasoning (KCR) framework, which enhances the ability of LLMs to resolve conflicting knowledge. The key idea of KCR is to train backbone LLMs to establish a correct reasoning process by rewarding them for selecting and adhering to the context with stronger logical consistency when presented with conflicting contexts. Specifically, we first extract reasoning paths, represented by either text or local knowledge graphs, from the conflicting long contexts. Subsequently, we employ Reinforcement Learning to encourage the model to learn the paradigm of reasoning process that follows correct reasoning paths rather than the incorrect counterparts. This enables the backbone models to genuinely acquire the capability to resolve inter-context knowledge conflicts within long contexts. Experimental results demonstrate that our framework significantly improves the ability of various backbone models to resolve knowledge conflicts in long-context scenarios, yielding substantial performance gains.

[Arxiv](https://arxiv.org/abs/2508.01273)
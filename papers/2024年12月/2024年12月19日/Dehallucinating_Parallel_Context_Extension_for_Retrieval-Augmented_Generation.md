# 用于检索增强生成的消除幻觉并行上下文扩展

发布时间：2024年12月19日

`RAG` `语言模型` `信息处理`

> Dehallucinating Parallel Context Extension for Retrieval-Augmented Generation

# 摘要

> 大型语言模型（LLMs）即便整合了检索增强生成（RAG），仍易产生幻觉信息。并行上下文扩展（PCE）致力于有效整合并行（无序）上下文，然而在适配 RAG 场景时仍饱受幻觉困扰。本文中，我们提出了 DePaC（消除并行上下文扩展中的幻觉），借助上下文感知的负训练和信息校准聚合来减轻幻觉问题。DePaC 旨在化解两类上下文幻觉：事实虚构（即 LLMs 给出无上下文支撑的主张）和事实遗漏（即 LLMs 未能给出有上下文支持的主张）。具体来说，（1）针对事实虚构，我们采用上下文感知的负训练，通过负监督对 LLMs 进行微调，明确引导 LLMs 在上下文与问题无关时拒绝作答；（2）针对事实遗漏，我们提出信息校准聚合，优先考虑相对于其上下文具有更高信息增量的上下文窗口。在九个 RAG 任务上的实验结果显示，DePaC 显著减轻了这两类幻觉，且在这些任务上始终表现更优。

> Large language models (LLMs) are susceptible to generating hallucinated information, despite the integration of retrieval-augmented generation (RAG). Parallel context extension (PCE) is a line of research attempting to effectively integrating parallel (unordered) contexts, while it still suffers from hallucinations when adapted to RAG scenarios. In this paper, we propose DePaC (Dehallucinating Parallel Context Extension), which alleviates the hallucination problem with context-aware negative training and information-calibrated aggregation. DePaC is designed to alleviate two types of in-context hallucination: fact fabrication (i.e., LLMs present claims that are not supported by the contexts) and fact omission (i.e., LLMs fail to present claims that can be supported by the contexts). Specifically, (1) for fact fabrication, we apply the context-aware negative training that fine-tunes the LLMs with negative supervisions, thus explicitly guiding the LLMs to refuse to answer when contexts are not related to questions; (2) for fact omission, we propose the information-calibrated aggregation which prioritizes context windows with higher information increment from their contexts. The experimental results on nine RAG tasks demonstrate that DePaC significantly alleviates the two types of hallucination and consistently achieves better performances on these tasks.

[Arxiv](https://arxiv.org/abs/2412.14905)
# RAG-Instruct: 利用多样化检索增强指令提升LLMs性能

发布时间：2024年12月31日

`RAG

理由：该论文主要讨论了检索增强生成（RAG）方法，并提出了一种新的方法RAG-Instruct来生成多样且高质量的RAG指令数据。论文的核心内容围绕如何提升RAG的能力，并通过实验验证了其方法的有效性。因此，该论文应归类为RAG。` `信息检索`

> RAG-Instruct: Boosting LLMs with Diverse Retrieval-Augmented Instructions

# 摘要

> 检索增强生成（RAG）通过整合外部知识，已成为提升大型语言模型（LLMs）能力的重要范式。然而，现有RAG方法存在两大局限：（1）覆盖场景有限；（2）因缺乏通用数据集，任务多样性不足。为此，我们提出了RAG-Instruct，一种基于任意源语料库生成多样且高质量RAG指令数据的通用方法。该方法结合了五种涵盖多种查询-文档关系的RAG范式，并通过指令模拟提升指令的多样性和质量。基于此，我们从维基百科构建了一个包含40K指令的数据集，全面覆盖了各类RAG场景和任务。实验证明，RAG-Instruct显著提升了LLMs的RAG能力，在零-shot任务中表现优异，并在多种任务上大幅超越现有RAG基线。RAG-Instruct已开源，详见https://github.com/FreedomIntelligence/RAG-Instruct。

> Retrieval-Augmented Generation (RAG) has emerged as a key paradigm for enhancing large language models (LLMs) by incorporating external knowledge. However, current RAG methods face two limitations: (1) they only cover limited RAG scenarios. (2) They suffer from limited task diversity due to the lack of a general RAG dataset. To address these limitations, we propose RAG-Instruct, a general method for synthesizing diverse and high-quality RAG instruction data based on any source corpus. Our approach leverages (1) five RAG paradigms, which encompass diverse query-document relationships, and (2) instruction simulation, which enhances instruction diversity and quality by utilizing the strengths of existing instruction datasets. Using this method, we construct a 40K instruction dataset from Wikipedia, comprehensively covering diverse RAG scenarios and tasks. Experiments demonstrate that RAG-Instruct effectively enhances LLMs' RAG capabilities, achieving strong zero-shot performance and significantly outperforming various RAG baselines across a diverse set of tasks. RAG-Instruct is publicly available at https://github.com/FreedomIntelligence/RAG-Instruct.

[Arxiv](https://arxiv.org/abs/2501.00353)
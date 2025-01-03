# SimRAG: 自优化检索增强生成，助力大型语言模型精准适配专业领域

发布时间：2024年10月23日

`RAG

理由：这篇论文主要讨论了检索增强生成（RAG）在特定领域（如科学和医学）中的应用，并提出了一种自训练方法（SimRAG）来提升LLM在领域特定RAG任务中的表现。论文的核心内容围绕如何通过RAG技术增强LLM的问答能力，因此应归类为RAG。`

> SimRAG: Self-Improving Retrieval-Augmented Generation for Adapting Large Language Models to Specialized Domains

# 摘要

> 检索增强生成（RAG）通过整合外部知识，显著提升了大型语言模型（LLMs）的问答（QA）能力。然而，将通用RAG系统应用于科学和医学等专业领域时，由于数据分布变化和领域特定数据的稀缺，带来了独特挑战。为此，我们提出了SimRAG，一种自训练方法，赋予LLM问答和问题生成的联合能力，以适应特定领域。我们的方法首先在指令遵循、问答和搜索相关数据上对LLM进行微调，然后利用同一LLM从未标记的语料库中生成多样化的领域相关问题，并通过过滤策略保留高质量的合成示例。这些合成示例显著提升了LLM在领域特定RAG任务中的表现。在11个数据集上的实验，涵盖两个骨干模型大小和三个领域，结果显示SimRAG比基线模型高出1.2\%--8.6\%。

> Retrieval-augmented generation (RAG) enhances the question-answering (QA) abilities of large language models (LLMs) by integrating external knowledge. However, adapting general-purpose RAG systems to specialized fields such as science and medicine poses unique challenges due to distribution shifts and limited access to domain-specific data. To tackle this, we propose SimRAG, a self-training approach that equips the LLM with joint capabilities of question answering and question generation for domain adaptation. Our method first fine-tunes the LLM on instruction-following, question-answering, and search-related data. Then, it prompts the same LLM to generate diverse domain-relevant questions from unlabeled corpora, with an additional filtering strategy to retain high-quality synthetic examples. By leveraging these synthetic examples, the LLM can improve their performance on domain-specific RAG tasks. Experiments on 11 datasets, spanning two backbone sizes and three domains, demonstrate that SimRAG outperforms baselines by 1.2\%--8.6\%.

[Arxiv](https://arxiv.org/abs/2410.17952)
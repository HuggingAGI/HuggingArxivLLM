# # 系统性知识注入：通过多样化增强实现领域特定 RAG 的大型语言模型知识注入

发布时间：2025年02月12日

`RAG` `通用领域`

> Systematic Knowledge Injection into Large Language Models via Diverse Augmentation for Domain-Specific RAG

# 摘要

> 检索增强生成（RAG）作为一种新兴且有效的方法，能够将领域知识融入大型语言模型（LLMs）。虽然RAG通过在上下文中引入检索到的领域知识提升了回答的相关性，但检索错误仍然可能导致幻觉现象和错误答案。为了解决检索器失效的问题，我们通过微调模型来注入领域知识，使其即使在检索出错时也能生成正确答案。然而，我们发现，如果没有系统性的知识增强，微调后的LLMs可能会记住新信息，但仍然无法有效提取相关领域知识，导致性能不佳。针对这一问题，本研究提出了一种全新的框架，通过两种方式对训练数据进行增强，从而显著提升微调效果——上下文增强和知识改写。在上下文增强中，我们为每个问答对生成多个训练样本，通过改变检索信息的相关性，教导模型何时应忽略检索内容、何时应依赖检索内容。在知识改写中，我们使用同一问题的多个答案进行微调，帮助大语言模型更好地内化专业知识。为了缓解微调带来的灾难性遗忘问题，我们在问题中添加领域特定标识符，并引入一个包含通用问答对的回放缓存。实验结果表明，与现有技术相比，我们的方法在保持LLMs泛化能力的同时，实现了高达10%的相对token级召回率提升，充分验证了方法的有效性。

> Retrieval-Augmented Generation (RAG) has emerged as a prominent method for incorporating domain knowledge into Large Language Models (LLMs). While RAG enhances response relevance by incorporating retrieved domain knowledge in the context, retrieval errors can still lead to hallucinations and incorrect answers. To recover from retriever failures, domain knowledge is injected by fine-tuning the model to generate the correct response, even in the case of retrieval errors. However, we observe that without systematic knowledge augmentation, fine-tuned LLMs may memorize new information but still fail to extract relevant domain knowledge, leading to poor performance. In this work, we present a novel framework that significantly enhances the fine-tuning process by augmenting the training data in two ways -- context augmentation and knowledge paraphrasing. In context augmentation, we create multiple training samples for a given QA pair by varying the relevance of the retrieved information, teaching the model when to ignore and when to rely on retrieved content. In knowledge paraphrasing, we fine-tune with multiple answers to the same question, enabling LLMs to better internalize specialized knowledge. To mitigate catastrophic forgetting due to fine-tuning, we add a domain-specific identifier to a question and also utilize a replay buffer containing general QA pairs. Experimental results demonstrate the efficacy of our method over existing techniques, achieving up to 10\% relative gain in token-level recall while preserving the LLM's generalization capabilities.

[Arxiv](https://arxiv.org/abs/2502.08356)
# 借助作者特征与对比示例，优化RAG的个性化能力

发布时间：2025年03月23日

`RAG` `个性化内容生成`

> Improving RAG for Personalization with Author Features and Contrastive Examples

# 摘要

> 检索增强生成（RAG）的个性化生成难以捕捉作者的细粒度特征，导致难以识别其独特风格。为丰富 RAG 的上下文信息，我们提出在提供作者档案过往样本的同时，向大型语言模型（LLMs）添加作者特定特征，如平均情感极性及常用词汇。我们引入了“对比示例”这一新特征：通过检索其他作者的文档，帮助 LLM 识别某位作者的独特风格。实验表明，添加关于命名实体、依赖关系模式及常用词汇的几句话，显著提升了个性化文本生成效果。将特征与对比示例结合，性能进一步提升，在基准 RAG 的基础上实现 15% 的相对提升，超越现有基准。我们的研究不仅突显了细粒度特征在实现更好个性化中的价值，还为引入对比示例作为 RAG 的补充开辟了新方向。我们已公开发布了代码。


> Personalization with retrieval-augmented generation (RAG) often fails to capture fine-grained features of authors, making it hard to identify their unique traits. To enrich the RAG context, we propose providing Large Language Models (LLMs) with author-specific features, such as average sentiment polarity and frequently used words, in addition to past samples from the author's profile. We introduce a new feature called Contrastive Examples: documents from other authors are retrieved to help LLM identify what makes an author's style unique in comparison to others. Our experiments show that adding a couple of sentences about the named entities, dependency patterns, and words a person uses frequently significantly improves personalized text generation. Combining features with contrastive examples boosts the performance further, achieving a relative 15% improvement over baseline RAG while outperforming the benchmarks. Our results show the value of fine-grained features for better personalization, while opening a new research dimension for including contrastive examples as a complement with RAG. We release our code publicly.

[Arxiv](https://arxiv.org/abs/2504.08745)
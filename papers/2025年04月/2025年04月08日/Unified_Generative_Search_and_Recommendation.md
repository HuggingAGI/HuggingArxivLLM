# # 统一生成式搜索与推荐系统

发布时间：2025年04月08日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLMs）驱动的生成检索技术来平衡搜索和推荐任务。它提出了一个统一的生成框架GenSAR，用于解决搜索和推荐之间的权衡问题。因此，它属于LLM应用类别，因为它展示了LLMs在实际应用中的具体应用和效果。` `电子商务` `推荐系统`

> Unified Generative Search and Recommendation

# 摘要

> 现代商业平台通常同时提供搜索和推荐功能，以满足多样化的用户需求，因此将这两个任务联合建模成为一个吸引人的研究方向。尽管先前的研究表明，整合搜索和推荐可以实现互惠互利，但也揭示了性能上的权衡：一个任务的改进往往以另一个任务的牺牲为代价。这一挑战源于它们不同的信息需求：搜索强调查询与项目之间的语义相关性，而推荐更依赖于用户与项目之间的协同信号。有效解决这一权衡需要解决两个关键问题：（1）将语义和协同信号整合到项目表示中，（2）引导模型区分并适应搜索和推荐的独特需求。大型语言模型（LLMs）驱动的生成检索技术的出现带来了新的可能性。这一范式将项目编码为标识符，并将搜索和推荐都视为序列生成任务，提供了灵活利用多个标识符和任务特定提示的能力。基于此，我们提出了GenSAR，一个用于平衡搜索和推荐的统一生成框架。我们的方法设计了双用途标识符和定制化训练策略，以整合互补信号并适应任务特定目标。在公共数据集和商业数据集上的实验表明，GenSAR有效减少了权衡，并在两个任务上实现了最先进的性能。

> Modern commercial platforms typically offer both search and recommendation functionalities to serve diverse user needs, making joint modeling of these tasks an appealing direction. While prior work has shown that integrating search and recommendation can be mutually beneficial, it also reveals a performance trade-off: enhancements in one task often come at the expense of the other. This challenge arises from their distinct information requirements: search emphasizes semantic relevance between queries and items, whereas recommendation depends more on collaborative signals among users and items. Effectively addressing this trade-off requires tackling two key problems: (1) integrating both semantic and collaborative signals into item representations, and (2) guiding the model to distinguish and adapt to the unique demands of search and recommendation. The emergence of generative retrieval with Large Language Models (LLMs) presents new possibilities. This paradigm encodes items as identifiers and frames both search and recommendation as sequential generation tasks, offering the flexibility to leverage multiple identifiers and task-specific prompts. In light of this, we introduce GenSAR, a unified generative framework for balanced search and recommendation. Our approach designs dual-purpose identifiers and tailored training strategies to incorporate complementary signals and align with task-specific objectives. Experiments on both public and commercial datasets demonstrate that GenSAR effectively reduces the trade-off and achieves state-of-the-art performance on both tasks.

[Arxiv](https://arxiv.org/abs/2504.05730)
# TagRouter：利用标签学习通向大型语言模型的路径，专为开放领域文本生成任务设计。

发布时间：2025年06月14日

`LLM应用` `模型集成` `模型优化`

> TagRouter: Learning Route to LLMs through Tags for Open-Domain Text Generation Tasks

# 摘要

> 模型路由通过将查询分配到合适的模型，在提升系统性能的同时降低成本。然而，现有的路由方法在实际应用中存在局限性，难以在大规模应用中扩展，也无法跟上 LLM 生态系统的快速发展。为了解决这些问题，我们提出了无需训练的 TagRouter 方法，旨在优化多个 LLM 在开放领域文本生成任务中的协同工作。实验结果表明，TagRouter 在性能上超越了 13 种基线方法，使系统接受率提高了 6.15%，成本降低了 17.20%，达到了最优的成本效益。我们的研究为 LLM 社区提供了一个高效且可扩展的模型集成解决方案，为用户提供了可演进的“超级模型”。

> Model routing allocates queries to the suitable model, improving system performance while reducing costs. However, existing routing methods face practical limitations that hinder scalability in large-scale applications and struggle to keep up with the rapid growth of the large language model (LLM) ecosystem. To tackle these challenges, we propose TagRouter, a training-free model routing method designed to optimize the synergy among multiple LLMs for open-domain text generation tasks. Experimental results demonstrate that TagRouter outperforms 13 baseline methods, increasing the accept rate of system by 6.15% and reducing costs by 17.20%, achieving optimal cost-efficiency. Our findings provides the LLM community with an efficient and scalable solution for model ensembling, offering users an evolvable "super model."

[Arxiv](https://arxiv.org/abs/2506.12473)
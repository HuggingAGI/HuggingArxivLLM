# ProRank：基于强化学习的小语言模型提示预热与重排序

发布时间：2025年06月03日

`RAG` `信息检索`

> ProRank: Prompt Warmup via Reinforcement Learning for Small Language Models Reranking

# 摘要

> 重排序是信息检索和检索增强生成的关键，大型语言模型（LLMs）的出现显著提升了重排序质量。尽管LLMs在文档重排序方面取得了显著进展，但现有方法主要依赖于大规模LLMs（>70亿参数）通过零样本提示实现，导致高昂的计算成本。小型语言模型（SLMs）因其高效性提供了一个有前景的替代方案，但我们的初步分析表明，它们在未经微调的情况下难以理解任务提示，这限制了它们在文档重排序任务中的有效性。为了解决这一问题，我们提出了一种基于SLM的文档重排序新型两阶段训练方法——ProRank。首先，我们提出使用强化学习GRPO的提示预热阶段，引导SLMs理解任务提示，并为文档重排序生成更准确的粗粒度相关性二元评分。然后，我们通过细粒度评分学习阶段持续微调SLMs，无需添加额外层，进一步提升重排序质量。全面的实验结果表明，所提出的ProRank在开源和专有重排序模型中始终表现出色。值得注意的是，我们的轻量级ProRank-0.5B模型甚至在BEIR基准上超越了强大的320亿参数LLM重排序模型，证明了经过适当训练的SLMs可以在保持计算效率的同时实现优越的文档重排序性能。

> Reranking is fundamental to information retrieval and retrieval-augmented generation, with recent Large Language Models (LLMs) significantly advancing reranking quality. While recent advances with LLMs have significantly improved document reranking quality, current approaches primarily rely on large-scale LLMs (>7B parameters) through zero-shot prompting, presenting high computational costs. Small Language Models (SLMs) offer a promising alternative because of their efficiency, but our preliminary quantitative analysis reveals they struggle with understanding task prompts without fine-tuning. This limits their effectiveness for document reranking tasks. To address this issue, we introduce a novel two-stage training approach, ProRank, for SLM-based document reranking. First, we propose a prompt warmup stage using reinforcement learning GRPO to steer SLMs to understand task prompts and generate more accurate coarse-grained binary relevance scores for document reranking. Then, we continuously fine-tune the SLMs with a fine-grained score learning stage without introducing additional layers to further improve the reranking quality. Comprehensive experimental results demonstrate that the proposed ProRank consistently outperforms both the most advanced open-source and proprietary reranking models. Notably, our lightweight ProRank-0.5B model even surpasses the powerful 32B LLM reranking model on the BEIR benchmark, establishing that properly trained SLMs can achieve superior document reranking performance while maintaining computational efficiency.

[Arxiv](https://arxiv.org/abs/2506.03487)
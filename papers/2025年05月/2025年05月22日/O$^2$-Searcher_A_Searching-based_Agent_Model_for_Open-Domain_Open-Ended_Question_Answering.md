# O平方搜索者：面向开放领域开放性问答的基于搜索的智能体模型

发布时间：2025年05月22日

`Agent` `问答系统`

> O$^2$-Searcher: A Searching-based Agent Model for Open-Domain Open-Ended Question Answering

# 摘要

> 大型语言模型 (LLMs) 尽管性能卓越，但其静态知识参数从根本上限制了其在需要开放领域实时信息的任务中的表现。虽然让 LLMs 与外部知识环境交互是一个有前景的解决方案，但目前的研究主要集中在封闭式问题上。对于缺乏标准答案或提供非唯一、多样化答案的开放性问题，研究仍然不足。为了解决这一问题，我们提出了 O$^2$-Searcher，这是一种基于强化学习的新型搜索代理，能够有效处理开放领域的开放式和封闭式问题。O$^2$-Searcher 通过利用高效的本地模拟搜索环境实现动态知识获取，成功将外部世界知识与模型复杂的推理过程解耦。它采用统一的训练机制，结合精心设计的奖励函数，使代理能够识别问题类型并灵活调整答案生成策略。为了评估在复杂开放式任务中的性能，我们构建了 O$^2$-QA，这是一个高质量的基准测试，包含 300 个手动精选的多领域开放式问题，每个问题都附带相关的网页缓存。实验结果表明，仅使用 3B 规模的模型，O$^2$-Searcher 在 O$^2$-QA 上显著超越了现有的 LLM 代理。它还在多种封闭式问答基准测试中对同样规模的模型实现了最优性能，甚至与更大规模的模型表现相当。

> Large Language Models (LLMs), despite their advancements, are fundamentally limited by their static parametric knowledge, hindering performance on tasks requiring open-domain up-to-date information. While enabling LLMs to interact with external knowledge environments is a promising solution, current efforts primarily address closed-end problems. Open-ended questions, which characterized by lacking a standard answer or providing non-unique and diverse answers, remain underexplored. To bridge this gap, we present O$^2$-Searcher, a novel search agent leveraging reinforcement learning to effectively tackle both open-ended and closed-ended questions in the open domain. O$^2$-Searcher leverages an efficient, locally simulated search environment for dynamic knowledge acquisition, effectively decoupling the external world knowledge from model's sophisticated reasoning processes. It employs a unified training mechanism with meticulously designed reward functions, enabling the agent to identify problem types and adapt different answer generation strategies. Furthermore, to evaluate performance on complex open-ended tasks, we construct O$^2$-QA, a high-quality benchmark featuring 300 manually curated, multi-domain open-ended questions with associated web page caches. Extensive experiments show that O$^2$-Searcher, using only a 3B model, significantly surpasses leading LLM agents on O$^2$-QA. It also achieves SOTA results on various closed-ended QA benchmarks against similarly-sized models, while performing on par with much larger ones.

[Arxiv](https://arxiv.org/abs/2505.16582)
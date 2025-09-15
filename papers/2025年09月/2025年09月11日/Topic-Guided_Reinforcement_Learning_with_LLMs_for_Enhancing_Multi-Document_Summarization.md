# 主题引导强化学习与LLMs：增强多文档摘要

发布时间：2025年09月11日

`强化学习` `基础理论`

> Topic-Guided Reinforcement Learning with LLMs for Enhancing Multi-Document Summarization

# 摘要

> 多文档摘要（MDS）的核心难题在于如何高效整合多源信息，同时确保连贯性与主题相关性。尽管大型语言模型在单文档摘要任务中表现出色，但它们在MDS上的性能仍有提升余地。本文提出一种主题引导的强化学习方法，以改进MDS的内容选择。我们首先证明，用主题标签明确提示模型可提升生成摘要的信息量。基于这一发现，我们在群体相对策略优化（GRPO）框架中设计了一种新的主题奖励机制，用于衡量生成摘要与源文档的主题对齐程度。在Multi-News和Multi-XScience数据集上的实验结果显示，我们的方法显著且持续优于强基线，充分证明了在MDS中利用主题线索的有效性。

> A key challenge in Multi-Document Summarization (MDS) is effectively integrating information from multiple sources while maintaining coherence and topical relevance. While Large Language Models have shown impressive results in single-document summarization, their performance on MDS still leaves room for improvement. In this paper, we propose a topic-guided reinforcement learning approach to improve content selection in MDS. We first show that explicitly prompting models with topic labels enhances the informativeness of the generated summaries. Building on this insight, we propose a novel topic reward within the Group Relative Policy Optimization (GRPO) framework to measure topic alignment between the generated summary and source documents. Experimental results on the Multi-News and Multi-XScience datasets demonstrate that our method consistently outperforms strong baselines, highlighting the effectiveness of leveraging topical cues in MDS.

[Arxiv](https://arxiv.org/abs/2509.09852)
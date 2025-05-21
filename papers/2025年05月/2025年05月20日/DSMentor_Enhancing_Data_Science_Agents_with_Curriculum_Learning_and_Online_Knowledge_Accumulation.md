# DSMentor：基于课程学习与在线知识积累的数据科学代理增强方法

发布时间：2025年05月20日

`LLM应用` `数据科学`

> DSMentor: Enhancing Data Science Agents with Curriculum Learning and Online Knowledge Accumulation

# 摘要

> 大型语言模型（LLM）代理在生成解决复杂数据科学问题的代码方面表现优异。尽管近期研究主要致力于通过改进搜索、采样和规划技术来优化上下文学习，但对推理过程中解决问题顺序的重要性却鲜有关注。针对这一问题，我们提出了名为DSMentor的创新推理时优化框架，该框架采用课程学习策略——即先从简单任务入手，随着学习者进步逐步增加任务难度——来提升LLM代理在复杂数据科学任务中的表现。我们的框架通过将数据科学任务按难度排序，并结合不断扩展的长期记忆来保存过往经验，从而有效引导代理的学习进程并提升知识利用效率。在DSEval和QRData基准上的大量实验表明，DSMentor相较于基线代理，使用Claude-3.5-Sonnet时的通过率提升了5.2%。此外，在因果推理任务中，DSMentor的表现尤为突出，相较于使用Program-of-Thoughts提示的GPT-4，通过率提升了8.8%。本研究强调了在推理过程中开发有效知识积累与利用策略的重要性，这一过程模拟了人类的学习模式，为通过基于课程的推理优化提升LLM性能提供了全新思路。

> Large language model (LLM) agents have shown promising performance in generating code for solving complex data science problems. Recent studies primarily focus on enhancing in-context learning through improved search, sampling, and planning techniques, while overlooking the importance of the order in which problems are tackled during inference. In this work, we develop a novel inference-time optimization framework, referred to as DSMentor, which leverages curriculum learning -- a strategy that introduces simpler task first and progressively moves to more complex ones as the learner improves -- to enhance LLM agent performance in challenging data science tasks. Our mentor-guided framework organizes data science tasks in order of increasing difficulty and incorporates a growing long-term memory to retain prior experiences, guiding the agent's learning progression and enabling more effective utilization of accumulated knowledge. We evaluate DSMentor through extensive experiments on DSEval and QRData benchmarks. Experiments show that DSMentor using Claude-3.5-Sonnet improves the pass rate by up to 5.2% on DSEval and QRData compared to baseline agents. Furthermore, DSMentor demonstrates stronger causal reasoning ability, improving the pass rate by 8.8% on the causality problems compared to GPT-4 using Program-of-Thoughts prompts. Our work underscores the importance of developing effective strategies for accumulating and utilizing knowledge during inference, mirroring the human learning process and opening new avenues for improving LLM performance through curriculum-based inference optimization.

[Arxiv](https://arxiv.org/abs/2505.14163)
# 个性化对话基准——探索个性化对话的模拟

发布时间：2025年05月20日

`LLM应用` `对话系统` `基准测试`

> A Personalized Conversational Benchmark: Towards Simulating Personalized Conversations

# 摘要

> 我们推出了PersonaConvBench，一个用于评估大型语言模型（LLMs）在多轮对话中个性化推理与生成能力的大型基准测试。与现有工作不同，现有的工作往往孤立地关注个性化或对话结构中的某一方面，而PersonaConvBench将两者结合起来，提供了三个核心任务：句子分类、影响回归以及以用户为中心的文本生成，覆盖了基于Reddit的十个多样化领域。这种设计使得我们能够系统性地分析个性化对话背景如何在现实的多用户场景下影响LLM的输出。我们在统一的提示设置下对多个商用和开源的LLMs进行了基准测试，发现引入个性化历史记录带来了显著的性能提升，包括在情感分类任务中相较于最佳非对话基准模型，相对提升了198%。通过发布PersonaConvBench，包括评估和代码，我们希望支持那些能够适应个体风格、追踪长期背景并生成内容丰富且引人入胜的响应的LLMs研究。

> We present PersonaConvBench, a large-scale benchmark for evaluating personalized reasoning and generation in multi-turn conversations with large language models (LLMs). Unlike existing work that focuses on either personalization or conversational structure in isolation, PersonaConvBench integrates both, offering three core tasks: sentence classification, impact regression, and user-centric text generation across ten diverse Reddit-based domains. This design enables systematic analysis of how personalized conversational context shapes LLM outputs in realistic multi-user scenarios. We benchmark several commercial and open-source LLMs under a unified prompting setup and observe that incorporating personalized history yields substantial performance improvements, including a 198 percent relative gain over the best non-conversational baseline in sentiment classification. By releasing PersonaConvBench with evaluations and code, we aim to support research on LLMs that adapt to individual styles, track long-term context, and produce contextually rich, engaging responses.

[Arxiv](https://arxiv.org/abs/2505.14106)
# # 提升与评测面向大型语言模型的个性化工具调用

发布时间：2025年05月06日

`LLM应用

摘要讨论了大型语言模型（LLMs）在工具调用方面的应用，特别是个性化工具调用的概念和框架PTool，以及基准测试PTBench的构建。这些内容属于LLMs的应用研究，因此归类为LLM应用。` `电子商务` `推荐系统`

> Advancing and Benchmarking Personalized Tool Invocation for LLMs

# 摘要

> 工具调用是扩展大型语言模型（LLMs）能力的关键机制，近期受到了广泛关注。它使LLMs能够通过工具调用解决复杂问题并访问最新世界知识。然而，现有研究主要关注LLMs调用工具解决问题的基本能力，而忽略了工具调用中的个性化约束。在本研究中，我们提出个性化工具调用的概念，并定义了两个关键任务：工具偏好和基于用户画像的查询。工具偏好关注用户在选择功能相似工具时的偏好，而基于用户画像的查询则处理用户查询缺少某些工具参数的情况，需要模型从用户画像中推断这些参数。为解决这些挑战，我们提出了PTool，一个专为个性化工具调用设计的数据合成框架。此外，我们构建了	extbf{PTBench}，这是首个用于评估个性化工具调用的基准测试。通过微调各种开源模型，我们验证了我们框架的有效性，并为该领域提供了有价值的见解。我们的基准测试已公开，地址为https://github.com/hyfshadow/PTBench。

> Tool invocation is a crucial mechanism for extending the capabilities of Large Language Models (LLMs) and has recently garnered significant attention. It enables LLMs to solve complex problems through tool calls while accessing up-to-date world knowledge. However, existing work primarily focuses on the fundamental ability of LLMs to invoke tools for problem-solving, without considering personalized constraints in tool invocation. In this work, we introduce the concept of Personalized Tool Invocation and define two key tasks: Tool Preference and Profile-dependent Query. Tool Preference addresses user preferences when selecting among functionally similar tools, while Profile-dependent Query considers cases where a user query lacks certain tool parameters, requiring the model to infer them from the user profile. To tackle these challenges, we propose PTool, a data synthesis framework designed for personalized tool invocation. Additionally, we construct \textbf{PTBench}, the first benchmark for evaluating personalized tool invocation. We then fine-tune various open-source models, demonstrating the effectiveness of our framework and providing valuable insights. Our benchmark is public at https://github.com/hyfshadow/PTBench.

[Arxiv](https://arxiv.org/abs/2505.04072)
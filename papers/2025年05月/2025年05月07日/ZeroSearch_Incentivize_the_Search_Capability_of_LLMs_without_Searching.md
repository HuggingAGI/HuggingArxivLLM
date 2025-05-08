# 零搜索：激发LLMs的搜索潜能，无需实际搜索

发布时间：2025年05月07日

`LLM应用

摘要中提到的研究重点在于提升大型语言模型的推理和生成能力，特别是通过强化学习框架（ZeroSearch）来优化检索机制。这属于大型语言模型的应用研究，因此归类为LLM应用。` `信息检索`

> ZeroSearch: Incentivize the Search Capability of LLMs without Searching

# 摘要

> 提升大型语言模型 (LLMs) 的推理与生成能力，离不开高效的检索机制。近期研究尝试通过强化学习 (RL) 与实时搜索引擎互动来优化 LLMs 的搜索能力，但这一方法面临两大难题：文档质量不可控和 API 成本过高。为突破这些限制，我们提出了 ZeroSearch，一个无需真实搜索引擎参与的强化学习框架，旨在激发 LLMs 的检索潜力。我们的方法从轻量级监督微调入手，将 LLM 转化为一个既能生成相关文档也能生成噪声文档的检索模块。在 RL 训练中，我们采用渐进式课程策略，逐步降低生成文档质量，通过不断挑战模型的检索能力，最终使其推理能力得到显著提升。实验结果表明，ZeroSearch 采用 3B LLM 作为检索模块时表现优异。更令人惊喜的是，7B 模块可匹敌真实搜索引擎，而 14B 模块更是超越了它。此外，ZeroSearch 在各类参数规模的基模型和指令微调模型上均表现出色，且与多种 RL 算法无缝兼容，展现了强大的通用性和扩展性。

> Effective information searching is essential for enhancing the reasoning and generation capabilities of large language models (LLMs). Recent research has explored using reinforcement learning (RL) to improve LLMs' search capabilities by interacting with live search engines in real-world environments. While these approaches show promising results, they face two major challenges: (1) Uncontrolled Document Quality: The quality of documents returned by search engines is often unpredictable, introducing noise and instability into the training process. (2) Prohibitively High API Costs: RL training requires frequent rollouts, potentially involving hundreds of thousands of search requests, which incur substantial API expenses and severely constrain scalability. To address these challenges, we introduce ZeroSearch, a reinforcement learning framework that incentivizes the search capabilities of LLMs without interacting with real search engines. Our approach begins with lightweight supervised fine-tuning to transform the LLM into a retrieval module capable of generating both relevant and noisy documents in response to a query. During RL training, we employ a curriculum-based rollout strategy that incrementally degrades the quality of generated documents, progressively eliciting the model's reasoning ability by exposing it to increasingly challenging retrieval scenarios. Extensive experiments demonstrate that ZeroSearch effectively incentivizes the search capabilities of LLMs using a 3B LLM as the retrieval module. Remarkably, a 7B retrieval module achieves comparable performance to the real search engine, while a 14B retrieval module even surpasses it. Furthermore, it generalizes well across both base and instruction-tuned models of various parameter sizes and is compatible with a wide range of RL algorithms.

[Arxiv](https://arxiv.org/abs/2505.04588)
# 只见树木，不见森林：利用启发式方法和偏见，揭示LLMs的非理性决策

发布时间：2025年05月03日

`LLM应用` `人工智能安全`

> Cannot See the Forest for the Trees: Invoking Heuristics and Biases to Elicit Irrational Choices of LLMs

# 摘要

> 尽管大型语言模型（LLMs）表现卓越，但它们依然容易受到越狱攻击，这类攻击可能破坏其安全机制。现有研究通常依赖暴力优化或手动设计，未能揭示现实场景中的潜在风险。为解决这一问题，我们提出了一种基于人类认知中的启发式和偏见的新型越狱攻击框架ICRT。通过利用简单效应，我们采用认知分解来降低恶意提示的复杂性。同时，借助相关偏见，重新组织提示，增强语义对齐，有效诱导有害输出。此外，我们引入了一种基于排名的有害性评估指标，超越了传统的成功或失败二元范式，通过Elo、HodgeRank和Rank Centrality等排名聚合方法，全面量化生成内容的有害性。实验结果表明，我们的方法能够持续绕过主流LLMs的安全机制，生成高风险内容，为越狱攻击风险提供了新的见解，并为构建更强的安全防御策略做出了贡献。

> Despite the remarkable performance of Large Language Models (LLMs), they remain vulnerable to jailbreak attacks, which can compromise their safety mechanisms. Existing studies often rely on brute-force optimization or manual design, failing to uncover potential risks in real-world scenarios. To address this, we propose a novel jailbreak attack framework, ICRT, inspired by heuristics and biases in human cognition. Leveraging the simplicity effect, we employ cognitive decomposition to reduce the complexity of malicious prompts. Simultaneously, relevance bias is utilized to reorganize prompts, enhancing semantic alignment and inducing harmful outputs effectively. Furthermore, we introduce a ranking-based harmfulness evaluation metric that surpasses the traditional binary success-or-failure paradigm by employing ranking aggregation methods such as Elo, HodgeRank, and Rank Centrality to comprehensively quantify the harmfulness of generated content. Experimental results show that our approach consistently bypasses mainstream LLMs' safety mechanisms and generates high-risk content, providing insights into jailbreak attack risks and contributing to stronger defense strategies.

[Arxiv](https://arxiv.org/abs/2505.02862)
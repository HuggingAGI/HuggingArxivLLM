# CoIn：计数商业级不透明LLM API中的不可见推理标记数量

发布时间：2025年05月19日

`LLM应用

理由：这篇论文讨论了大型语言模型（LLMs）在实际应用中的计费透明度问题，并提出了一个审核框架CoIn来解决这一问题。它属于LLM的应用层面，因为它关注的是如何在实际服务中验证和审核LLM的使用情况，而不是理论上的模型改进或智能体的行为。`

> CoIn: Counting the Invisible Reasoning Tokens in Commercial Opaque LLM APIs

# 摘要

> 随着后训练技术的演进，大型语言模型 (LLMs) 日益被赋予结构化的多步推理能力，这些能力通常通过强化学习进行优化。这些增强推理能力的模型在复杂任务上表现优异，并支撑着许多商用的 LLM API。然而，为了保护专有行为并减少冗余，提供商通常隐藏推理轨迹，仅返回最终答案。这种不透明性带来了一个关键问题：用户为不可见的推理令牌付费，这些令牌通常占成本大头，却无法验证其真实性。这为令牌计数膨胀提供了可乘之机：提供商可能夸大令牌使用量或注入低效的合成令牌以增加费用。为了解决这一问题，我们提出了 CoIn，一个用于审核隐藏令牌数量和语义有效性的验证框架。CoIn 通过构建可验证的哈希树来检查令牌计数，利用令牌嵌入指纹，并使用基于嵌入的相关性匹配来检测伪造的推理内容。实验表明，CoIn 作为受信任的第三方审核工具，可以有效检测令牌计数膨胀，成功率高达 94.7%，展现出在不透明的 LLM 服务中恢复计费透明度的强大能力。数据集和代码可在 https://github.com/CASE-Lab-UMD/LLM-Auditing-CoIn 获取。

> As post-training techniques evolve, large language models (LLMs) are increasingly augmented with structured multi-step reasoning abilities, often optimized through reinforcement learning. These reasoning-enhanced models outperform standard LLMs on complex tasks and now underpin many commercial LLM APIs. However, to protect proprietary behavior and reduce verbosity, providers typically conceal the reasoning traces while returning only the final answer. This opacity introduces a critical transparency gap: users are billed for invisible reasoning tokens, which often account for the majority of the cost, yet have no means to verify their authenticity. This opens the door to token count inflation, where providers may overreport token usage or inject synthetic, low-effort tokens to inflate charges. To address this issue, we propose CoIn, a verification framework that audits both the quantity and semantic validity of hidden tokens. CoIn constructs a verifiable hash tree from token embedding fingerprints to check token counts, and uses embedding-based relevance matching to detect fabricated reasoning content. Experiments demonstrate that CoIn, when deployed as a trusted third-party auditor, can effectively detect token count inflation with a success rate reaching up to 94.7%, showing the strong ability to restore billing transparency in opaque LLM services. The dataset and code are available at https://github.com/CASE-Lab-UMD/LLM-Auditing-CoIn.

[Arxiv](https://arxiv.org/abs/2505.13778)
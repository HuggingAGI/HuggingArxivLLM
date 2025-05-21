# CoIn：揭秘商用黑箱LLM API中的隐形推理标记

发布时间：2025年05月19日

`LLM应用` `人工智能` `商业服务`

> CoIn: Counting the Invisible Reasoning Tokens in Commercial Opaque LLM APIs

# 摘要

> 随着后训练技术的演进，大型语言模型（LLMs）正越来越多地被赋予结构化的多步骤推理能力，这些能力通常通过强化学习进行优化。相比标准LLMs，这些推理增强型模型在复杂任务中表现更优，如今已成为众多商用LLM API的基石。然而，为了保护专有行为并减少冗余，服务提供商通常会隐藏推理过程，仅返回最终答案。这种不透明性造成了一个关键的透明度缺口：用户需为不可见的推理标记付费，这些标记往往占总成本的大多数，却无法验证其真实性。这为标记计数虚增打开了大门：提供商可能夸大标记使用量或注入合成的、低效的标记以虚增费用。为解决这一问题，我们提出CoIn，一个用于审核隐藏标记数量和语义有效性的验证框架。CoIn通过构建可验证的哈希树来检查标记数量，这些哈希树基于标记嵌入指纹生成；同时，它利用基于嵌入的相关性匹配来检测伪造的推理内容。实验表明，当作为受信任的第三方审核工具部署时，CoIn能够有效检测标记计数虚增，成功率高达94.7%，充分展示了其在恢复不透明LLM服务计费透明度方面的强大能力。数据集和代码可在https://github.com/CASE-Lab-UMD/LLM-Auditing-CoIn获取。

> As post-training techniques evolve, large language models (LLMs) are increasingly augmented with structured multi-step reasoning abilities, often optimized through reinforcement learning. These reasoning-enhanced models outperform standard LLMs on complex tasks and now underpin many commercial LLM APIs. However, to protect proprietary behavior and reduce verbosity, providers typically conceal the reasoning traces while returning only the final answer. This opacity introduces a critical transparency gap: users are billed for invisible reasoning tokens, which often account for the majority of the cost, yet have no means to verify their authenticity. This opens the door to token count inflation, where providers may overreport token usage or inject synthetic, low-effort tokens to inflate charges. To address this issue, we propose CoIn, a verification framework that audits both the quantity and semantic validity of hidden tokens. CoIn constructs a verifiable hash tree from token embedding fingerprints to check token counts, and uses embedding-based relevance matching to detect fabricated reasoning content. Experiments demonstrate that CoIn, when deployed as a trusted third-party auditor, can effectively detect token count inflation with a success rate reaching up to 94.7%, showing the strong ability to restore billing transparency in opaque LLM services. The dataset and code are available at https://github.com/CASE-Lab-UMD/LLM-Auditing-CoIn.

[Arxiv](https://arxiv.org/abs/2505.13778)
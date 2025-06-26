# LLM越狱指南

发布时间：2025年06月17日

`LLM理论

这篇论文探讨了大型语言模型（LLMs）在安全关键应用中的越狱攻击评估问题，提出了理论框架和算法，属于LLM的内在机制和安全性分析，因此归类为LLM理论。` `网络安全` `模型安全`

> LLM Jailbreak Oracle

# 摘要

> 随着大型语言模型（LLMs）在安全关键型应用中的广泛应用，缺乏系统性方法来评估其对越狱攻击的脆弱性，形成了一个关键的安全缺口。我们提出了“越狱预言问题”：给定一个模型、提示和解码策略，判断是否能够生成一种越狱响应，其生成概率超过指定阈值。这一形式化定义为研究越狱漏洞提供了理论基础。然而，回答越狱预言问题面临巨大的计算挑战——搜索空间随着响应令牌的长度呈指数级增长。我们提出了Boa，这是首个高效解决越狱预言问题的算法。Boa采用三阶段搜索策略：首先构建阻断列表识别拒绝模式，其次通过广度优先采样发现易于访问的越狱点，最后借助细粒度安全评分指导的深度优先优先搜索，系统性地探索有潜力的低概率路径。Boa为网络安全评估提供了坚实基础，支持系统性防御评估、标准化红队攻击比较，以及在极端对抗条件下对模型的认证。

> As large language models (LLMs) become increasingly deployed in safety-critical applications, the lack of systematic methods to assess their vulnerability to jailbreak attacks presents a critical security gap. We introduce the jailbreak oracle problem: given a model, prompt, and decoding strategy, determine whether a jailbreak response can be generated with likelihood exceeding a specified threshold. This formalization enables a principled study of jailbreak vulnerabilities. Answering the jailbreak oracle problem poses significant computational challenges -- the search space grows exponentially with the length of the response tokens. We present Boa, the first efficient algorithm for solving the jailbreak oracle problem. Boa employs a three-phase search strategy: (1) constructing block lists to identify refusal patterns, (2) breadth-first sampling to identify easily accessible jailbreaks, and (3) depth-first priority search guided by fine-grained safety scores to systematically explore promising low-probability paths. Boa enables rigorous security assessments including systematic defense evaluation, standardized comparison of red team attacks, and model certification under extreme adversarial conditions.

[Arxiv](https://arxiv.org/abs/2506.17299)
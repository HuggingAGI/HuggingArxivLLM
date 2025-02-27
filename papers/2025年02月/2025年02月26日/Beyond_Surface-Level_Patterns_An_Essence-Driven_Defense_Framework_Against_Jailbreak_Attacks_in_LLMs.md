# 超越表层模式：针对大型语言模型的越狱攻击构建基于本质的防御框架

发布时间：2025年02月26日

`LLM应用` `网络安全` `人工智能`

> Beyond Surface-Level Patterns: An Essence-Driven Defense Framework Against Jailbreak Attacks in LLMs

# 摘要

> 尽管对齐的大型语言模型（LLMs）能够识别并拒绝有害请求，但它们仍然容易受到越狱攻击。现有方法往往只关注表面模式，忽视了攻击的本质。因此，当攻击提示发生变化时，即使“攻击本质”相同，现有防御也会失效。为了解决这一问题，我们提出了EDDF——一种	extbf{基于“攻击本质”的防御框架，用于防范LLMs中的越狱攻击}。EDDF是一种即插即用的输入过滤方法，分为两个阶段：1）离线本质数据库构建，2）在线对抗查询检测。EDDF的核心思想是，从多种已知攻击实例中提取“攻击本质”，并将其存储在离线向量数据库中。实验结果表明，EDDF在降低攻击成功率方面显著优于现有方法，至少降低了20%，充分证明了其在抵御越狱攻击方面的优越鲁棒性。

> Although Aligned Large Language Models (LLMs) are trained to refuse harmful requests, they remain vulnerable to jailbreak attacks. Unfortunately, existing methods often focus on surface-level patterns, overlooking the deeper attack essences. As a result, defenses fail when attack prompts change, even though the underlying "attack essence" remains the same. To address this issue, we introduce EDDF, an \textbf{E}ssence-\textbf{D}riven \textbf{D}efense \textbf{F}ramework Against Jailbreak Attacks in LLMs. EDDF is a plug-and-play input-filtering method and operates in two stages: 1) offline essence database construction, and 2) online adversarial query detection. The key idea behind EDDF is to extract the "attack essence" from a diverse set of known attack instances and store it in an offline vector database. Experimental results demonstrate that EDDF significantly outperforms existing methods by reducing the Attack Success Rate by at least 20\%, underscoring its superior robustness against jailbreak attacks.

[Arxiv](https://arxiv.org/abs/2502.19041)
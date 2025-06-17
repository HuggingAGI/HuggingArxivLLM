# 基于编辑的LLMs后门注入安全回退缓解方法探讨

发布时间：2025年06月16日

`LLM理论` `人工智能安全` `网络安全`

> Mitigating Safety Fallback in Editing-based Backdoor Injection on LLMs

# 摘要

> 大型语言模型（LLMs）在自然语言任务中表现出色，但仍然容易受到后门攻击。最近基于模型编辑的方法通过直接修改参数，将特定触发词与攻击者期望的响应相关联，从而实现高效后门注入。然而，这些方法常常受到安全回退机制的限制，模型最初会积极响应，但随后又会拒绝执行，这是由于安全对齐机制所致。在本研究中，我们提出了一种双目标模型编辑框架DualEdit，旨在同时促进积极响应并抑制拒绝反应。为了解决两大关键挑战——平衡促进积极响应与抑制拒绝反应之间的权衡，以及处理多样化的拒绝表达方式——DualEdit引入了两种互补技术。第一，动态损失加权根据预编辑模型调整目标尺度，以稳定优化过程。第二，拒绝值锚定通过聚类具有代表性的拒绝值向量来压缩抑制目标空间，从而减少来自过于多样化的令牌集带来的优化冲突。在安全对齐的LLMs上的实验表明，与基线方法相比，DualEdit将攻击成功率提高了9.98%，并将安全回退率降低了10.88%。

> Large language models (LLMs) have shown strong performance across natural language tasks, but remain vulnerable to backdoor attacks. Recent model editing-based approaches enable efficient backdoor injection by directly modifying parameters to map specific triggers to attacker-desired responses. However, these methods often suffer from safety fallback, where the model initially responds affirmatively but later reverts to refusals due to safety alignment. In this work, we propose DualEdit, a dual-objective model editing framework that jointly promotes affirmative outputs and suppresses refusal responses. To address two key challenges -- balancing the trade-off between affirmative promotion and refusal suppression, and handling the diversity of refusal expressions -- DualEdit introduces two complementary techniques. (1) Dynamic loss weighting calibrates the objective scale based on the pre-edited model to stabilize optimization. (2) Refusal value anchoring compresses the suppression target space by clustering representative refusal value vectors, reducing optimization conflict from overly diverse token sets. Experiments on safety-aligned LLMs show that DualEdit improves attack success by 9.98\% and reduces safety fallback rate by 10.88\% over baselines.

[Arxiv](https://arxiv.org/abs/2506.13285)
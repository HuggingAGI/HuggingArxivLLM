# # 规范性冲突与表层AI对齐

发布时间：2025年06月05日

`LLM理论` `AI安全` `AI治理`

> Normative Conflicts and Shallow AI Alignment

# 摘要

> AI系统的快速发展，尤其是大型语言模型（LLMs），引发了对其安全部署的日益紧迫的关注。本文深入探讨了LLMs的“价值对齐”问题，指出当前的对齐策略在防止滥用方面存在根本性不足。尽管通过基于人类偏好的微调尝试在LLMs中植入 helpfulness、 honesty 和 harmlessness 等规范，但这些模型依然容易受到利用规范间冲突的对抗攻击。这一脆弱性揭示了现有对齐方法的核心局限：它们强化了浅层的行为模式，而非赋予LLMs真正的规范推理能力。借鉴道德心理学的研究，我们发现人类通过审慎推理提升了抵御类似对抗策略的能力。然而，LLMs却缺乏检测和理性解决规范冲突的能力，使其易受操纵；即便是在推理能力上取得的最新进展，也未能消除这一隐患。这种“浅层对齐”问题对AI安全和监管具有深远影响，表明现有的方法难以应对日益强大的AI系统可能带来的潜在风险。

> The progress of AI systems such as large language models (LLMs) raises increasingly pressing concerns about their safe deployment. This paper examines the value alignment problem for LLMs, arguing that current alignment strategies are fundamentally inadequate to prevent misuse. Despite ongoing efforts to instill norms such as helpfulness, honesty, and harmlessness in LLMs through fine-tuning based on human preferences, they remain vulnerable to adversarial attacks that exploit conflicts between these norms. I argue that this vulnerability reflects a fundamental limitation of existing alignment methods: they reinforce shallow behavioral dispositions rather than endowing LLMs with a genuine capacity for normative deliberation. Drawing from on research in moral psychology, I show how humans' ability to engage in deliberative reasoning enhances their resilience against similar adversarial tactics. LLMs, by contrast, lack a robust capacity to detect and rationally resolve normative conflicts, leaving them susceptible to manipulation; even recent advances in reasoning-focused LLMs have not addressed this vulnerability. This ``shallow alignment'' problem carries significant implications for AI safety and regulation, suggesting that current approaches are insufficient for mitigating potential harms posed by increasingly capable AI systems.

[Arxiv](https://arxiv.org/abs/2506.04679)
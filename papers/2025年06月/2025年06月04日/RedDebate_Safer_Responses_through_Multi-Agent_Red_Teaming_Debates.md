# RedDebate：通过多智能体红队辩论达成更安全的回应

发布时间：2025年06月04日

`Agent` `AI安全` `自动化测试`

> RedDebate: Safer Responses through Multi-Agent Red Teaming Debates

# 摘要

> 我们提出了 RedDebate，一个全新的多智能体辩论框架，通过大型语言模型 (LLMs) 之间的对抗性论证，主动识别和缓解潜在的不安全行为。现有的 AI 安全方法往往依赖昂贵的人工评估或孤立的单模型评估，这两种方式都存在可扩展性限制和监督风险。RedDebate 则通过协作性异议，让多个 LLM 相互审视推理过程，借助自动化的红队测试系统性地发现安全盲点，并迭代优化回应。我们还集成了多种长期记忆模块，确保从辩论互动中获得的安全见解得以保留。在 HarmBench 等安全基准测试中，RedDebate 展现了显著效果：仅辩论就能将不安全行为减少 17.7%，结合长期记忆模块后，减少幅度更超过 23.5%。据我们所知，这是首个结合多智能体辩论与红队测试的全自动框架，能够在无需人工直接干预的情况下，逐步提升 AI 的安全性。

> We propose RedDebate, a novel multi-agent debate framework that leverages adversarial argumentation among Large Language Models (LLMs) to proactively identify and mitigate their own unsafe behaviours. Existing AI safety methods often depend heavily on costly human evaluations or isolated single-model assessment, both subject to scalability constraints and oversight risks. RedDebate instead embraces collaborative disagreement, enabling multiple LLMs to critically examine one another's reasoning, and systematically uncovering unsafe blind spots through automated red-teaming, and iteratively improve their responses. We further integrate distinct types of long-term memory that retain learned safety insights from debate interactions. Evaluating on established safety benchmarks such as HarmBench, we demonstrate the proposed method's effectiveness. Debate alone can reduce unsafe behaviours by 17.7%, and when combined with long-term memory modules, achieves reductions exceeding 23.5%. To our knowledge, RedDebate constitutes the first fully automated framework that combines multi-agent debates with red-teaming to progressively enhance AI safety without direct human intervention.(Github Repository: https://github.com/aliasad059/RedDebate)

[Arxiv](https://arxiv.org/abs/2506.11083)
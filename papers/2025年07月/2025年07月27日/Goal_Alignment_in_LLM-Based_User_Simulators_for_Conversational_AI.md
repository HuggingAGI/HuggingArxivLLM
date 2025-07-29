# # 对话式AI中基于LLM的用户模拟器的目标对齐
在对话式 AI 中，基于大型语言模型（LLM）的用户模拟器实现目标对齐。

发布时间：2025年07月27日

`LLM应用` `对话式AI` `用户模拟器`

> Goal Alignment in LLM-Based User Simulators for Conversational AI

# 摘要

> 用户模拟器是对话式AI的核心，通过模拟交互实现规模化代理开发和评估。尽管当前大型语言模型（LLMs）在用户模拟能力上取得了进展，但我们发现它们在多轮对话中始终难以保持目标导向行为——这一关键缺陷削弱了其在下游应用中的可靠性。我们引入了用户目标状态追踪（UGST），一个全新的框架，用于跟踪对话全程的用户目标进展。基于UGST，我们提出了一种三阶段方法，用于开发能够自主追踪目标进展并推理生成目标对齐响应的用户模拟器。此外，我们制定了全面的评估指标，用于衡量用户模拟器中的目标对齐程度，并证明我们的方法在两个基准数据集（MultiWOZ 2.4 和 τ-Bench）上取得了显著提升。我们的贡献填补了对话式AI中的关键空白，确立了UGST作为开发目标对齐用户模拟器的核心框架。

> User simulators are essential to conversational AI, enabling scalable agent development and evaluation through simulated interactions. While current Large Language Models (LLMs) have advanced user simulation capabilities, we reveal that they struggle to consistently demonstrate goal-oriented behavior across multi-turn conversations--a critical limitation that compromises their reliability in downstream applications. We introduce User Goal State Tracking (UGST), a novel framework that tracks user goal progression throughout conversations. Leveraging UGST, we present a three-stage methodology for developing user simulators that can autonomously track goal progression and reason to generate goal-aligned responses. Moreover, we establish comprehensive evaluation metrics for measuring goal alignment in user simulators, and demonstrate that our approach yields substantial improvements across two benchmarks (MultiWOZ 2.4 and τ-Bench). Our contributions address a critical gap in conversational AI and establish UGST as an essential framework for developing goal-aligned user simulators.

[Arxiv](https://arxiv.org/abs/2507.20152)
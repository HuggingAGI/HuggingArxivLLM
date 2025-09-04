# A-SEA3L-QA：一种全自动自进化对抗性阿拉伯语长上下文问答生成工作流

发布时间：2025年09月02日

`Agent` `基础理论`

> A-SEA3L-QA: A Fully Automated Self-Evolving, Adversarial Workflow for Arabic Long-Context Question-Answer Generation

# 摘要

> 我们提出了一种端到端自进化对抗性工作流，专为阿拉伯语长上下文问答（QA）生成设计。该工作流通过协同多个专用大型视觉语言模型（LVLM）——问题生成器、评估器与一群答案生成器，实现了无人干预的性能迭代优化。系统以跨领域的原始多页阿拉伯语文档为输入，由问题生成器产出细粒度的上下文感知查询，经答案生成器群处理后，再由评估器评估并反馈质量指标。这种闭环机制驱动持续学习：低置信度输出会自动触发重新生成与模型更新，逐步提升问题的难度和相关性。此外，我们将质量指标设为可调超参数，可灵活控制问题生成的难度级别。我们还发布了大规模阿拉伯语基准AraLongBench，涵盖数百页单页及多页挑战，验证了自进化工作流显著优于静态管道，大幅增强了主流阿拉伯语大型视觉语言模型（LVLM）的长上下文理解能力。最后，我们精心构建了用于长上下文阿拉伯语文档收集的全自动智能体工作流。

> We present an end-to-end, self-evolving adversarial workflow for long-context Question-Answer (QA) Generation in Arabic. By orchestrating multiple specialized LVLMs: a question generator, an evaluator, and a swarm of answer generators, our system iteratively refines its own performance without any human intervention. Starting from raw, multi-page Arabic documents across diverse domains, the question generator produces fine-grained, context-aware queries to be tackled by the answer generator swarm, and the evaluator assesses and feeds back quality metrics. This closed-loop cycle enables continuous learning: low-confidence outputs trigger automated re-generation and model updates, progressively enhancing question difficulty and relevance. Moreover, we set the quality metrics as a tunable hyperparameter, enabling question generation at controllable and customizable difficulty levels. We release AraLongBench, a large-scale Arabic benchmark of single- and multi-page challenges spanning hundreds of pages, and demonstrate that our self-evolving workflow substantially outperform static pipelines, markedly boosting the long-context comprehension capabilities of leading Arabic Large Vision Language Models (LVLMs). Lastly, we also meticulously architect a fully automated agentic workflow for long-context Arabic document collection.

[Arxiv](https://arxiv.org/abs/2509.02864)
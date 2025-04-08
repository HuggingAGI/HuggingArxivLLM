# 从自生成数据中学习泛化：突破人类限制的模型训练新范式

发布时间：2025年04月06日

`Agent` `人工智能` `知识生成`

> Generalising from Self-Produced Data: Model Training Beyond Human Constraints

# 摘要

> 现有的大型语言模型 (LLMs) 受制于人类编写的训练数据，且受限于单一抽象层次，这使得明确判断真伪变得困难。本文提出了一种创新框架，让 AI 模型能够通过直接与环境互动，自主生成并验证新知识。该框架的核心是一个无边界且不可操控的数值奖励机制，例如附加磁盘空间或粉丝数量，这种奖励无需人工基准即可有效引导学习过程。AI 代理通过不断迭代生成策略和可执行代码，以最大化这一指标，而成功的案例则成为自我再训练和增量泛化的基石。为了解决模型崩溃和冷启动问题，该框架更注重经验验证而非文本相似度，并支持通过 GRPO 进行微调。系统架构采用模块化设计，分别由代理负责环境分析、策略生成和代码合成，从而实现可扩展的实验能力。这项研究为突破人类设定的限制，迈向自主通用智能的自我改进 AI 系统铺平了道路。

> Current large language models (LLMs) are constrained by human-derived training data and limited by a single level of abstraction that impedes definitive truth judgments. This paper introduces a novel framework in which AI models autonomously generate and validate new knowledge through direct interaction with their environment. Central to this approach is an unbounded, ungamable numeric reward - such as annexed disk space or follower count - that guides learning without requiring human benchmarks. AI agents iteratively generate strategies and executable code to maximize this metric, with successful outcomes forming the basis for self-retraining and incremental generalisation. To mitigate model collapse and the warm start problem, the framework emphasizes empirical validation over textual similarity and supports fine-tuning via GRPO. The system architecture employs modular agents for environment analysis, strategy generation, and code synthesis, enabling scalable experimentation. This work outlines a pathway toward self-improving AI systems capable of advancing beyond human-imposed constraints toward autonomous general intelligence.

[Arxiv](https://arxiv.org/abs/2504.04711)
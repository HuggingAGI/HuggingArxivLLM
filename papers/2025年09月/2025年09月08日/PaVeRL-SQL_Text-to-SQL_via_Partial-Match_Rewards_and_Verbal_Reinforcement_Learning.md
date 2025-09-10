# PaVeRL-SQL：基于部分匹配奖励与语言强化学习的文本转SQL

发布时间：2025年09月08日

`强化学习` `工业与制造`

> PaVeRL-SQL: Text-to-SQL via Partial-Match Rewards and Verbal Reinforcement Learning

# 摘要

> 文本转SQL模型能将自然语言问题转化为可执行SQL语句，让用户更轻松地与数据库交互。尽管近年来在简单数据库和问题上表现出色，但现有方法在面对行业级数据库及涉及特定领域业务逻辑的复杂问题时，执行准确率仍不尽如人意。为此，我们提出\emph{PaVeRL-SQL}框架——它融合\emph{部分匹配奖励}与\emph{语言强化学习}，旨在推动文本转SQL推理语言模型（RLMs）实现自我提升。为应对实际应用场景，我们设计了两条技术路线：（1）全新的上下文学习框架，结合组内自我评价机制（语言强化学习，verbal-RL），以高性能开源/闭源大型语言模型（LLMs）为核心；（2）思维链（CoT）强化学习路线，基于小型骨干模型OmniSQL-7B，通过定制奖励函数和两阶段强化学习训练。这两条路线在主流文本转SQL基准测试（Spider、Spider 2.0和BIRD）上均达到最先进（SOTA）水平：在工业级Spider2.0-SQLite测试中，语言强化学习路线准确率较SOTA提升7.4%，思维链路线提升1.4%。值得注意的是，混合SQL方言的强化学习训练带来显著三倍增益，尤其对训练数据有限的方言效果突出。总体而言，\emph{PaVeRL-SQL}在真实工业环境约束下，实现了可靠且领先的文本转SQL能力。相关代码已开源，地址为https://github.com/PaVeRL-SQL/PaVeRL-SQL。

> Text-to-SQL models allow users to interact with a database more easily by generating executable SQL statements from natural-language questions. Despite recent successes on simpler databases and questions, current Text-to-SQL methods still suffer from low execution accuracy on industry-scale databases and complex questions involving domain-specific business logic. We present \emph{PaVeRL-SQL}, a framework that combines \emph{Partial-Match Rewards} and \emph{Verbal Reinforcement Learning} to drive self-improvement in reasoning language models (RLMs) for Text-to-SQL. To handle practical use cases, we adopt two pipelines: (1) a newly designed in-context learning framework with group self-evaluation (verbal-RL), using capable open- and closed-source large language models (LLMs) as backbones; and (2) a chain-of-thought (CoT) RL pipeline with a small backbone model (OmniSQL-7B) trained with a specially designed reward function and two-stage RL. These pipelines achieve state-of-the-art (SOTA) results on popular Text-to-SQL benchmarks -- Spider, Spider 2.0, and BIRD. For the industrial-level Spider2.0-SQLite benchmark, the verbal-RL pipeline achieves an execution accuracy 7.4\% higher than SOTA, and the CoT pipeline is 1.4\% higher. RL training with mixed SQL dialects yields strong, threefold gains, particularly for dialects with limited training data. Overall, \emph{PaVeRL-SQL} delivers reliable, SOTA Text-to-SQL under realistic industrial constraints. The code is available at https://github.com/PaVeRL-SQL/PaVeRL-SQL.

[Arxiv](https://arxiv.org/abs/2509.07159)
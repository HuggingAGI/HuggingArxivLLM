# 行为信号驱动的个性化偏好推断：扩展归纳推理方法

发布时间：2025年05月23日

`LLM应用` `人工智能` `人机交互`

> Extended Inductive Reasoning for Personalized Preference Inference from Behavioral Signals

# 摘要

> 大型语言模型（LLMs）在数学和编程等复杂推理任务中表现优异。然而，与这些以演绎推理为主的任务不同，归纳推理——从不完整证据中推导一般规则的能力——仍是一个未被充分探索的领域。本文通过个性化偏好推理的视角，深入研究了LLMs中的扩展归纳推理能力。这一视角在LLM对齐中是一个关键挑战，因为现有方法难以捕捉多样化的用户偏好。该任务需要强大的归纳推理能力，因为用户偏好通常隐含在各种交互形式中，模型需从分散的信号中提炼出一致的偏好模式。

我们提出了	extsc{AlignXplore}，一种通过扩展推理链从用户交互历史中的行为信号进行系统化偏好推理的模型。通过结合基于合成数据的冷启动训练和后续的在线强化学习，我们开发了	extsc{AlignXplore}。实验结果表明，与基础模型相比，	extsc{AlignXplore}在内部和外部基准上平均提升了11.05\%，同时在不同的输入格式和下游模型中保持了强大的泛化能力。进一步分析通过系统比较奖励建模策略，确立了偏好推理学习的最佳实践，并揭示了训练过程中出现的类人类归纳推理模式。

> Large language models (LLMs) have demonstrated significant success in complex reasoning tasks such as math and coding. In contrast to these tasks where deductive reasoning predominates, inductive reasoning\textemdash the ability to derive general rules from incomplete evidence, remains underexplored. This paper investigates extended inductive reasoning in LLMs through the lens of personalized preference inference, a critical challenge in LLM alignment where current approaches struggle to capture diverse user preferences. The task demands strong inductive reasoning capabilities as user preferences are typically embedded implicitly across various interaction forms, requiring models to synthesize consistent preference patterns from scattered signals. We propose \textsc{AlignXplore}, a model that leverages extended reasoning chains to enable systematic preference inference from behavioral signals in users' interaction histories. We develop \textsc{AlignXplore} by combining cold-start training based on synthetic data with subsequent online reinforcement learning. Through extensive experiments, we demonstrate that \textsc{AlignXplore} achieves substantial improvements over the backbone model by an average of 11.05\% on in-domain and out-of-domain benchmarks, while maintaining strong generalization ability across different input formats and downstream models. Further analyses establish best practices for preference inference learning through systematic comparison of reward modeling strategies, while revealing the emergence of human-like inductive reasoning patterns during training.

[Arxiv](https://arxiv.org/abs/2505.18071)
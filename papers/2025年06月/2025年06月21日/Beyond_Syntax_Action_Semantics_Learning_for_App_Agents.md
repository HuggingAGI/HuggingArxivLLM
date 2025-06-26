# # 超越语法：应用代理的动作语义学习研究

发布时间：2025年06月21日

`Agent` `智能应用` `智能代理`

> Beyond Syntax: Action Semantics Learning for App Agents

# 摘要

> 大型语言模型（LLMs）的出现推动了App代理的兴起，这些代理能够通过点击和滚动等操作解读用户意图并运行智能手机应用程序。尽管基于提示词的解决方案结合封闭的LLM API展现了强大的能力，但它们带来了高昂的计算成本和对外部API的依赖。微调小型开源LLMs能够解决这些问题。然而，目前的微调方法采用了一种基于句法的学习范式，强制代理精确复现地面真实动作字符串，导致了对分布外（OOD）情况的脆弱性。为填补这一空白，我们提出了动作语义学习（ASL），一种全新的学习框架，其学习目标是捕捉地面真实动作的语义。具体来说，受编程语言理论的启发，我们将App代理的动作语义定义为该动作在用户界面上引发的状态转换。基于这一洞察，ASL采用了一种新颖的语义估计器（SEE）来计算语义奖励，用于训练App代理生成与地面真实动作语义对齐的动作，即使句法形式有所不同。为了支持ASL的有效性，我们从理论上证明了与现有基于句法的学习范式相比，ASL在OOD问题上具有更优越的鲁棒性。在离线和在线智能手机App操作基准上的大量实验表明，与现有方法相比，ASL显著提高了App代理的准确性和泛化能力。

> The advent of Large Language Models (LLMs) enables the rise of App agents that interpret user intent and operate smartphone Apps through actions such as clicking and scrolling. While prompt-based solutions with closed LLM APIs show promising ability, they incur heavy compute costs and external API dependency. Fine-tuning smaller open-source LLMs solves these limitations. However, current fine-tuning methods use a syntax learning paradigm that forces agents to reproduce exactly the ground truth action strings, leading to out-of-distribution (OOD) vulnerability. To fill this gap, we propose Action Semantics Learning (ASL), a novel learning framework, where the learning objective is capturing the semantics of the ground truth actions. Specifically, inspired by the programming language theory, we define the action semantics for App agents as the state transition induced by the action in the user interface. With this insight, ASL employs a novel SEmantic Estimator (SEE) to compute a semantic reward to train the App agents in generating actions aligned with the semantics of ground truth actions, even when the syntactic forms differ. To support the effectiveness of ASL, we theoretically demonstrate the superior robustness of ASL for the OOD problem compared with the existing syntax learning paradigm. Extensive experiments on offline and online smartphone App operation benchmarks show that ASL significantly improves the accuracy and generalisation of App agents over existing methods.

[Arxiv](https://arxiv.org/abs/2506.17697)
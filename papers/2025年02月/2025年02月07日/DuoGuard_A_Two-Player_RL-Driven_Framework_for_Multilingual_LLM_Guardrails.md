# 基于双玩家强化学习的多语言大语言模型护栏框架

发布时间：2025年02月07日

`LLM应用

理由：这篇论文主要探讨了如何利用强化学习框架生成合成数据，用于训练多语言护栏模型，以提高大型语言模型的安全性。虽然涉及理论上的形式化，但其核心目标是解决实际应用中的问题，属于应用层面的研究。` `人工智能安全` `数据生成`

> DuoGuard: A Two-Player RL-Driven Framework for Multilingual LLM Guardrails

# 摘要

> 随着大型语言模型 (LLMs) 的快速发展，确保负责任使用的需求日益迫切，尤其是在检测不安全和非法内容方面。尽管英语中已有大量安全数据，但其他语言开源安全数据的匮乏限制了多语言护栏建模的发展。为了解决这一难题，我们提出了一种创新的双玩家强化学习 (RL) 框架，其中生成器和护栏模型通过对抗方式共同进化，以生成高质量的合成数据用于多语言护栏训练。我们从理论上将此交互形式化为一个双玩家游戏，并证明其收敛到纳什均衡。实证评估显示，我们的模型 \ours 在英语基准上比 LlamaGuard3 (8B) 提高了近 10%，同时推理速度提高了 4.5 倍，模型规模也小得多（0.5B）。我们在多语言安全任务中取得了显著进展，特别是在解决收集的真实数据集中低资源语言的不平衡问题。消融研究表明，合成数据生成在缓解英语和其他语言之间开源数据不平衡方面起着关键作用。这些发现为合成数据生成提供了一种可扩展且高效的方法，为改进多语言护栏模型以提高 LLM 安全性奠定了基础。所有代码、模型和数据将在 https://github.com/yihedeng9/DuoGuard 上开源。

> The rapid advancement of large language models (LLMs) has increased the need for guardrail models to ensure responsible use, particularly in detecting unsafe and illegal content. While substantial safety data exist in English, multilingual guardrail modeling remains underexplored due to the scarcity of open-source safety data in other languages. To address this gap, we propose a novel two-player Reinforcement Learning (RL) framework, where a generator and a guardrail model co-evolve adversarially to produce high-quality synthetic data for multilingual guardrail training. We theoretically formalize this interaction as a two-player game, proving convergence to a Nash equilibrium. Empirical evaluations show that our model \ours outperforms state-of-the-art models, achieving nearly 10% improvement over LlamaGuard3 (8B) on English benchmarks while being 4.5x faster at inference with a significantly smaller model (0.5B). We achieve substantial advancements in multilingual safety tasks, particularly in addressing the imbalance for lower-resource languages in a collected real dataset. Ablation studies emphasize the critical role of synthetic data generation in bridging the imbalance in open-source data between English and other languages. These findings establish a scalable and efficient approach to synthetic data generation, paving the way for improved multilingual guardrail models to enhance LLM safety. Code, model, and data will be open-sourced at https://github.com/yihedeng9/DuoGuard.

[Arxiv](https://arxiv.org/abs/2502.05163)
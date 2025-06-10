# 强化抽象思维，提升大型语言模型的推理能力

发布时间：2025年06月09日

`LLM理论` `人工智能` `机器学习`

> Augmenting LLMs' Reasoning by Reinforcing Abstract Thinking

# 摘要

> 近期研究表明，大型语言模型（LLMs），尤其是较小规模的模型，常常在推理能力上缺乏稳健性。面对分布变化（如数值或名义变量的改变，或插入干扰性子句）时，它们往往会表现出性能下降。应对这一问题的可能策略包括生成合成数据，以在潜在变化中“实例化”推理问题。相比之下，我们的方法专注于“抽象”推理问题。这不仅有助于缓解分布变化的影响，还能促进与符号工具的连接，从而推导出解决方案。我们发现，这种抽象过程通过强化学习（RL）比单纯的监督微调更易掌握，后者通常难以生成忠实的抽象表达。我们的方法AbstraL——利用强化学习在细粒度抽象数据上促进LLMs的抽象推理能力——显著缓解了近期GSM扰动基准测试中的性能退化问题。

> Recent studies have shown that large language models (LLMs), especially smaller ones, often lack robustness in their reasoning. I.e., they tend to experience performance drops when faced with distribution shifts, such as changes to numerical or nominal variables, or insertions of distracting clauses. A possible strategy to address this involves generating synthetic data to further "instantiate" reasoning problems on potential variations. In contrast, our approach focuses on "abstracting" reasoning problems. This not only helps counteract distribution shifts but also facilitates the connection to symbolic tools for deriving solutions. We find that this abstraction process is better acquired through reinforcement learning (RL) than just supervised fine-tuning, which often fails to produce faithful abstractions. Our method, AbstraL -- which promotes abstract reasoning in LLMs using RL on granular abstraction data -- significantly mitigates performance degradation on recent GSM perturbation benchmarks.

[Arxiv](https://arxiv.org/abs/2506.07751)
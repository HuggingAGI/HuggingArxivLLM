# # 程序语义不等价博弈：基于大型语言模型的语义差异评估
程序语义不等价博弈是一种利用大型语言模型来衡量程序间语义差异的方法。

发布时间：2025年05月02日

`LLM应用

理由：这篇论文探讨了如何通过代理间的互动提升大型语言模型在代码生成和推理中的表现，属于将LLMs应用于特定任务的范畴，因此归类为LLM应用。` `软件工程` `数据科学`

> Program Semantic Inequivalence Game with Large Language Models

# 摘要

> 大型语言模型（LLMs）在日常编码任务中表现出色，但在需要复杂语义推理的任务上容易出错。寻找合适的训练示例来教会LLMs解决这些任务颇具挑战性。在本研究中，我们提出了一种基于语义不等价游戏SInQ的方法，用于合成生成代码推理训练数据。生成器代理创建语义不同的程序变体，这些变体源自真实世界的编程任务数据集，而评估器代理必须识别导致原始程序和生成变体行为出现差异的输入示例。代理之间以半对抗的方式互相训练。我们证明了这种设置在无限计算资源的情况下，通过自我对弈可以实现理论上无限的改进。我们在多个代码生成和理解基准上评估了我们的方法，包括跨语言漏洞检测（Lu et al., 2021），其中我们的方法在C/C++代码中提高了漏洞检测能力，尽管它仅在Python代码上进行过训练。此外，我们在具有挑战性的Python内置标识符交换基准（Miceli-Barone et al., 2023）上展示了，尽管现代LLMs仍然难以应对这一基准，但我们的方法带来了显著改进。我们发布了用于复制实验所需的代码，以及生成的合成数据，这些数据可用于微调LLMs。

> Large Language Models (LLMs) can achieve strong performance on everyday coding tasks, but they can fail on complex tasks that require non-trivial reasoning about program semantics. Finding training examples to teach LLMs to solve these tasks can be challenging.
  In this work, we explore a method to synthetically generate code reasoning training data based on a semantic inequivalence game SInQ: a generator agent creates program variants that are semantically distinct, derived from a dataset of real-world programming tasks, while an evaluator agent has to identify input examples that cause the original programs and the generated variants to diverge in their behaviour, with the agents training each other semi-adversarially. We prove that this setup enables theoretically unlimited improvement through self-play in the limit of infinite computational resources.
  We evaluated our approach on multiple code generation and understanding benchmarks, including cross-language vulnerability detection (Lu et al., 2021), where our method improves vulnerability detection in C/C++ code despite being trained exclusively on Python code, and the challenging Python builtin identifier swap benchmark (Miceli-Barone et al., 2023), showing that whereas modern LLMs still struggle with this benchmark, our approach yields substantial improvements.
  We release the code needed to replicate the experiments, as well as the generated synthetic data, which can be used to fine-tune LLMs.

[Arxiv](https://arxiv.org/abs/2505.03818)
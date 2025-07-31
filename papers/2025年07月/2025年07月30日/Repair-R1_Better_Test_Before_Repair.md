# # Repair-R1：修复前的更优测试方案

发布时间：2025年07月30日

`LLM应用` `软件工程` `人工智能`

> Repair-R1: Better Test Before Repair

# 摘要

> # 摘要
自动化程序修复（APR）的目标是自动发现程序缺陷、生成修复补丁并验证修复效果。现有的APR技术通常会结合大型语言模型（LLMs），利用LLMs的代码理解能力来提升修复效果。当前基于LLMs的APR方法通常仅在推理阶段使用测试用例，采用先修复后通过测试验证的迭代方法。这一传统范式忽视了两个重要方面：测试用例在训练阶段的潜在贡献，以及在修复前利用测试的可能性。为了解决这一问题，我们提出了Repair-R1，将测试用例引入模型的训练阶段，并将测试生成提前到修复之前。模型需要首先生成能够区分缺陷行为的判别性测试用例，然后基于这些测试进行修复。这使模型能够更好地定位缺陷并理解缺陷的根本原因，从而提升修复效果。我们使用三种不同的基础模型实现了Repair-R1，并采用强化学习（RL）来协同优化测试生成和漏洞修复。在四个广泛采用的基准测试上的实验结果证明了Repair-R1的优越性。特别地，与基础模型相比，Repair-R1将修复成功率提高了2.68%到48.29%，测试生成成功率提高了16.38%到53.28%，测试覆盖率提高了0.78%到53.96%。我们已将代码和权重发布在https://github.com/Tomsawyerhu/APR-RL和https://huggingface.co/tomhu/Qwen3-4B-RL-5000-step。


> APR (Automated Program Repair) aims to automatically locate program defects, generate patches and validate the repairs. Existing techniques for APR are often combined with LLMs (Large Language Models), which leverages the code-related knowledge of LLMs to improve repair effectiveness. Current LLM-based APR methods typically utilize test cases only during the inference stage, adopting an iterative approach that performs repair first and validates it through test execution afterward. This conventional paradigm neglects two important aspects: the potential contribution of test cases in the training phase, and the possibility of leveraging testing prior to repair. To address this, we propose Repair-R1, which introduces test cases into the model's training phase and shifts test generation to precede repair. The model is required to first generate discriminative test cases that can distinguish defective behaviors, and then perform repair based on these tests. This enables the model to better locate defects and understand the underlying causes of defects, thereby improving repair effectiveness. We implement Repair-R1 with three different backbone models, using RL (reinforcement learning) to co-optimize test generation and bug repair. Experimental results on four widely adopted benchmarks demonstrate the superiority of Repair-R1. Specially, compared to vanilla models, Repair-R1 improves repair success rate by 2.68\% to 48.29\%, test generation success rate by 16.38\% to 53.28\%, and test coverage by 0.78\% to 53.96\%. We publish the code and weights at https://github.com/Tomsawyerhu/APR-RL and https://huggingface.co/tomhu/Qwen3-4B-RL-5000-step.

[Arxiv](https://arxiv.org/abs/2507.22853)
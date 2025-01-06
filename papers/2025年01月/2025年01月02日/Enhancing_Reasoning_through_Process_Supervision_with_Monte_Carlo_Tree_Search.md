# 利用蒙特卡洛树搜索的过程监督提升推理能力

发布时间：2025年01月02日

`LLM理论

理由：这篇论文主要探讨了如何通过过程监督和蒙特卡洛树搜索（MCTS）来提升大型语言模型（LLMs）的推理能力。研究涉及了LLMs的内部机制和训练方法，特别是通过生成过程监督数据来训练模型，并验证了该方法在数学推理任务上的有效性。这些内容属于对LLMs的理论研究和改进，因此归类为“LLM理论”。` `人工智能` `数学推理`

> Enhancing Reasoning through Process Supervision with Monte Carlo Tree Search

# 摘要

> 大型语言模型（LLMs）在多种任务中展现了强大的能力，但推理仍是其短板。为提升LLMs的推理能力，过程监督比结果监督更为有效。本研究利用蒙特卡洛树搜索（MCTS）与LLMs自身生成过程监督数据，进而训练模型。我们通过LLM对推理步骤进行采样，并为每一步赋予“相对正确性”评分，随后通过最小化生成推理步骤的加权对数似然来训练LLM。这一生成-训练过程迭代进行，直至收敛。实验结果显示，该方法显著提升了LLMs在两个数学推理数据集上的表现。此外，在一个数据集上训练的模型在另一个数据集上也表现出性能提升，证明了增强推理能力的可迁移性。

> Large language models (LLMs) have demonstrated their remarkable capacity across a variety of tasks. However, reasoning remains a challenge for LLMs. To improve LLMs' reasoning ability, process supervision has proven to be better than outcome supervision. In this work, we study using Monte Carlo Tree Search (MCTS) to generate process supervision data with LLMs themselves for training them. We sample reasoning steps with an LLM and assign each step a score that captures its "relative correctness," and the LLM is then trained by minimizing weighted log-likelihood of generating the reasoning steps. This generate-then-train process is repeated iteratively until convergence.Our experimental results demonstrate that the proposed methods considerably improve the performance of LLMs on two mathematical reasoning datasets. Furthermore, models trained on one dataset also exhibit improved performance on the other, showing the transferability of the enhanced reasoning ability.

[Arxiv](https://arxiv.org/abs/2501.01478)
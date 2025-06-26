# 孔子3-数学：专为中文 K-12 数学学习设计的轻量级高性能推理大语言模型

发布时间：2025年06月23日

`LLM应用

理由：这篇论文主要介绍了一个专注于数学推理和教育领域的大型语言模型Confucius3-Math，并详细描述了其技术创新和应用效果。论文的重点在于模型的应用和技术创新，而非理论探讨或代理（Agent）、检索增强生成（RAG）等其他领域。因此，归类为LLM应用是合适的。` `教育科技`

> Confucius3-Math: A Lightweight High-Performance Reasoning LLM for Chinese K-12 Mathematics Learning

# 摘要

> 我们很高兴推出 Confucius3-Math，一款开源大型语言模型，拥有 140 亿参数，具备两大突出特点：(1) 能在单个消费级 GPU 上高效运行；(2) 在多项数学推理任务中达到最先进水平，超越众多规模更大的模型。特别值得一提的是，作为我们利用 AI 推动教育与知识传播使命的一部分，Confucius3-Math 专注于为中国 K-12 学生和教育工作者提供数学学习支持。通过基于大规模强化学习（RL）的后训练构建，Confucius3-Math 与国家课程无缝对接，擅长以低成本解决主流的中国 K-12 数学问题。在本报告中，我们将分享我们的开发心得、面临的挑战以及克服这些挑战的技术创新。特别地，我们带来了三项技术突破：目标熵正则化、近期样本恢复和策略特定难度加权。这些创新涵盖了新型熵正则化方法、创新的数据调度策略以及优化的组相对优势估计器。这些技术的综合应用显著提升了 RL 训练的稳定性，优化了数据利用效率，并显著提升了模型性能。我们的研究证明了以低成本构建特定领域强大推理模型的可行性。Confucius3-Math 的模型和代码已开源，访问地址为 https://github.com/netease-youdao/Confucius3-Math。

> We introduce Confucius3-Math, an open-source large language model with 14B parameters that (1) runs efficiently on a single consumer-grade GPU; (2) achieves SOTA performances on a range of mathematical reasoning tasks, outperforming many models with significantly larger sizes. In particular, as part of our mission to enhancing education and knowledge dissemination with AI, Confucius3-Math is specifically committed to mathematics learning for Chinese K-12 students and educators. Built via post-training with large-scale reinforcement learning (RL), Confucius3-Math aligns with national curriculum and excels at solving main-stream Chinese K-12 mathematical problems with low cost. In this report we share our development recipe, the challenges we encounter and the techniques we develop to overcome them. In particular, we introduce three technical innovations: Targeted Entropy Regularization, Recent Sample Recovery and Policy-Specific Hardness Weighting. These innovations encompass a new entropy regularization, a novel data scheduling policy, and an improved group-relative advantage estimator. Collectively, they significantly stabilize the RL training, improve data efficiency, and boost performance. Our work demonstrates the feasibility of building strong reasoning models in a particular domain at low cost. We open-source our model and code at https://github.com/netease-youdao/Confucius3-Math.

[Arxiv](https://arxiv.org/abs/2506.18330)
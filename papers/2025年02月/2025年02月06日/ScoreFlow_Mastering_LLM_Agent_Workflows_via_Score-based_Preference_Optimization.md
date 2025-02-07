# ScoreFlow: 基于分数优化的LLM代理工作流掌控

发布时间：2025年02月06日

`Agent

理由：这篇论文主要讨论了利用大型语言模型的多智能体系统来解决复杂问题，并提出了一个名为ScoreFlow的框架，该框架通过梯度优化在连续空间中工作。论文的核心内容围绕智能体系统的优化和改进，特别是通过引入Score-DPO来处理定量反馈。因此，这篇论文应归类为Agent。` `自动化` `智能体系统`

> ScoreFlow: Mastering LLM Agent Workflows via Score-based Preference Optimization

# 摘要

> # 摘要
近期研究利用大型语言模型多智能体系统解决复杂问题，同时减少构建所需的手动工作量，推动了自动化智能体工作流优化方法的发展。然而，现有方法因表示限制、适应性不足和依赖离散优化技术时的可扩展性差而显得不够灵活。我们提出了ScoreFlow，一个简单但高效的框架，利用连续空间中的梯度优化。ScoreFlow引入了Score-DPO，一种新颖的直接偏好优化方法变体，能够处理定量反馈。在问答、编码和数学推理的六个基准测试中，ScoreFlow比现有基线提升了8.2%。此外，它使较小模型以更低推理成本超越较大模型。项目地址：https://github.com/Gen-Verse/ScoreFlow

> Recent research has leveraged large language model multi-agent systems for complex problem-solving while trying to reduce the manual effort required to build them, driving the development of automated agent workflow optimization methods. However, existing methods remain inflexible due to representational limitations, a lack of adaptability, and poor scalability when relying on discrete optimization techniques. We address these challenges with ScoreFlow, a simple yet high-performance framework that leverages efficient gradient-based optimization in a continuous space. ScoreFlow incorporates Score-DPO, a novel variant of the direct preference optimization method that accounts for quantitative feedback. Across six benchmarks spanning question answering, coding, and mathematical reasoning, ScoreFlow achieves an 8.2% improvement over existing baselines. Moreover, it empowers smaller models to outperform larger ones with lower inference costs. Project: https://github.com/Gen-Verse/ScoreFlow

[Arxiv](https://arxiv.org/abs/2502.04306)
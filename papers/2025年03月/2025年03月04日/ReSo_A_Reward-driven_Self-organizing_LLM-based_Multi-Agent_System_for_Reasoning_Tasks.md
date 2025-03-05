# ReSo：基于奖励驱动的自组织LLM多智能体推理系统

发布时间：2025年03月04日

`Agent` `人工智能`

> ReSo: A Reward-driven Self-organizing LLM-based Multi-Agent System for Reasoning Tasks

# 摘要

> 多智能体系统（MAS）为提升大型语言模型在复杂问题解决中的推理能力提供了有前景的解决方案。然而，现有的MAS框架在灵活性、可扩展性和优化策略方面仍存在诸多限制。针对这些问题，我们提出了ReSo框架，它巧妙地结合了任务图生成与基于奖励的两阶段智能体选择过程。ReSo的核心在于其协作奖励模型，能够为MAS的合作提供精细的奖励信号，从而实现优化。此外，我们还开发了一个自动化数据合成框架，用于生成无需人工标注的MAS基准测试。实验结果表明，ReSo在性能上不仅能够匹敌现有方法，甚至在某些场景下超越它们。具体而言，在Math-MAS和SciBench-MAS SciBench基准测试中，ReSo分别达到了	extbf{33.7\%}和	extbf{32.3\%}的准确率，而其他方法则完全失效。ReSo的代码已在GitHub上开源，地址为：\href{https://github.com/hengzzzhou/ReSo}{ReSo}

> Multi-agent systems have emerged as a promising approach for enhancing the reasoning capabilities of large language models in complex problem-solving. However, current MAS frameworks are limited by poor flexibility and scalability, with underdeveloped optimization strategies. To address these challenges, we propose ReSo, which integrates task graph generation with a reward-driven two-stage agent selection process. The core of ReSo is the proposed Collaborative Reward Model, which can provide fine-grained reward signals for MAS cooperation for optimization. We also introduce an automated data synthesis framework for generating MAS benchmarks, without human annotations. Experimentally, ReSo matches or outperforms existing methods. ReSo achieves \textbf{33.7\%} and \textbf{32.3\%} accuracy on Math-MAS and SciBench-MAS SciBench, while other methods completely fail. Code is available at: \href{https://github.com/hengzzzhou/ReSo}{ReSo}

[Arxiv](https://arxiv.org/abs/2503.02390)
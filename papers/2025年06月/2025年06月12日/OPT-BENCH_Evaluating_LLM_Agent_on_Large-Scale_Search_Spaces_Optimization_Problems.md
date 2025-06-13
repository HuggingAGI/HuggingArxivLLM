# # OPT-BENCH: 在大规模搜索空间优化问题上评估 LLM 代理
OPT-BENCH 是一个用于评估 LLM 代理在大规模搜索空间优化问题中性能的框架。通过设计多样化搜索空间和优化任务，我们全面了解了 LLM 代理在不同复杂度和规模下的表现。

发布时间：2025年06月12日

`LLM应用` `机器学习` `计算机科学`

> OPT-BENCH: Evaluating LLM Agent on Large-Scale Search Spaces Optimization Problems

# 摘要

> 大型语言模型（LLMs）在多样任务中展现出了卓越的能力，但它们在通过学习以往反馈来迭代优化复杂解决方案方面的潜力尚未被充分挖掘。为了解决这一研究空白，我们推出了OPT-BENCH——一个全面的基准测试平台，专门用于评估LLM代理在大规模搜索空间优化问题中的表现。该平台整合了来自Kaggle的20个真实世界机器学习任务和10个经典NP问题，为评估LLM代理在迭代推理和解决方案优化方面的能力提供了一个多样化且具有挑战性的环境。为了实现严格的评估，我们开发了OPT-Agent——一个端到端的优化框架。该框架通过生成、验证并利用历史反馈来迭代改进解决方案，从而模拟人类在解决复杂问题时的推理过程。通过对来自6个模型家族的9个先进LLM进行广泛实验，我们深入分析了优化迭代次数、温度设置和模型架构对解决方案质量和收敛性的影响。实验结果表明，融入历史上下文信息在ML和NP任务中均显著提升了优化性能。为了推动这一领域的进一步研究，我们已将所有数据集、代码和评估工具开源。项目页面：\href{https://github.com/OliverLeeXZ/OPT-BENCH}{https://github.com/OliverLeeXZ/OPT-BENCH}。

> Large Language Models (LLMs) have shown remarkable capabilities in solving diverse tasks. However, their proficiency in iteratively optimizing complex solutions through learning from previous feedback remains insufficiently explored. To bridge this gap, we present OPT-BENCH, a comprehensive benchmark designed to evaluate LLM agents on large-scale search space optimization problems. OPT-BENCH includes 20 real-world machine learning tasks sourced from Kaggle and 10 classical NP problems, offering a diverse and challenging environment for assessing LLM agents on iterative reasoning and solution refinement. To enable rigorous evaluation, we introduce OPT-Agent, an end-to-end optimization framework that emulates human reasoning when tackling complex problems by generating, validating, and iteratively improving solutions through leveraging historical feedback. Through extensive experiments on 9 state-of-the-art LLMs from 6 model families, we analyze the effects of optimization iterations, temperature settings, and model architectures on solution quality and convergence. Our results demonstrate that incorporating historical context significantly enhances optimization performance across both ML and NP tasks. All datasets, code, and evaluation tools are open-sourced to promote further research in advancing LLM-driven optimization and iterative reasoning. Project page: \href{https://github.com/OliverLeeXZ/OPT-BENCH}{https://github.com/OliverLeeXZ/OPT-BENCH}.

[Arxiv](https://arxiv.org/abs/2506.10764)
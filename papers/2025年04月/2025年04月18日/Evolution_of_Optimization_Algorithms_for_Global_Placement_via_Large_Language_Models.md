# # 摘要
大型语言模型驱动的全局布图优化算法演变

发布时间：2025年04月18日

`LLM应用` `电子设计自动化` `自动化`

> Evolution of Optimization Algorithms for Global Placement via Large Language Models

# 摘要

> 优化算法广泛应用于解决复杂问题，但手动设计这些算法往往耗时费力且需要深厚的专业知识。全局布线是电子设计自动化（EDA）中的基础步骤。尽管分析方法目前是全局布线的前沿，但其核心优化算法仍然高度依赖于启发式方法和定制化组件，例如初始化策略、预处理方法以及步长搜索技术。本文提出了一种基于大型语言模型（LLM）的自动化框架，用于进化全局布线的优化算法。我们首先通过精心设计的提示词，利用LLM生成多样化的候选算法。接着，我们引入一种基于LLM的遗传流程来进化选定的候选算法。实验结果表明，所发现的优化算法在多个基准测试中展现出显著的性能提升。具体而言，我们针对特定设计案例发现的算法在MMS、ISPD2005和ISPD2019基准测试中分别实现了平均HPWL提升	extbf{5.05\%}、	ext{5.29\%}和	extbf{8.30\%}，并在个别案例中达到了	extbf{17\%}的提升。此外，所发现的算法还表现出良好的泛化能力，并且与现有的参数调优方法具有互补性。

> Optimization algorithms are widely employed to tackle complex problems, but designing them manually is often labor-intensive and requires significant expertise. Global placement is a fundamental step in electronic design automation (EDA). While analytical approaches represent the state-of-the-art (SOTA) in global placement, their core optimization algorithms remain heavily dependent on heuristics and customized components, such as initialization strategies, preconditioning methods, and line search techniques. This paper presents an automated framework that leverages large language models (LLM) to evolve optimization algorithms for global placement. We first generate diverse candidate algorithms using LLM through carefully crafted prompts. Then we introduce an LLM-based genetic flow to evolve selected candidate algorithms. The discovered optimization algorithms exhibit substantial performance improvements across many benchmarks. Specifically, Our design-case-specific discovered algorithms achieve average HPWL improvements of \textbf{5.05\%}, \text{5.29\%} and \textbf{8.30\%} on MMS, ISPD2005 and ISPD2019 benchmarks, and up to \textbf{17\%} improvements on individual cases. Additionally, the discovered algorithms demonstrate good generalization ability and are complementary to existing parameter-tuning methods.

[Arxiv](https://arxiv.org/abs/2504.17801)
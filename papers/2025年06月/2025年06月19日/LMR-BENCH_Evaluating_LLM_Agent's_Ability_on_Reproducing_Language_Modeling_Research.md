# LMR-BENCH：评测 LLM 代理在复现语言建模研究中的能力

发布时间：2025年06月19日

`LLM应用` `科学发现`

> LMR-BENCH: Evaluating LLM Agent's Ability on Reproducing Language Modeling Research

# 摘要

> 大型语言模型（LLM）代理在科学发现领域展现出巨大潜力，但在从研究论文中复现代码这一关键任务上仍有待探索，尤其是在自然语言处理领域。这一任务涉及抽象概念的智力整合和对包含相互依赖文件的代码仓库的理解，带来了独特的复杂推理挑战。为填补这一空白，我们推出了LLM-BENCH——一个系统性评估LLM代理在语言建模研究代码复现任务中能力的基准测试。该基准测试涵盖过去五年内发表在顶级NLP会议上的23篇研究论文，从中衍生出28个代码复现任务，涉及九个基础类别。模型将获得一篇研究论文、一个包含一个或多个被遮蔽函数的代码仓库以及实现这些函数的指令。我们使用当前最先进的LLMs在标准提示和LLM代理设置下进行了广泛实验，评估单元测试的准确性并进行基于LLM的代码正确性评估。实验结果表明，即使是目前最先进的模型在科学推理和代码合成方面仍然存在持续性局限，凸显了LLM代理在自主复现科学研究能力上的关键差距。

> Large language model (LLM) agents have demonstrated remarkable potential in advancing scientific discovery. However, their capability in the fundamental yet crucial task of reproducing code from research papers, especially in the NLP domain, remains underexplored. This task includes unique complex reasoning challenges in the intellectual synthesis of abstract concepts and the comprehension of code repositories with interdependent files. Motivated by this gap, we present LMR-BENCH, a benchmark designed to systematically evaluate the capability of LLM agents on code reproduction from Language Modeling Research. It consists of 28 code reproduction tasks derived from 23 research papers published in top-tier NLP venues over the past five years, spanning nine fundamental categories. Models are provided with a research paper, a code repository containing one or more masked functions, and instructions for implementing these functions. We conduct extensive experiments in standard prompting and LLM agent settings with state-of-the-art LLMs, evaluating the accuracy of unit tests and performing LLM-based evaluation of code correctness. Experimental results reveal that even the most advanced models still exhibit persistent limitations in scientific reasoning and code synthesis, highlighting critical gaps in LLM agents' ability to autonomously reproduce scientific research

[Arxiv](https://arxiv.org/abs/2506.17335)
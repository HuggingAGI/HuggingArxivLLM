# BugScope：掌握像人类一样发现漏洞的技能

发布时间：2025年07月21日

`LLM应用` `软件工程` `开源软件`

> BugScope: Learn to Find Bugs Like Human

# 摘要

> 软件缺陷检测依然是一个基本挑战，原因在于真实世界中缺陷的广泛多样性。传统的静态分析工具往往依赖于符号化工作流，这限制了它们的覆盖范围并阻碍了它们对具有多样化反模式的定制化缺陷的适应能力。尽管最近的研究通过引入大型语言模型（LLMs）来增强缺陷检测，但这些方法仍然在处理复杂的缺陷时遇到困难，并且通常只能在有限的分析上下文中运行。

为了解决这些挑战，我们提出了BugScope，这是一个LLM驱动的多智能体系统，模拟了人类审计员如何从代表性实例中学习新的缺陷模式，并在代码审计过程中应用这些知识。给定一组展示了有缺陷和无缺陷行为的示例，BugScope会合成一个检索策略，通过程序切片提取相关的检测上下文，然后构建一个定制的检测提示，以引导LLM进行准确的推理。

我们在一个精心整理的数据集上进行了评估，该数据集包含从21个广泛使用的开源项目中提取的40个真实世界缺陷。结果表明，BugScope实现了87.04%的精确率和90.00%的召回率，其F1分数比最先进的工业工具高出0.44。此外，在对大型开源系统（包括Linux内核）的进一步测试中，BugScope发现了141个之前未知的缺陷，其中78个已修复，7个得到了开发者的确认，这凸显了BugScope在实践中的重大影响。

> Detecting software bugs remains a fundamental challenge due to the extensive diversity of real-world defects. Traditional static analysis tools often rely on symbolic workflows, which restrict their coverage and hinder adaptability to customized bugs with diverse anti-patterns. While recent advances incorporate large language models (LLMs) to enhance bug detection, these methods continue to struggle with sophisticated bugs and typically operate within limited analysis contexts. To address these challenges, we propose BugScope, an LLM-driven multi-agent system that emulates how human auditors learn new bug patterns from representative examples and apply that knowledge during code auditing. Given a set of examples illustrating both buggy and non-buggy behaviors, BugScope synthesizes a retrieval strategy to extract relevant detection contexts via program slicing and then constructs a tailored detection prompt to guide accurate reasoning by the LLM. Our evaluation on a curated dataset of 40 real-world bugs drawn from 21 widely-used open-source projects demonstrates that BugScope achieves 87.04% precision and 90.00% recall, surpassing state-of-the-art industrial tools by 0.44 in F1 score. Further testing on large-scale open-source systems, including the Linux kernel, uncovered 141 previously unknown bugs, of which 78 have been fixed and 7 confirmed by developers, highlighting BugScope's substantial practical impact.

[Arxiv](https://arxiv.org/abs/2507.15671)
# SAGE:基于规范的语法提取方法，用于LLMs驱动的自动化测试用例生成

发布时间：2025年06月04日

`LLM应用` `编程竞赛` `软件工程`

> SAGE:Specification-Aware Grammar Extraction for Automated Test Case Generation with LLMs

# 摘要

> 基于语法规则的测试用例生成在编程竞赛问题中表现出色，但如何从自然语言规范中生成有效且通用的语法规则仍是一个关键挑战，尤其是在监督有限的情况下。带计数器的上下文无关文法（CCFGs）作为一种形式化方法，通过存储和复用计数器值来表示具有逻辑约束的规范，最近受到了广泛关注。

在本研究中，我们探索了利用开源大型语言模型（LLMs）从规范中诱导CCFGs的方法，仅使用少量带标签的示例，并结合可验证奖励引导的强化学习。我们的方法首先对开源LLM进行微调，以实现规范到语法规则的翻译，随后应用组相对策略优化（GRPO）来提升语法规则的有效性和通用性。此外，我们还研究了迭代反馈在开源和闭源LLMs中对生成语法规则中句法和语义错误的修正效果。

实验结果表明，我们的方法SAGE在语法规则质量和测试有效性方面均实现了更强的泛化能力，并超越了17个开源和闭源LLMs。与现有最优方法相比，SAGE在语法规则有效性和测试有效性方面分别提升了15.92个百分点和12.34个百分点。我们的实现和数据集已开源，详情请访问匿名仓库：https://anonymous.4open.science/r/SAGE-5714

> Grammar-based test case generation has proven effective for competitive programming problems, but generating valid and general grammars from natural language specifications remains a key challenge, especially under limited supervision. Context-Free Grammars with Counters (CCFGs) have recently been introduced as a formalism to represent such specifications with logical constraints by storing and reusing counter values during derivation. In this work, we explore the use of open-source large language models (LLMs) to induce CCFGs from specifications using a small number of labeled examples and verifiable reward-guided reinforcement learning. Our approach first fine-tunes an open-source LLM to perform specification-to-grammar translation, and further applies Group Relative Policy Optimization (GRPO) to enhance grammar validity and generality. We also examine the effectiveness of iterative feedback for open and closed-source LLMs in correcting syntactic and semantic errors in generated grammars.
  Experimental results show that our approach SAGE achieves stronger generalization and outperforms 17 open and closed-source LLMs in both grammar quality and test effectiveness, improving over the state-of-the-art by 15.92%p in grammar validity and 12.34%p in test effectiveness. We provide our implementation and dataset at the following anonymous repository:https://anonymous.4open.science/r/SAGE-5714

[Arxiv](https://arxiv.org/abs/2506.11081)
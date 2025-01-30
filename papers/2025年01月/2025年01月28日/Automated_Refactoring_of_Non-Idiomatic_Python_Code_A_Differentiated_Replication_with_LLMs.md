# 自动化重构非惯用Python代码：基于LLMs的差异化复制

发布时间：2025年01月28日

`LLM应用

**解释**：这篇论文探讨了大型语言模型（GPT-4）在代码重构任务中的应用，特别是其在推荐惯用代码重构方面的表现。论文的核心是研究LLM在实际应用中的潜力，因此应归类为LLM应用。` `软件工程` `编程语言`

> Automated Refactoring of Non-Idiomatic Python Code: A Differentiated Replication with LLMs

# 摘要

> 在 Python 生态系统中，尽管惯用结构在熟悉度和可理解性上存在争议，但其强大的表达力和对生产力的提升使其得到了广泛应用。最近的研究提出了基于静态代码分析和转换的方法，能够自动将非惯用代码重构为惯用代码。鉴于大型语言模型（LLMs）在代码任务中的潜力，本文通过复制研究探讨了 GPT-4 在推荐惯用重构操作方面的表现。结果显示，GPT-4 不仅能有效识别惯用结构，还在现有基准失败的情况下，提出了更优的重构方案。随机样本的手动分析验证了这些建议的正确性。我们的研究揭示了 LLMs 在替代传统复杂代码分析推荐器方面的巨大潜力。

> In the Python ecosystem, the adoption of idiomatic constructs has been fostered because of their expressiveness, increasing productivity and even efficiency, despite controversial arguments concerning familiarity or understandability issues. Recent research contributions have proposed approaches -- based on static code analysis and transformation -- to automatically identify and enact refactoring opportunities of non-idiomatic code into idiomatic ones. Given the potential recently offered by Large Language Models (LLMs) for code-related tasks, in this paper, we present the results of a replication study in which we investigate GPT-4 effectiveness in recommending and suggesting idiomatic refactoring actions. Our results reveal that GPT-4 not only identifies idiomatic constructs effectively but frequently exceeds the benchmark in proposing refactoring actions where the existing baseline failed. A manual analysis of a random sample shows the correctness of the obtained recommendations. Our findings underscore the potential of LLMs to achieve tasks where, in the past, implementing recommenders based on complex code analyses was required.

[Arxiv](https://arxiv.org/abs/2501.17024)
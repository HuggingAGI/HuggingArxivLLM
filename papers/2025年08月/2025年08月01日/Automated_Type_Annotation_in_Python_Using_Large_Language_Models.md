# # 自动化类型注释
Python 中的自动化类型注释：借助大语言模型实现类型提示

发布时间：2025年08月01日

`LLM应用` `编程语言` `软件工程`

> Automated Type Annotation in Python Using Large Language Models

# 摘要

> Python中的类型注解能显著提升代码的可维护性和错误检测能力。然而，手动编写这些注解不仅费时，还容易出错。传统自动化方法如静态分析、机器学习和深度学习则面临类型词库有限、行为过度近似以及依赖大规模标注数据集的挑战。本研究探索了使用大语言模型（LLMs）为Python代码生成类型注解的可能性。我们设计了一个生成-验证-修复的流水线：LLM基于抽象语法树（Concrete Syntax Tree）提出注解，静态类型检查器（Mypy）验证其正确性，任何错误都会被反馈用于迭代优化。我们评估了四个LLM变体：GPT 4oMini、GPT 4.1mini（通用型）、O3Mini和O4Mini（推理优化型），在ManyTypes4Py基准测试中的6000个代码片段上进行测试。首先，我们测量LLM生成注解后Mypy未报告错误的比例（即一致结果）：GPT 4oMini在65.9%的情况下保持一致（34.1%不一致），而GPT 4.1mini、O3Mini和O4Mini分别达到约88.6%的一致性（约11.4%失败）。为了评估注解质量，我们计算了所有6000个代码片段的精确匹配和基类匹配准确率：GPT 4.1mini和O3Mini表现最佳，分别达到70.5%的精确匹配率和79.1%的基类匹配率，平均修复迭代次数不到一次。我们的结果显示，无需任何特定任务的微调或额外训练，通用型和推理优化型的LLM都能有效生成一致的类型注解。它们的表现可与传统深度学习技术相媲美，而传统方法需要大规模标注数据集进行训练。虽然本研究聚焦于Python，但该流水线可扩展至其他可选类型的过程式语言如Ruby。


> Type annotations in Python enhance maintainability and error detection. However, generating these annotations manually is error prone and requires extra effort. Traditional automation approaches like static analysis, machine learning, and deep learning struggle with limited type vocabularies, behavioral over approximation, and reliance on large labeled datasets. In this work, we explore the use of LLMs for generating type annotations in Python. We develop a generate check repair pipeline: the LLM proposes annotations guided by a Concrete Syntax Tree representation, a static type checker (Mypy) verifies them, and any errors are fed back for iterative refinement. We evaluate four LLM variants: GPT 4oMini, GPT 4.1mini (general-purpose), and O3Mini, O4Mini (reasoning optimized), on 6000 code snippets from the ManyTypes4Py benchmark. We first measure the proportion of code snippets annotated by LLMs for which MyPy reported no errors (i.e., consistent results): GPT 4oMini achieved consistency on 65.9% of cases (34.1% inconsistent), while GPT 4.1mini, O3Mini, and O4Mini each reached approximately 88.6% consistency (around 11.4% failures). To measure annotation quality, we then compute exact-match and base-type match accuracies over all 6000 snippets: GPT 4.1mini and O3Mini perform the best, achieving up to 70.5% exact match and 79.1% base type accuracy, requiring under one repair iteration on average. Our results demonstrate that general-purpose and reasoning optimized LLMs, without any task specific fine tuning or additional training can be effective in generating consistent type annotations.They perform competitively with traditional deep learning techniques which require large labeled dataset for training. While our work focuses on Python, the pipeline can be extended to other optionally typed imperative languages like Ruby

[Arxiv](https://arxiv.org/abs/2508.00422)
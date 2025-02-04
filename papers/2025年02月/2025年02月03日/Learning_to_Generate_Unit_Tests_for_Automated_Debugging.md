# 学习生成单元测试，助力自动化调试

发布时间：2025年02月03日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）生成单元测试输入和输出，并将其集成到一个调试管道中，以提高代码调试的效率。论文的核心是LLM在代码调试和测试生成中的应用，因此属于“LLM应用”类别。` `软件开发`

> Learning to Generate Unit Tests for Automated Debugging

# 摘要

> # 摘要
单元测试（UTs）在评估代码正确性和为大型语言模型（LLM）提供反馈方面至关重要，尤其是在LLM迭代调试错误代码时，这推动了自动化测试生成的动机。然而，我们发现了一个矛盾：在给定错误代码时生成揭示错误的单元测试输入，与在没有黄金解决方案的情况下正确预测单元测试输出之间存在权衡。为此，我们提出了UTGen，它教导LLMs基于任务描述和候选代码生成揭示错误的单元测试输入及其正确的预期输出。我们将UTGen集成到UTDebug中，这是一个强大的调试管道，利用生成的测试帮助LLMs有效调试。由于模型生成的测试可能带来噪声信号（如错误预测的输出），UTDebug通过（i）测试时计算扩展UTGen以改进UT输出预测，（ii）基于多个生成的UT验证和回溯编辑以避免过拟合。实验表明，UTGen在衡量揭示错误的UT输入和正确UT输出存在的指标上优于UT生成基线7.59%。当与UTDebug结合使用时，UTGen的单元测试反馈将Qwen-2.5 7B在HumanEvalFix和我们更难的MBPP+调试分割上的pass@1准确率分别提高了3%和12.35%，优于其他基于LLM的UT生成基线。

> Unit tests (UTs) play an instrumental role in assessing code correctness as well as providing feedback to a large language model (LLM) as it iteratively debugs faulty code, motivating automated test generation. However, we uncover a trade-off between generating unit test inputs that reveal errors when given a faulty code and correctly predicting the unit test output without access to the gold solution. To address this trade-off, we propose UTGen, which teaches LLMs to generate unit test inputs that reveal errors along with their correct expected outputs based on task descriptions and candidate code. We integrate UTGen into UTDebug, a robust debugging pipeline that uses generated tests to help LLMs debug effectively. Since model-generated tests can provide noisy signals (e.g., from incorrectly predicted outputs), UTDebug (i) scales UTGen via test-time compute to improve UT output prediction, and (ii) validates and back-tracks edits based on multiple generated UTs to avoid overfitting. We show that UTGen outperforms UT generation baselines by 7.59% based on a metric measuring the presence of both error-revealing UT inputs and correct UT outputs. When used with UTDebug, we find that feedback from UTGen's unit tests improves pass@1 accuracy of Qwen-2.5 7B on HumanEvalFix and our own harder debugging split of MBPP+ by over 3% and 12.35% (respectively) over other LLM-based UT generation baselines.

[Arxiv](https://arxiv.org/abs/2502.01619)
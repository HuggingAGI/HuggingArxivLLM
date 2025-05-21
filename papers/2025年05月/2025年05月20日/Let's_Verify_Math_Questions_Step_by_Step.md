# 一步步验证数学题，我们来试试看！

发布时间：2025年05月20日

`LLM应用` `数据生成`

> Let's Verify Math Questions Step by Step

# 摘要

> 大型语言模型（LLMs）在数学推理领域取得了显著突破。现有研究主要通过构建长链式思维或设计算法生成高质量数学问答数据来实现这一能力。然而，这些方法大多聚焦于正确推理路径和答案的生成，却忽视了问题本身的合理性。为此，我们提出了数学问题验证（MathQ-Verify），一个五阶段的新型管道，专为严格筛选表述不清或定义不全的数学问题而设计。首先，MathQ-Verify进行格式级别的验证，去除冗余指令，确保每个问题在语法上完整。随后，它将问题形式化，分解为基本条件，并根据数学定义进行验证。接下来，它检测这些条件之间的逻辑矛盾，并通过目标导向的完整性检查，确保问题提供了足够的解答信息。为了评估这一任务，我们采用了现有基准测试和一个额外数据集，该数据集包含2,147个数学问题，涵盖多种错误类型，每个问题都经过人工双重验证。实验结果表明，MathQ-Verify在多个基准测试中达到了最先进的性能，与直接验证基线相比，F1分数提高了25个百分点。通过轻量级模型投票方案，它实现了约90%的精度和63%的召回率。MathQ-Verify为整理可靠的数学数据集提供了一个可扩展且准确的解决方案，减少了标签噪声，并避免了对无效问题进行不必要的计算。我们的代码和数据可在https://github.com/scuuy/MathQ-Verify获取。

> Large Language Models (LLMs) have recently achieved remarkable progress in mathematical reasoning. To enable such capabilities, many existing works distill strong reasoning models into long chains of thought or design algorithms to construct high-quality math QA data for training. However, these efforts primarily focus on generating correct reasoning paths and answers, while largely overlooking the validity of the questions themselves. In this work, we propose Math Question Verification (MathQ-Verify), a novel five-stage pipeline designed to rigorously filter ill-posed or under-specified math problems. MathQ-Verify first performs format-level validation to remove redundant instructions and ensure that each question is syntactically well-formed. It then formalizes each question, decomposes it into atomic conditions, and verifies them against mathematical definitions. Next, it detects logical contradictions among these conditions, followed by a goal-oriented completeness check to ensure the question provides sufficient information for solving. To evaluate this task, we use existing benchmarks along with an additional dataset we construct, containing 2,147 math questions with diverse error types, each manually double-validated. Experiments show that MathQ-Verify achieves state-of-the-art performance across multiple benchmarks, improving the F1 score by up to 25 percentage points over the direct verification baseline. It further attains approximately 90% precision and 63% recall through a lightweight model voting scheme. MathQ-Verify offers a scalable and accurate solution for curating reliable mathematical datasets, reducing label noise and avoiding unnecessary computation on invalid questions. Our code and data are available at https://github.com/scuuy/MathQ-Verify.

[Arxiv](https://arxiv.org/abs/2505.13903)
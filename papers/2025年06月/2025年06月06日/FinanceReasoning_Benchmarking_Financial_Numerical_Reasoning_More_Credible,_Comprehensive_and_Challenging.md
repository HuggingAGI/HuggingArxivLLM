# # FinanceReasoning：更可信、更全面、更具挑战性的金融数值推理基准评测

发布时间：2025年06月06日

`LLM应用`

> FinanceReasoning: Benchmarking Financial Numerical Reasoning More Credible, Comprehensive and Challenging

# 摘要

> 我们推出全新的FinanceReasoning基准测试，专注于评估大型推理模型（LRMs）在财务数值推理领域的推理能力。相比现有基准，我们的工作在三个方面实现了突破：

1. 可信度：我们更新了15.6%的现有问题，并新增了908个标注问题，每个都配有详细的Python解答脚本。同时，我们对评估标准进行了严格优化，确保能够准确衡量LRMs推理能力的提升。

2. 全面性：FinanceReasoning覆盖了67.8%的财务概念和公式，远超现有数据集。我们还开发了3,133个Python格式化函数，通过优化知识（例如GPT-4o准确率从83.2%提升至91.6%）显著增强了LRMs的财务推理能力。

3. 挑战性：模型需要运用多个财务公式对238个高难度问题进行精准数值推理。目前表现最佳的模型（OpenAI o1结合PoT）达到了89.1%的准确率，但LRMs在数值精度方面仍面临挑战。我们的研究证明，结合推理模型与编程模型（如DeepSeek-R1从83.2%提升至87.8%）能有效提升整体表现。

这项研究为未来在特定领域复杂推理任务中评估和优化LRMs提供了重要参考。


> We introduce FinanceReasoning, a novel benchmark designed to evaluate the reasoning capabilities of large reasoning models (LRMs) in financial numerical reasoning problems. Compared to existing benchmarks, our work provides three key advancements. (1) Credibility: We update 15.6% of the questions from four public datasets, annotating 908 new questions with detailed Python solutions and rigorously refining evaluation standards. This enables an accurate assessment of the reasoning improvements of LRMs. (2) Comprehensiveness: FinanceReasoning covers 67.8% of financial concepts and formulas, significantly surpassing existing datasets. Additionally, we construct 3,133 Python-formatted functions, which enhances LRMs' financial reasoning capabilities through refined knowledge (e.g., 83.2% $\rightarrow$ 91.6% for GPT-4o). (3) Challenge: Models are required to apply multiple financial formulas for precise numerical reasoning on 238 Hard problems. The best-performing model (i.e., OpenAI o1 with PoT) achieves 89.1% accuracy, yet LRMs still face challenges in numerical precision. We demonstrate that combining Reasoner and Programmer models can effectively enhance LRMs' performance (e.g., 83.2% $\rightarrow$ 87.8% for DeepSeek-R1). Our work paves the way for future research on evaluating and improving LRMs in domain-specific complex reasoning tasks.

[Arxiv](https://arxiv.org/abs/2506.05828)
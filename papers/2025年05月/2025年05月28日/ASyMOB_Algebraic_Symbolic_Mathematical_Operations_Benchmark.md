# # ASyMOB: 代数符号数学运算评测基准

发布时间：2025年05月28日

`LLM应用

理由：这篇论文主要探讨了大型语言模型在符号数学能力上的表现和评估，引入了一个新的框架来测试和分析LLMs在数学任务中的泛化能力。虽然涉及模型的性能分析，但其核心在于应用层面，即评估和应用LLMs在数学问题上的能力，因此归类为LLM应用。` `计算机科学`

> ASyMOB: Algebraic Symbolic Mathematical Operations Benchmark

# 摘要

> 大型语言模型（LLMs）在大学水平符号数学能力上正快速接近应用于高级科学和科技所需的水平。然而，现有基准测试未能充分评估LLMs在积分、微分方程和代数化简等核心符号数学技能上的能力。为填补这一空白，我们引入了ASyMOB——一个专注于符号运算评估的全新框架，包含17,092个独特的数学挑战，按相似性和复杂性分类。通过比较LLMs在仅因简单数值或符号`扰动`而不同的问题上的表现，ASyMOB使分析LLM的泛化能力成为可能。评估结果显示，各模型在所有类型的扰动下表现均有显著下降（最高达-70.3%），表明它们依赖于记忆的模式而非对符号数学的深层理解，即使是在基线准确率较高的模型中也是如此。将LLM的表现与计算机代数系统进行比较，我们发现了一些LLMs成功而系统失败的例子，以及需要结合两种方法才能解决的问题。具备代码执行能力的模型在启用代码时表现更佳，尤其是能稳定较弱模型的表现（某些扰动类型下提升高达+33.1%）。值得注意的是，最先进的模型（如o4-mini和Gemini 2.5 Flash）不仅在符号数学能力上表现出色（在未扰动的测试集上分别达到96.8%和97.6%的得分），而且在面对扰动时展现出显著的鲁棒性（-21.7%和-21.2%的下降幅度，而其他模型平均下降达-50.4%）。这可能表明前沿LLMs的泛化能力近期发生了“相变”。未来的发展方向可能在于更深度地整合复杂外部工具，或开发能力足够强大的模型，使得像CAS这样的符号数学系统变得多余。

> Large language models (LLMs) are rapidly approaching the level of proficiency in university-level symbolic mathematics required for applications in advanced science and technology. However, existing benchmarks fall short in assessing the core skills of LLMs in symbolic mathematics-such as integration, differential equations, and algebraic simplification. To address this gap, we introduce ASyMOB, a novel assessment framework focused exclusively on symbolic manipulation, featuring 17,092 unique math challenges, organized by similarity and complexity. ASyMOB enables analysis of LLM generalization capabilities by comparing performance in problems that differ by simple numerical or symbolic `perturbations'. Evaluated LLMs exhibit substantial degradation in performance for all perturbation types (up to -70.3%), suggesting reliance on memorized patterns rather than deeper understanding of symbolic math, even among models achieving high baseline accuracy. Comparing LLM performance to computer algebra systems, we identify examples where they fail while LLMs succeed, as well as problems solved only by combining both approaches. Models capable of integrated code execution yielded higher accuracy compared to their performance without code, particularly stabilizing weaker models (up to +33.1% for certain perturbation types). Notably, the most advanced models (o4-mini, Gemini 2.5 Flash) demonstrate not only high symbolic math proficiency (scoring 96.8% and 97.6% on the unperturbed set), but also remarkable robustness against perturbations, (-21.7% and -21.2% vs. average -50.4% for the other models). This may indicate a recent "phase transition" in the generalization capabilities of frontier LLMs. It remains to be seen whether the path forward lies in deeper integration with sophisticated external tools, or in developing models so capable that symbolic math systems like CAS become unnecessary.

[Arxiv](https://arxiv.org/abs/2505.23851)
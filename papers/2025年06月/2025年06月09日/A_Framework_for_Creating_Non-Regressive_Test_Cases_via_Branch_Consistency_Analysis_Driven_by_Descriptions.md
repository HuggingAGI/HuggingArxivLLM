# # 基于描述驱动的分支一致性分析创建非回归测试用例框架

发布时间：2025年06月09日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLM）在自动化测试生成中的应用，特别是如何通过描述引导的分支一致性分析来提升缺陷检测能力。论文提出了一个新的框架DISTINCT，并通过实验展示了其在缺陷检测和代码覆盖率上的提升。这属于将LLM应用于具体任务的范畴，因此归类为LLM应用。` `软件工程` `测试生成`

> A Framework for Creating Non-Regressive Test Cases via Branch Consistency Analysis Driven by Descriptions

# 摘要

> 自动化测试生成研究通常假设被测方法是正确的，但在实际开发中，被测方法可能存在缺陷的情况屡见不鲜。我们对EvoSuite、ChatTester和ChatUniTest这三个基于LLM的生成器进行了基准评估，结果发现尽管它们的分支覆盖率高达83%，却未能检测到任何缺陷。
为解决这一问题，我们构建了两个新的基准测试集Defects4J-Desc和QuixBugs-Desc，每个被测方法都附加了自然语言描述（NLD），以帮助理解代码功能。
我们提出了DISTINCT框架，该框架通过描述引导的分支一致性分析，将LLM转变为具有缺陷感知能力的测试生成器。DISTINCT包含三个核心组件：（1）生成器，基于NLD和被测方法生成初始测试；（2）验证器，利用编译器诊断修复无法编译的测试；（3）分析器，通过分支分析对齐测试行为与NLD语义。
实验结果表明，DISTINCT在编译成功率（CSR）和通过率（PR）上比现有方法平均提升了14.64%和6.66%。在缺陷检测率（DDR）方面，它在两个基准测试集上均有显著提升，尤其在Defects4J-Desc上提升了149.26%。此外，DISTINCT还提高了代码覆盖率，平均提升了3.77%的语句覆盖率（SC）和5.36%的分支覆盖率（BC）。这些成果为非回归测试生成设定了新基准，并展示了基于描述的推理如何使LLMs从单纯的覆盖率追逐转向有效的缺陷检测。

> Automated test-generation research overwhelmingly assumes the correctness of focal methods, yet practitioners routinely face non-regression scenarios where the focal method may be defective. A baseline evaluation of EvoSuite and two leading Large Language Model (LLM)-based generators, namely ChatTester and ChatUniTest, on defective focal methods reveals that despite achieving up to 83% of branch coverage, none of the generated tests expose defects.
  To resolve this problem, we first construct two new benchmarks, namely Defects4J-Desc and QuixBugs-Desc, for experiments. In particular, each focal method is equipped with an extra Natural Language Description (NLD) for code functionality understanding.
  Subsequently, we propose DISTINCT, a Description-guided, branch-consistency analysis framework that transforms LLMs into fault-aware test generators. DISTINCT carries three iterative components: (1) a Generator that derives initial tests based on the NLDs and the focal method, (2) a Validator that iteratively fixes uncompilable tests using compiler diagnostics, and (3) an Analyzer that iteratively aligns test behavior with NLD semantics via branch-level analysis.
  Extensive experiments confirm the effectiveness of our approach. Compared to state-of-the-art methods, DISTINCT achieves an average improvement of 14.64% in Compilation Success Rate (CSR) and 6.66% in Passing Rate (PR) across both benchmarks. It notably enhances Defect Detection Rate (DDR) on both benchmarks, with a particularly significant gain of 149.26% observed on Defects4J-Desc. In terms of code coverage, DISTINCT improves Statement Coverage (SC) by an average of 3.77% and Branch Coverage (BC) by 5.36%. These results set a new baseline for non-regressive test generation and highlight how description-driven reasoning enables LLMs to move beyond coverage chasing toward effective defect detection.

[Arxiv](https://arxiv.org/abs/2506.07486)
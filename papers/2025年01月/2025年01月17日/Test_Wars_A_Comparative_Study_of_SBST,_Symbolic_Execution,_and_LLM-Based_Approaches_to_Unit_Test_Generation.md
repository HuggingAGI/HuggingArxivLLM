# 测试之战：SBST、符号执行与LLM驱动的单元测试生成方法对比研究

发布时间：2025年01月17日

`LLM应用` `软件工程` `测试生成`

> Test Wars: A Comparative Study of SBST, Symbolic Execution, and LLM-Based Approaches to Unit Test Generation

# 摘要

> 自动生成测试是软件工程研究的核心课题之一。随着大型语言模型（LLMs）的崛起，这一领域迎来了新的机遇，因为LLMs能够胜任多种任务。然而，与传统的基于搜索的软件测试（SBST）和符号执行相比，基于LLM的方法效果如何仍不明确。本文深入研究了三种工具的自动测试生成方法：EvoSuite（SBST）、Kex（符号执行）和TestSpark（基于LLM的测试生成）。我们在GitBug Java数据集上评估了这些工具的性能，并通过多种执行和特征指标进行了对比。结果显示，尽管基于LLM的测试生成颇具潜力，但在覆盖率上仍不及传统方法。不过，它在变异分数上表现突出，表明LLM对代码的语义理解更为深入。在故障检测能力上，基于LLM的方法则逊色于SBST和符号执行。此外，特征分析表明，所有工具的性能都受被测类（CUT）的复杂性和内部依赖性影响，而基于LLM的方法对CUT的大小尤为敏感。

> Generating tests automatically is a key and ongoing area of focus in software engineering research. The emergence of Large Language Models (LLMs) has opened up new opportunities, given their ability to perform a wide spectrum of tasks. However, the effectiveness of LLM-based approaches compared to traditional techniques such as search-based software testing (SBST) and symbolic execution remains uncertain. In this paper, we perform an extensive study of automatic test generation approaches based on three tools: EvoSuite for SBST, Kex for symbolic execution, and TestSpark for LLM-based test generation. We evaluate tools performance on the GitBug Java dataset and compare them using various execution-based and feature-based metrics. Our results show that while LLM-based test generation is promising, it falls behind traditional methods in terms of coverage. However, it significantly outperforms them in mutation scores, suggesting that LLMs provide a deeper semantic understanding of code. LLM-based approach also performed worse than SBST and symbolic execution-based approaches w.r.t. fault detection capabilities. Additionally, our feature-based analysis shows that all tools are primarily affected by the complexity and internal dependencies of the class under test (CUT), with LLM-based approaches being especially sensitive to the CUT size.

[Arxiv](https://arxiv.org/abs/2501.10200)
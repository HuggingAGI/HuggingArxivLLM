# <翻译失败>

发布时间：2025年02月10日

`LLM应用` `软件工程` `数据安全`

> LessLeak-Bench: A First Investigation of Data Leakage in LLMs Across 83 Software Engineering Benchmarks

# 摘要

> 大型语言模型（LLMs）在软件工程领域得到了广泛应用，涵盖代码生成和自动化程序修复等任务。然而，这些模型依赖于大量且通常未公开的预训练数据集，由此引发了关于数据泄露的严重担忧。具体而言，评估基准数据可能在模型构建阶段被LLMs无意中“接触”，这将严重影响基于LLMs的研究和评估的有效性。尽管LLMs在软件工程领域得到了广泛应用，但目前尚无全面研究评估LLMs在软件工程基准中的数据泄露程度。为填补这一研究空白，本文首次对83个涉及LLMs的软件工程基准进行了大规模数据泄露分析。我们的研究结果表明，总体而言，软件工程基准中的数据泄露程度较低，Python、Java和C/C++基准的平均泄露率分别为4.8%、2.8%和0.7%。然而，部分基准的泄露率相对较高，这引发了对其评估偏见的担忧。例如，QuixBugs和BigCloneBench的泄露率分别为100.0%和55.7%。此外，我们发现数据泄露对LLM评估产生了重大影响。我们还识别了导致高数据泄露的关键因素，例如直接将基准数据纳入预训练数据集，以及使用LeetCode等编码平台构建基准。为应对数据泄露问题，我们引入了LessLeak-Bench，一个全新的基准测试，通过去除83个软件工程基准中的泄露样本，为未来的研究提供了更可靠的LLM评估方法。本研究加深了对软件工程基准中数据泄露的理解，并为未来涉及LLMs的软件工程研究提供了宝贵的见解。

> Large Language Models (LLMs) are widely utilized in software engineering (SE) tasks, such as code generation and automated program repair. However, their reliance on extensive and often undisclosed pre-training datasets raises significant concerns about data leakage, where the evaluation benchmark data is unintentionally ``seen'' by LLMs during the model's construction phase. The data leakage issue could largely undermine the validity of LLM-based research and evaluations. Despite the increasing use of LLMs in the SE community, there is no comprehensive study that assesses the extent of data leakage in SE benchmarks for LLMs yet. To address this gap, this paper presents the first large-scale analysis of data leakage in 83 SE benchmarks concerning LLMs. Our results show that in general, data leakage in SE benchmarks is minimal, with average leakage ratios of only 4.8\%, 2.8\%, and 0.7\% for Python, Java, and C/C++ benchmarks, respectively. However, some benchmarks exhibit relatively higher leakage ratios, which raises concerns about their bias in evaluation. For instance, QuixBugs and BigCloneBench have leakage ratios of 100.0\% and 55.7\%, respectively. Furthermore, we observe that data leakage has a substantial impact on LLM evaluation. We also identify key causes of high data leakage, such as the direct inclusion of benchmark data in pre-training datasets and the use of coding platforms like LeetCode for benchmark construction. To address the data leakage, we introduce \textbf{LessLeak-Bench}, a new benchmark that removes leaked samples from the 83 SE benchmarks, enabling more reliable LLM evaluations in future research. Our study enhances the understanding of data leakage in SE benchmarks and provides valuable insights for future research involving LLMs in SE.

[Arxiv](https://arxiv.org/abs/2502.06215)
# 几秒钟锁定你！——大型语言模型在代码作者归属中的应用

发布时间：2025年01月14日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在源代码作者归属中的应用，具体研究了LLMs在不同编程语言和编码风格间的泛化能力，并提出了改进方法以提高分类准确率。这属于LLMs在实际问题中的应用，因此归类为LLM应用。` `软件工程` `网络安全`

> I Can Find You in Seconds! Leveraging Large Language Models for Code Authorship Attribution

# 摘要

> # 摘要
源代码作者归属在软件取证、抄袭检测和保护软件补丁完整性中至关重要。现有技术多依赖监督机器学习，但由于需要大量标注数据，难以在不同编程语言和编码风格间泛化。受近期LLMs在自然语言作者分析中的突破启发，本文探索了LLMs在源代码作者归属中的应用。
  研究表明，最先进的LLMs能跨语言成功进行源代码作者归属。通过零-shot提示，LLMs能判断两个代码片段是否出自同一作者，MCC达0.78；通过少样本学习，MCC达0.77。此外，LLMs对错误归属攻击展现出一定鲁棒性。
  然而，由于输入令牌限制，简单提示在大量作者时效果不佳。为此，我们提出了一种锦标赛式的大规模归属方法。在GitHub的C++（500位作者，26,355个样本）和Java（686位作者，55,267个样本）数据集上，仅用每位作者的一个参考样本，分类准确率分别达到65%和68.7%。这些结果为LLMs在网络安全和软件工程中的代码作者归属应用开辟了新途径。

> Source code authorship attribution is important in software forensics, plagiarism detection, and protecting software patch integrity. Existing techniques often rely on supervised machine learning, which struggles with generalization across different programming languages and coding styles due to the need for large labeled datasets. Inspired by recent advances in natural language authorship analysis using large language models (LLMs), which have shown exceptional performance without task-specific tuning, this paper explores the use of LLMs for source code authorship attribution.
  We present a comprehensive study demonstrating that state-of-the-art LLMs can successfully attribute source code authorship across different languages. LLMs can determine whether two code snippets are written by the same author with zero-shot prompting, achieving a Matthews Correlation Coefficient (MCC) of 0.78, and can attribute code authorship from a small set of reference code snippets via few-shot learning, achieving MCC of 0.77. Additionally, LLMs show some adversarial robustness against misattribution attacks.
  Despite these capabilities, we found that naive prompting of LLMs does not scale well with a large number of authors due to input token limitations. To address this, we propose a tournament-style approach for large-scale attribution. Evaluating this approach on datasets of C++ (500 authors, 26,355 samples) and Java (686 authors, 55,267 samples) code from GitHub, we achieve classification accuracy of up to 65% for C++ and 68.7% for Java using only one reference per author. These results open new possibilities for applying LLMs to code authorship attribution in cybersecurity and software engineering.

[Arxiv](https://arxiv.org/abs/2501.08165)
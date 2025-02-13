# 前沿综述：模糊测试何方？定向模糊测试中的目标选择方法探索

发布时间：2025年02月12日

`其他` `软件工程`

> SoK: Where to Fuzz? Assessing Target Selection Methods in Directed Fuzzing

# 摘要

> 提升模糊测试性能的常用方法是专注于程序的特定区域，而非整个程序。尽管之前的研究主要探讨了如何到达这些位置，但对这些位置的选择，即“哪里”，目前关注较少。本文首次对模糊测试的目标选择方法进行全面分析。我们研究了来自领先安全与软件工程会议的论文，识别出选择目标的常见方法。通过将这些方法建模为通用评分函数，我们能够在来自OSS-Fuzz项目的1,600多个崩溃案例的语料库上进行比较和测量。我们的分析揭示了目标选择的实用新见解：首先，简单的软件度量显著优于其他方法，包括定向模糊测试中常用的启发式方法，如最近修改的代码或带有 sanitizer 仪器的位置。其次，语言模型是目标选择的有前途的选择。总之，本文为定向模糊测试提供了新的视角，强调了目标选择作为提高性能的独立维度的作用。

> A common paradigm for improving fuzzing performance is to focus on selected regions of a program rather than its entirety. While previous work has largely explored how these locations can be reached, their selection, that is, the where, has received little attention so far. A common paradigm for improving fuzzing performance is to focus on selected regions of a program rather than its entirety. While previous work has largely explored how these locations can be reached, their selection, that is, the where, has received little attention so far. In this paper, we fill this gap and present the first comprehensive analysis of target selection methods for fuzzing. To this end, we examine papers from leading security and software engineering conferences, identifying prevalent methods for choosing targets. By modeling these methods as general scoring functions, we are able to compare and measure their efficacy on a corpus of more than 1,600 crashes from the OSS-Fuzz project. Our analysis provides new insights for target selection in practice: First, we find that simple software metrics significantly outperform other methods, including common heuristics used in directed fuzzing, such as recently modified code or locations with sanitizer instrumentation. Next to this, we identify language models as a promising choice for target selection. In summary, our work offers a new perspective on directed fuzzing, emphasizing the role of target selection as an orthogonal dimension to improve performance.

[Arxiv](https://arxiv.org/abs/2502.08341)
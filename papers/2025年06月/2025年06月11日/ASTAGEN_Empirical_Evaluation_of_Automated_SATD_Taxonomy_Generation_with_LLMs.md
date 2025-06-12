# ASTAGEN：利用大型语言模型自动生成SATD分类法的实证研究

发布时间：2025年06月11日

`LLM应用` `软件工程`

> ASTAGEN: Empirical Evaluation of Automated SATD Taxonomy Generation with LLMs

# 摘要

> 技术债务是指那些影响软件质量的次优代码。当开发人员主动承认这种债务时，我们称之为自我承认的技术债务（SATD）。由于SATD会阻碍软件维护，识别其具体类别是发现质量问题的关键。传统上，构建这类分类学需要手动检查SATD注释及其上下文代码，这种方法不仅耗时耗力，还因标注者主观性而常常不一致。本研究提出了一种名为ASTAGEN的工具，旨在利用大型语言模型（LLMs）实现SATD分类学的自动化生成。ASTAGEN的工作流程是：首先为每个SATD注释生成简洁的解释，然后逐步生成和更新分类，最终构建完整的分类学。我们在三个领域的SATD数据集上对ASTAGEN进行了评估：量子软件、智能合约和机器学习。结果显示，ASTAGEN成功恢复了先前研究中提到的领域特定类别，例如机器学习中的“层配置”。与直接使用LLM相比，ASTAGEN基于解释、迭代的设计使其能够生成更一致的类别分配。即使在处理最大规模的数据集时，ASTAGEN也能在不到两小时且成本不到一美元的情况下完成分类学构建。这些结果表明，尽管完全自动化仍具挑战性，但ASTAGEN为半自动化的分类学构建提供了有力支持。此外，我们的研究还为未来工作指明了方向，例如在其他领域实现自动分类学生成。

> Technical debt refers to suboptimal code that degrades software quality. When developers intentionally introduce such debt, it is called self-admitted technical debt (SATD). Since SATD hinders maintenance, identifying its categories is key to uncovering quality issues. Traditionally, constructing such taxonomies requires manually inspecting SATD comments and surrounding code, which is time-consuming, labor-intensive, and often inconsistent due to annotator subjectivity. This study presents ASTAGEN, an initial step toward automating SATD taxonomy generation using large language models (LLMs). Given a comment and its surrounding code, ASTAGEN first generates a concise explanation for each SATD comment, then incrementally generates and updates categories to construct a taxonomy. We evaluate ASTAGEN on SATD datasets from three domains: quantum software, smart contracts, and machine learning. It successfully recovers domain-specific categories reported in prior work, such as Layer Configuration in machine learning. Compared to a naive use of an LLM, ASTAGEN produces more consistent category assignments due to its explanation-driven, iterative design. It also completes taxonomy generation in under two hours and for less than one USD, even on the largest dataset. These results suggest that while full automation remains challenging, ASTAGEN is able to support semi-automated taxonomy construction. Furthermore, our work opens up avenues for future work, such as automatic taxonomy generation in other areas.

[Arxiv](https://arxiv.org/abs/2506.09601)
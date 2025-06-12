# 形式化方法与可读性携手：JML Java代码的自动文档生成

发布时间：2025年06月10日

`LLM应用` `软件工程` `文档生成`

> Formal Methods Meets Readability: Auto-Documenting JML Java Code

# 摘要

> 本文探讨了使用Java建模语言（JML）的正式规范能否提升大型语言模型（LLM）生成的Javadocs质量。虽然LLMs在从代码生成文档方面表现出色，但我们假设引入经过形式验证的不变式能够带来更完整和准确的结果。我们系统地比较了JML标注与非标注Java类生成的文档，通过自动化指标和专家分析评估其质量。研究发现，JML显著提升了类级文档的完整性，在方法级则有适度的提升。形式规范尤其擅长捕捉代码文档中常被忽视的复杂类不变式和设计契约。出现了一个阈值效应，即对于拥有更丰富不变式的类，JML的优势更加明显。虽然JML增强了规范覆盖率，但对核心描述质量的影响有限，表明形式规范主要确保全面覆盖，而非根本性改变实现描述。这些结果为采用形式方法的软件团队提供了可操作的见解，突显了JML明显优势的场景。本研究通过展示形式方法与LLMs如何协同提升文档质量，为AI辅助软件文档研究做出了贡献。

> This paper investigates whether formal specifications using Java Modeling Language (JML) can enhance the quality of Large Language Model (LLM)-generated Javadocs. While LLMs excel at producing documentation from code alone, we hypothesize that incorporating formally verified invariants yields more complete and accurate results. We present a systematic comparison of documentation generated from JML-annotated and non-annotated Java classes, evaluating quality through both automated metrics and expert analysis. Our findings demonstrate that JML significantly improves class-level documentation completeness, with more moderate gains at the method level. Formal specifications prove particularly effective in capturing complex class invariants and design contracts that are frequently overlooked in code-only documentation. A threshold effect emerges, where the benefits of JML become more pronounced for classes with richer sets of invariants. While JML enhances specification coverage, its impact on core descriptive quality is limited, suggesting that formal specifications primarily ensure comprehensive coverage rather than fundamentally altering implementation descriptions. These results offer actionable insights for software teams adopting formal methods in documentation workflows, highlighting scenarios where JML provides clear advantages. The study contributes to AI-assisted software documentation research by demonstrating how formal methods and LLMs can synergistically improve documentation quality.

[Arxiv](https://arxiv.org/abs/2506.09230)
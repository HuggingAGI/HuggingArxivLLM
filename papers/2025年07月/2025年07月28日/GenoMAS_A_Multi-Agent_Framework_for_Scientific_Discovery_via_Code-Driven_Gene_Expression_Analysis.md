# GenoMAS：基于代码驱动基因表达分析的多智能体科学发现框架

发布时间：2025年07月28日

`Agent` `生物医学` `基因组学`

> GenoMAS: A Multi-Agent Framework for Scientific Discovery via Code-Driven Gene Expression Analysis

# 摘要

> 基因表达分析是生物医学研究的重要突破口，但面对复杂庞大的转录组数据，如何提取有价值的信息仍是一项艰巨挑战。现有自动化解决方案往往顾此失彼：要么是 rigid 的工作流程难以应对特殊情况，要么是过度自主的代理系统缺乏科研所需的严谨精度。GenoMAS带来了全新解决方案：它打造了一支基于LLM的科学家团队，完美融合了结构化工作流程的可靠性与自主代理的灵活性。GenoMAS通过类型化消息传递协议，协调六个各具专长的LLM代理协同工作，每个代理都在共享的分析平台上发挥独特优势。GenoMAS的核心是其引导式规划框架：编程代理将复杂的任务指南分解为可执行的行动单元，并在每个关键节点做出推进、修订、绕过或回溯的决策，从而在保持逻辑连贯性的同时，灵活应对基因组数据的独特性。在GenoTEX基准测试中，GenoMAS的数据预处理综合相似性相关性达到89.13%，基因识别F1值达到60.48%，分别超越现有最优方法10.61%和16.85%。GenoMAS不仅在指标上表现出色，更重要的是它能够揭示经文献验证的生物合理基因表型关联，并自动调整潜在混杂因素。代码可在https://github.com/Liu-Hy/GenoMAS获取。

> Gene expression analysis holds the key to many biomedical discoveries, yet extracting insights from raw transcriptomic data remains formidable due to the complexity of multiple large, semi-structured files and the need for extensive domain expertise. Current automation approaches are often limited by either inflexible workflows that break down in edge cases or by fully autonomous agents that lack the necessary precision for rigorous scientific inquiry. GenoMAS charts a different course by presenting a team of LLM-based scientists that integrates the reliability of structured workflows with the adaptability of autonomous agents. GenoMAS orchestrates six specialized LLM agents through typed message-passing protocols, each contributing complementary strengths to a shared analytic canvas. At the heart of GenoMAS lies a guided-planning framework: programming agents unfold high-level task guidelines into Action Units and, at each juncture, elect to advance, revise, bypass, or backtrack, thereby maintaining logical coherence while bending gracefully to the idiosyncrasies of genomic data.
  On the GenoTEX benchmark, GenoMAS reaches a Composite Similarity Correlation of 89.13% for data preprocessing and an F$_1$ of 60.48% for gene identification, surpassing the best prior art by 10.61% and 16.85% respectively. Beyond metrics, GenoMAS surfaces biologically plausible gene-phenotype associations corroborated by the literature, all while adjusting for latent confounders. Code is available at https://github.com/Liu-Hy/GenoMAS.

[Arxiv](https://arxiv.org/abs/2507.21035)
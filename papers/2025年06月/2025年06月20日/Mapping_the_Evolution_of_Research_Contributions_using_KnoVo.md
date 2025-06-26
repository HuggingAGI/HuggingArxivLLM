# # 使用 KnoVo 分析研究贡献的演变历程

发布时间：2025年06月20日

`LLM应用` `科学研究` `文献分析`

> Mapping the Evolution of Research Contributions using KnoVo

# 摘要

> 本文介绍了KnoVo（知识进化），一个用于量化和分析科学文献中研究新颖性演变的智能框架。与传统的仅关注影响力的引文分析不同，KnoVo通过多层引文网络评估某篇论文相对于前后研究的新颖性。基于目标论文的摘要，KnoVo利用大型语言模型（LLMs）动态提取比较维度（如方法、应用、数据集），并在此基础上与相关文献进行比较。受锦标赛选择启发的比较分析生成定量的新颖性评分，反映目标论文在具体方面的相对改进、等同或不足。通过聚合这些评分并进行可视化展示（例如动态进化图和比较雷达图），KnoVo不仅帮助研究人员评估原创性、识别相似工作，还能跟踪特定研究维度的知识演变、发现研究空白，并探索跨学科联系。我们通过分析20篇来自多个科学领域的多样化论文，详细展示了这些功能，并报告了KnoVo框架内各种开源LLMs的表现。

> This paper presents KnoVo (Knowledge Evolution), an intelligent framework designed for quantifying and analyzing the evolution of research novelty in the scientific literature. Moving beyond traditional citation analysis, which primarily measures impact, KnoVo determines a paper's novelty relative to both prior and subsequent work within its multilayered citation network. Given a target paper's abstract, KnoVo utilizes Large Language Models (LLMs) to dynamically extract dimensions of comparison (e.g., methodology, application, dataset). The target paper is then compared to related publications along these same extracted dimensions. This comparative analysis, inspired by tournament selection, yields quantitative novelty scores reflecting the relative improvement, equivalence, or inferiority of the target paper in specific aspects. By aggregating these scores and visualizing their progression, for instance, through dynamic evolution graphs and comparative radar charts, KnoVo facilitates researchers not only to assess originality and identify similar work, but also to track knowledge evolution along specific research dimensions, uncover research gaps, and explore cross-disciplinary connections. We demonstrate these capabilities through a detailed analysis of 20 diverse papers from multiple scientific fields and report on the performance of various open-source LLMs within the KnoVo framework.

[Arxiv](https://arxiv.org/abs/2506.17508)
# 地平线扫描能够通过新型信息检索和人工智能工具加速。

发布时间：2025年04月02日

`LLM应用`

> Horizon Scans can be accelerated using novel information retrieval and artificial intelligence tools

# 摘要

> 引言：医疗领域的地平线扫描用于评估创新的早期信号，这对于及时采纳至关重要。然而，当前的地平线扫描在从新闻等非结构化来源中高效检索和分析信息方面面临挑战，亟需创新工具来应对这一需求。

方法：本研究介绍了SCANAR和AIDOC，这两个基于Python的开源工具，旨在提升地平线扫描的效率。SCANAR能够自动检索和处理新闻文章，提供去重和无监督相关性排序等功能。AIDOC则通过利用AI技术，根据相关性重新排序文本数据，并运用神经网络进行语义相似性分析，进而将可能相关的条目优先提交给人类审核。

结果：本研究使用了12个内部地平线扫描数据集和4个外部基准数据集。SCANAR通过自动化流程提升了检索效率，这些流程此前依赖于手动操作。AIDOC展示了节省人力的潜力，在95%的召回率下，将手动审核工作量减少了约62%。与基准数据的比较分析表明，AIDOC的表现与现有的系统综述自动化工具相当，尽管其性能因数据集特性而异。针对我们的新闻数据集的小规模案例研究显示，在主动学习过程中整合大型语言模型，有望加快相关文章在新闻数据集中的检测速度。

结论：验证结果表明，SCANAR和AIDOC通过简化数据检索和优先排序，具备提升地平线扫描效率的潜力。这些工具可能缓解方法学上的局限性，并使更广泛、更快速的地平线扫描成为可能。建议进一步研究以优化这些模型，并设计新的工作流程和验证过程，以整合大型语言模型。

> Introduction: Horizon scanning in healthcare assesses early signals of innovation, crucial for timely adoption. Current horizon scanning faces challenges in efficient information retrieval and analysis, especially from unstructured sources like news, presenting a need for innovative tools. Methodology: The study introduces SCANAR and AIDOC, open-source Python-based tools designed to improve horizon scanning. SCANAR automates the retrieval and processing of news articles, offering functionalities such as de-duplication and unsupervised relevancy ranking. AIDOC aids filtration by leveraging AI to reorder textual data based on relevancy, employing neural networks for semantic similarity, and subsequently prioritizing likely relevant entries for human review. Results: Twelve internal datasets from horizon scans and four external benchmarking datasets were used. SCANAR improved retrieval efficiency by automating processes previously dependent on manual labour. AIDOC displayed work-saving potential, achieving around 62% reduction in manual review efforts at 95% recall. Comparative analysis with benchmarking data showed AIDOC's performance was similar to existing systematic review automation tools, though performance varied depending on dataset characteristics. A smaller case-study on our news datasets shows the potential of ensembling large language models within the active-learning process for faster detection of relevant articles across news datasets. Conclusion: The validation indicates that SCANAR and AIDOC show potential to enhance horizon scanning efficiency by streamlining data retrieval and prioritisation. These tools may alleviate methodological limitations and allow broader, swifter horizon scans. Further studies are suggested to optimize these models and to design new workflows and validation processes that integrate large language models.

[Arxiv](https://arxiv.org/abs/2504.01627)
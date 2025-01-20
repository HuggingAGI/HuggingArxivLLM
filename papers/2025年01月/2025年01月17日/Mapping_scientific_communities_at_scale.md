# 大规模科学社区图谱绘制

发布时间：2025年01月17日

`LLM应用

理由：该论文摘要中提到使用大型语言模型（Mistral Nemo）为检测到的社区打标签，这表明该研究利用了大型语言模型（LLM）的功能来支持科学社区图谱的构建和分析。因此，这篇论文属于LLM应用的范畴。` `科学研究` `数据分析`

> Mapping scientific communities at scale

# 摘要

> # 摘要
本研究提出了一种创新方法，用于大规模绘制科学社区图谱，解决了大型文献计量数据集中网络分析的难题。我们利用法国研究门户scanR的丰富元数据，并通过高级过滤技术优先筛选实体间的强关联，构建了详细且可扩展的网络图谱。这些图谱通过持久标识符和专用算法对作者、机构和主题进行系统消歧，进一步优化。该框架整合了Elasticsearch用于高效数据聚合，Graphology用于网络空间化（Force Atlas2）和社区检测（Louvain算法），以及VOSviewer用于网络可视化。我们使用大型语言模型（Mistral Nemo）为检测到的社区打标签，并通过OpenAlex数据估算引用次数，以识别热门话题。这种可扩展的方法能够深入挖掘研究合作与主题结构，为科学政策和资金决策提供战略支持。这些工具不仅在全球（国家）层面有效，还可应用于法国任何研究机构（从大型研究组织到实验室），并可通过iframe集成。scanR社区分析工具已上线，访问地址为[https://scanr.enseignementsup-recherche.gouv.fr/networks/get-started](https://scanr.enseignementsup-recherche.gouv.fr/networks/get-started)。所有工具和方法论均在GitHub开源，仓库地址为[https://github.com/dataesr/scanr-ui](https://github.com/dataesr/scanr-ui)。

> This study introduces a novel methodology for mapping scientific communities at scale, addressing challenges associated with network analysis in large bibliometric datasets. By leveraging enriched publication metadata from the French research portal scanR and applying advanced filtering techniques to prioritize the strongest interactions between entities, we construct detailed, scalable network maps. These maps are enhanced through systematic disambiguation of authors, affiliations, and topics using persistent identifiers and specialized algorithms. The proposed framework integrates Elasticsearch for efficient data aggregation, Graphology for network spatialization (Force Atltas2) and community detection (Louvain algorithm) and VOSviewer for network vizualization. A Large Language Model (Mistral Nemo) is used to label the communities detected and OpenAlex data helps to enrich the results with citation counts estimation to detect hot topics. This scalable approach enables insightful exploration of research collaborations and thematic structures, with potential applications for strategic decision-making in science policy and funding. These web tools are effective at the global (national) scale but are also available (and can be integrated via iframes) on the perimeter of any French research institution (from large research organisms to any laboratory). The scanR community analysis tool is available online [https://scanr.enseignementsup-recherche.gouv.fr/networks/get-started](https://scanr.enseignementsup-recherche.gouv.fr/networks/get-started). All tools and methodologies are open-source on the repo [https://github.com/dataesr/scanr-ui](https://github.com/dataesr/scanr-ui)

[Arxiv](https://arxiv.org/abs/2501.10035)
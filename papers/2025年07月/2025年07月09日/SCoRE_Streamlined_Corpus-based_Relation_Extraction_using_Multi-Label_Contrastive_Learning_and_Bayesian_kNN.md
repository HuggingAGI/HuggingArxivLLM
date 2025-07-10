# # SCoRE: 通过基于语料库的简化方法进行关系抽取，采用多标签对比学习和贝叶斯k近邻技术

发布时间：2025年07月09日

`LLM应用` `知识图谱` `关系抽取`

> SCoRE: Streamlined Corpus-based Relation Extraction using Multi-Label Contrastive Learning and Bayesian kNN

# 摘要

> 知识图谱（KG）的高效构建需求推动了关系抽取（RE）技术的发展，特别是在低监督环境下。我们提出了一种名为SCoRE的模块化、经济高效的句级关系抽取系统，旨在与预训练大型语言模型（PLMs）无缝集成，同时具备强大的适应性和抗噪声能力。SCoRE支持灵活的预训练模型切换，无需微调，并能轻松适应不同语料库和知识图谱。通过结合监督对比学习与贝叶斯k-近邻（kNN）分类器进行多标签分类，SCoRE在处理噪声标注的远程监督语料库时仍能保持优异性能。我们还提出了两个创新评估指标：关联结构距离（CSD）和在R处的精度（P@R），分别用于衡量关系模式与知识图谱结构的契合度，以及评估其作为推荐系统的实用性。此外，我们发布了Wiki20d基准数据集，模拟仅依赖知识图谱导出标注的真实世界RE条件。实验结果表明，SCoRE不仅在五个基准数据集上达到了现有最优水平，还显著降低了能源消耗。进一步分析表明，SCoRE的极简设计优于传统复杂模型，展现出独特优势。凭借高效、灵活和可扩展的特点，SCoRE为真实世界的关系抽取应用提供了理想解决方案。

> The growing demand for efficient knowledge graph (KG) enrichment leveraging external corpora has intensified interest in relation extraction (RE), particularly under low-supervision settings. To address the need for adaptable and noise-resilient RE solutions that integrate seamlessly with pre-trained large language models (PLMs), we introduce SCoRE, a modular and cost-effective sentence-level RE system. SCoRE enables easy PLM switching, requires no finetuning, and adapts smoothly to diverse corpora and KGs. By combining supervised contrastive learning with a Bayesian k-Nearest Neighbors (kNN) classifier for multi-label classification, it delivers robust performance despite the noisy annotations of distantly supervised corpora. To improve RE evaluation, we propose two novel metrics: Correlation Structure Distance (CSD), measuring the alignment between learned relational patterns and KG structures, and Precision at R (P@R), assessing utility as a recommender system. We also release Wiki20d, a benchmark dataset replicating real-world RE conditions where only KG-derived annotations are available. Experiments on five benchmarks show that SCoRE matches or surpasses state-of-the-art methods while significantly reducing energy consumption. Further analyses reveal that increasing model complexity, as seen in prior work, degrades performance, highlighting the advantages of SCoRE's minimal design. Combining efficiency, modularity, and scalability, SCoRE stands as an optimal choice for real-world RE applications.

[Arxiv](https://arxiv.org/abs/2507.06895)
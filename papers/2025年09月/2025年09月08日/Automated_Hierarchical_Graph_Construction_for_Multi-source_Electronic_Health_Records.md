# 面向多源电子健康记录的自动化层次化图构建

发布时间：2025年09月08日

`其他` `医疗健康`

> Automated Hierarchical Graph Construction for Multi-source Electronic Health Records

# 摘要

> 电子健康记录（EHRs）涵盖诊断、用药、实验室结果等各类临床数据，在转化研究中前景广阔。EHR数据不仅推动了疾病预防的进步、优化了临床试验招募，还为真实世界证据的生成提供了支撑。整合跨机构EHRs虽能开展大规模、可推广的研究（如捕捉罕见病与人群多样性），却受限于医疗代码的异质性、机构专属术语及数据结构缺乏标准化等问题。这些障碍制约了EHR分析在可解释性、可比性和可扩展性上的表现，凸显出开发稳健方法以协调分布式异构数据并提取有效见解的迫切需求。为此，我们提出MASH（多源自动化结构化层次）——一个全自动框架：它借助神经最优传输对齐跨机构医疗代码，并通过学习双曲嵌入构建层次图。训练时，MASH融合预训练语言模型、共现模式、文本描述及监督标签等多源信息，更精准地捕捉医疗概念间的语义与层次关系。将其应用于真实EHR数据（含诊断、用药、实验室代码）后，生成的可解释层次图能助力异构临床数据的导航与理解。值得关注的是，它首次为非结构化本地实验室代码构建了自动化层次结构，为下游应用奠定了基础参考。

> Electronic Health Records (EHRs), comprising diverse clinical data such as diagnoses, medications, and laboratory results, hold great promise for translational research. EHR-derived data have advanced disease prevention, improved clinical trial recruitment, and generated real-world evidence. Synthesizing EHRs across institutions enables large-scale, generalizable studies that capture rare diseases and population diversity, but remains hindered by the heterogeneity of medical codes, institution-specific terminologies, and the absence of standardized data structures. These barriers limit the interpretability, comparability, and scalability of EHR-based analyses, underscoring the need for robust methods to harmonize and extract meaningful insights from distributed, heterogeneous data. To address this, we propose MASH (Multi-source Automated Structured Hierarchy), a fully automated framework that aligns medical codes across institutions using neural optimal transport and constructs hierarchical graphs with learned hyperbolic embeddings. During training, MASH integrates information from pre-trained language models, co-occurrence patterns, textual descriptions, and supervised labels to capture semantic and hierarchical relationships among medical concepts more effectively. Applied to real-world EHR data, including diagnosis, medication, and laboratory codes, MASH produces interpretable hierarchical graphs that facilitate the navigation and understanding of heterogeneous clinical data. Notably, it generates the first automated hierarchies for unstructured local laboratory codes, establishing foundational references for downstream applications.

[Arxiv](https://arxiv.org/abs/2509.06576)
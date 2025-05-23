# AutoData：一个多智能体系统（MAS），助力开放网络数据采集

发布时间：2025年05月21日

`Agent` `数据驱动系统` `数据收集`

> AutoData: A Multi-Agent System for Open Web Data Collection

# 摘要

> 数据驱动系统与人工智能技术的迅猛发展，使得对高质量网络数据集的需求日益迫切。尽管现有数据集已展现出其价值，但传统网络数据收集方法在人力投入和可扩展性方面仍存在明显局限。当前的数据收集方案主要分为两类：一类是基于包装器的方法，其适应性和可重复性不足；另一类则是基于大型语言模型（LLM）的方法，但其计算和财务成本较高。为应对这些挑战，我们推出了一种全新的自动化网络数据收集系统——AutoData。该系统只需极少量的人工干预，用户仅需提供一个自然语言指令即可指定所需数据集。此外，AutoData采用了强大的多智能体架构，其中包含由中央任务管理器协调的新型有向消息超图，能够有效组织跨研究与开发团队的智能体协作。我们还引入了一种新型超图缓存系统，以优化多智能体协作流程，实现高效自动化数据收集，并有效缓解现有基于LLM系统中普遍存在的Token成本问题。同时，我们推出了Instruct2DS这一新基准数据集，支持从学术、金融和体育三个领域的网络资源中实时收集数据。通过在Instruct2DS和三个现有基准数据集上的全面评估，AutoData展现出了优于基线方法的卓越性能。绘本收集和从调查中提取论文等具有挑战性的任务案例研究进一步证明了其适用性。我们的源代码和数据集现已在GitHub上开放获取，链接为https://github.com/GraphResearcher/AutoData。

> The exponential growth of data-driven systems and AI technologies has intensified the demand for high-quality web-sourced datasets. While existing datasets have proven valuable, conventional web data collection approaches face significant limitations in terms of human effort and scalability. Current data-collecting solutions fall into two categories: wrapper-based methods that struggle with adaptability and reproducibility, and large language model (LLM)-based approaches that incur substantial computational and financial costs. To address these challenges, we propose AutoData, a novel multi-agent system for Automated web Data collection, that requires minimal human intervention, i.e., only necessitating a natural language instruction specifying the desired dataset. In addition, AutoData is designed with a robust multi-agent architecture, featuring a novel oriented message hypergraph coordinated by a central task manager, to efficiently organize agents across research and development squads. Besides, we introduce a novel hypergraph cache system to advance the multi-agent collaboration process that enables efficient automated data collection and mitigates the token cost issues prevalent in existing LLM-based systems. Moreover, we introduce Instruct2DS, a new benchmark dataset supporting live data collection from web sources across three domains: academic, finance, and sports. Comprehensive evaluations over Instruct2DS and three existing benchmark datasets demonstrate AutoData's superior performance compared to baseline methods. Case studies on challenging tasks such as picture book collection and paper extraction from surveys further validate its applicability. Our source code and dataset are available at https://github.com/GraphResearcher/AutoData.

[Arxiv](https://arxiv.org/abs/2505.15859)
# # AutoData：一个用于开放网络数据采集的多智能体系统

发布时间：2025年05月21日

`Agent` `数据科学` `数据收集`

> AutoData: A Multi-Agent System for Open Web Data Collection

# 摘要

> 数据驱动系统与AI技术的指数级增长，让高质量网络数据集的需求日益迫切。尽管现有数据集已展现出其价值，但传统网络数据收集方法在人工投入与可扩展性方面仍存在明显局限。当前的数据收集方案主要分为两类：一类是基于包装器的方法，难以应对适应性与可重复性问题；另一类是基于大型语言模型（LLM）的方法，但会产生高昂的计算与财务成本。为解决这些难题，我们提出了一种全新的自动化网络数据收集多智能体系统AutoData，仅需极少量人工干预——只需提供一条自然语言指令来指定所需数据集。此外，AutoData采用了一种强大的多智能体架构，包含由中央任务管理器协调的新型定向消息超图，能够高效组织跨研究与开发团队的智能体。同时，我们引入了一种新型超图缓存系统，以促进多智能体协作流程，实现高效自动化数据收集，并有效缓解现有LLM系统中普遍存在的令牌成本问题。此外，我们推出了一项新基准数据集Instruct2DS，支持从学术、金融与体育三大领域的网络来源实时采集数据。通过在Instruct2DS以及三个现有基准数据集上的全面评估，AutoData相较于基线方法展现出更卓越的性能。针对绘本收集与从调查中提取论文等具有挑战性的任务的案例研究，进一步验证了其适用性。我们的源代码与数据集可在https://github.com/GraphResearcher/AutoData获取。

> The exponential growth of data-driven systems and AI technologies has intensified the demand for high-quality web-sourced datasets. While existing datasets have proven valuable, conventional web data collection approaches face significant limitations in terms of human effort and scalability. Current data-collecting solutions fall into two categories: wrapper-based methods that struggle with adaptability and reproducibility, and large language model (LLM)-based approaches that incur substantial computational and financial costs. To address these challenges, we propose AutoData, a novel multi-agent system for Automated web Data collection, that requires minimal human intervention, i.e., only necessitating a natural language instruction specifying the desired dataset. In addition, AutoData is designed with a robust multi-agent architecture, featuring a novel oriented message hypergraph coordinated by a central task manager, to efficiently organize agents across research and development squads. Besides, we introduce a novel hypergraph cache system to advance the multi-agent collaboration process that enables efficient automated data collection and mitigates the token cost issues prevalent in existing LLM-based systems. Moreover, we introduce Instruct2DS, a new benchmark dataset supporting live data collection from web sources across three domains: academic, finance, and sports. Comprehensive evaluations over Instruct2DS and three existing benchmark datasets demonstrate AutoData's superior performance compared to baseline methods. Case studies on challenging tasks such as picture book collection and paper extraction from surveys further validate its applicability. Our source code and dataset are available at https://github.com/GraphResearcher/AutoData.

[Arxiv](https://arxiv.org/abs/2505.15859)
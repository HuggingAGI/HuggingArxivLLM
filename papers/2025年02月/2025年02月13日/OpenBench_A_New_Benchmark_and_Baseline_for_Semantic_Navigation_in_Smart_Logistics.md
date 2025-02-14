# OpenBench：为智能物流中的语义导航提供新基准与基线

发布时间：2025年02月13日

`LLM应用` `智能物流` `机器人`

> OpenBench: A New Benchmark and Baseline for Semantic Navigation in Smart Logistics

# 摘要

> 智能物流对高效最后一公里配送的需求激增，凸显了自主机器人在提升运营效率和降低成本中的重要作用。然而，传统依赖高精度地图的导航方法资源消耗巨大，而基于学习的方法在现实场景中的泛化能力往往不尽如人意。为解决这些挑战，本研究提出了Openstreetmap增强的开放语义导航（OPEN）系统，该系统巧妙结合基础模型与经典算法，专为可扩展的户外导航而设计。

该系统采用现成的OpenStreetMap（OSM）实现灵活的地图表示，彻底告别了繁琐的预地图绘制工作。同时，系统借助大型语言模型（LLMs）精准理解配送指令，并通过视觉-语言模型（VLMs）实现全局定位、地图更新及门牌号识别等关键功能。针对现有基准测试在评估最后一公里配送能力方面的不足，本研究推出了一项专为住宅区户外导航设计的新基准测试，真实还原了自主配送系统在现实世界中面临的诸多挑战。

在模拟环境和真实世界环境中的大量实验均验证了所提出的系统在提升导航效率和可靠性方面的显著优势。为了推动相关领域的进一步研究，我们的代码和基准测试已面向公众开放。

> The increasing demand for efficient last-mile delivery in smart logistics underscores the role of autonomous robots in enhancing operational efficiency and reducing costs. Traditional navigation methods, which depend on high-precision maps, are resource-intensive, while learning-based approaches often struggle with generalization in real-world scenarios. To address these challenges, this work proposes the Openstreetmap-enhanced oPen-air sEmantic Navigation (OPEN) system that combines foundation models with classic algorithms for scalable outdoor navigation. The system uses off-the-shelf OpenStreetMap (OSM) for flexible map representation, thereby eliminating the need for extensive pre-mapping efforts. It also employs Large Language Models (LLMs) to comprehend delivery instructions and Vision-Language Models (VLMs) for global localization, map updates, and house number recognition. To compensate the limitations of existing benchmarks that are inadequate for assessing last-mile delivery, this work introduces a new benchmark specifically designed for outdoor navigation in residential areas, reflecting the real-world challenges faced by autonomous delivery systems. Extensive experiments in simulated and real-world environments demonstrate the proposed system's efficacy in enhancing navigation efficiency and reliability. To facilitate further research, our code and benchmark are publicly available.

[Arxiv](https://arxiv.org/abs/2502.09238)
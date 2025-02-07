# 从事故到洞察：多模态数据助力场景驱动的自动驾驶系统测试

发布时间：2025年02月04日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来生成自动驾驶系统（ADS）的测试用例。具体来说，论文提出了一个名为TRACE的框架，该框架利用LLMs从车祸报告中提取环境和道路网络信息，并构建了一个具备路径规划能力的ChatGPT LLM（TrackMate）来生成车辆轨迹。这些应用都直接依赖于LLMs的能力，因此将其分类为“LLM应用”是合适的。` `自动驾驶` `软件测试`

> From Accidents to Insights: Leveraging Multimodal Data for Scenario-Driven ADS Testing

# 摘要

> 自动驾驶系统（ADS）的迅猛发展对软件测试提出了更高要求，以确保其安全性和可靠性。然而，自动化生成可扩展且具体的测试场景仍是一大难题。现有的基于场景的测试用例生成方法常受限于不真实的场景和不准确的车辆轨迹，这些问题主要源于数据提取过程中地图信息的丢失，以及缺乏有效的验证机制来减少大型语言模型（LLMs）中的幻觉。本文提出了TRACE，一个面向关键场景的ADS测试用例生成框架。通过多模态数据从真实车祸报告中提取复杂场景，TRACE以较少数据构建了大量关键测试用例，显著提升了ADS的bug检测效率。我们采用上下文学习、思维链提示和自我验证方法，利用LLMs从车祸报告中提取环境和道路网络信息。对于车辆轨迹规划，基于包含地图信息和车辆坐标的数据，我们构建了一个具备路径规划能力的ChatGPT LLM，命名为TrackMate。基于50个现有车祸报告，我们的方法在MetaDrive和BeamNG两个仿真平台上成功测试了三个ADS模型。在生成的290个测试场景中，127个被识别为关键场景，因其导致了车辆碰撞。此外，用户反馈表明，TRACE在场景重建准确性上表现卓越，77.5%的场景被评为“大部分”或“完全”一致，而最相关的SOTA方法LCTGen仅为27%。

> The rapid advancements in Autonomous Driving Systems (ADS) have necessitated robust software testing to ensure safety and reliability. However, automating the generation of scalable and concrete test scenarios remains a significant challenge. Current scenario-based test case generation methods often face limitations, such as unrealistic scenes and inaccurate vehicle trajectories. These challenges largely result from the loss of map information during data extraction and the lack of an effective verification mechanism to mitigate hallucinations in large language models (LLMs). This paper introduces TRACE, a scenario-based ADS Test case Generation framework for Critical Scenarios. By leveraging multimodal data to extract challenging scenarios from real-world car crash reports, TRACE constructs numerous critical test cases with less data, significantly enhancing ADS bug detection efficiency. Using in-context learning, chain-of-thought prompting, and self-validation approaches, we use LLMs to extract environmental and road network information from crash reports. For vehicle trajectory planning, data containing map information and vehicle coordinates serves as a knowledge base to build a ChatGPT-based LLM with path-planning capabilities, which we named TrackMate. Based on 50 existing crash reports, our approach successfully tested three ADS models across two simulation platforms, MetaDrive and BeamNG. Of the 290 constructed test scenarios, 127 are identified as critical, as they resulted in vehicle collisions. Additionally, user feedback reveals that TRACE demonstrates superior scenario reconstruction accuracy, with 77.5% of the scenarios being rated as 'mostly or 'totally' consistent, compared to only 27% for the most related SOTA, LCTGen.

[Arxiv](https://arxiv.org/abs/2502.02025)
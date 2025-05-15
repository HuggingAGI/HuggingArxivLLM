# # AI的贪婪程度如何？评估LLM推理的能源、水和碳足迹

发布时间：2025年05月14日

`其他

理由：这篇论文探讨了大型语言模型（LLM）推理阶段的环境影响，包括能源消耗、水资源和碳排放等，属于环境影响评估的范畴，不属于LLM应用或LLM理论，因此归类为其他。` `可持续性` `环境科学`

> How Hungry is AI? Benchmarking Energy, Water, and Carbon Footprint of LLM Inference

# 摘要

> # 理解 LLM 推理的环境足迹：从个体高效到全球资源消耗的悖论
随着大型语言模型 (LLMs) 在各行业的普及，理解其推理阶段的环境足迹不再是可有可无的选择，而是势在必行的课题。然而，现有的大部分研究往往存在以下问题：要么将专有模型排除在外，要么忽视基础设施的差异性和额外开销，甚至有的研究只关注训练阶段，而忽视推理阶段的实际影响。尽管推理阶段在 AI 的环境影响中占据越来越重要的地位，但这一问题仍未得到充分重视。

为了解决这一研究空白，本文提出了一种基于基础设施感知的基准框架，用于量化部署在商业数据中心的 30 款先进 LLM 模型的推理环境足迹。我们的框架结合了公开 API 的性能数据、地区特定的环境影响因子以及硬件配置的统计推断。此外，我们还利用了交叉效率数据包络分析 (DEA) 来根据性能与环境成本的相对关系对模型进行排序。

研究结果揭示了几个关键发现：o3 和 DeepSeek-R1 是能耗最高的模型，每处理一个长提示需要消耗超过 33 瓦时的电量，远超 GPT-4.1 nano 的 0.47 瓦时，差距超过 70 倍。而 Claude-3.7 Sonnet 则在生态效率方面表现最佳。尽管一个简短的 GPT-4o 查询仅消耗 0.43 瓦时的电量，但如果将这一数字扩展到每天 7 亿次查询，其年度环境影响将十分显著。这包括相当于 3.5 万个美国家庭一年用电量的电力消耗、相当于 120 万人年度饮用水需求的淡水蒸发量，以及需要一个芝加哥大小的森林来抵消的碳排放量。

这些发现揭示了一个日益突出的悖论：尽管单个查询的资源消耗微乎其微，但全球范围内的海量查询却导致了资源消耗的显著增加。本研究为量化 LLM 部署的可持续性提供了一种标准化且实证支持的方法，为未来 AI 开发的环境责任和可持续性标准奠定了基础。

> As large language models (LLMs) spread across industries, understanding their environmental footprint at the inference level is no longer optional; it is essential. However, most existing studies exclude proprietary models, overlook infrastructural variability and overhead, or focus solely on training, even as inference increasingly dominates AI's environmental impact. To bridge this gap, this paper introduces a novel infrastructure-aware benchmarking framework for quantifying the environmental footprint of LLM inference across 30 state-of-the-art models as deployed in commercial data centers. Our framework combines public API performance data with region-specific environmental multipliers and statistical inference of hardware configurations. We additionally utilize cross-efficiency Data Envelopment Analysis (DEA) to rank models by performance relative to environmental cost. Our results show that o3 and DeepSeek-R1 emerge as the most energy-intensive models, consuming over 33 Wh per long prompt, more than 70 times the consumption of GPT-4.1 nano, and that Claude-3.7 Sonnet ranks highest in eco-efficiency. While a single short GPT-4o query consumes 0.43 Wh, scaling this to 700 million queries/day results in substantial annual environmental impacts. These include electricity use comparable to 35,000 U.S. homes, freshwater evaporation matching the annual drinking needs of 1.2 million people, and carbon emissions requiring a Chicago-sized forest to offset. These findings illustrate a growing paradox: although individual queries are efficient, their global scale drives disproportionate resource consumption. Our study provides a standardized, empirically grounded methodology for benchmarking the sustainability of LLM deployments, laying a foundation for future environmental accountability in AI development and sustainability standards.

[Arxiv](https://arxiv.org/abs/2505.09598)
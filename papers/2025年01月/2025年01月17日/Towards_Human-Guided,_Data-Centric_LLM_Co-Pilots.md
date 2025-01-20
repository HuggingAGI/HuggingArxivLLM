# 迈向人类引导、数据驱动的LLM协同驾驶

发布时间：2025年01月17日

`Agent

理由：这篇论文介绍了一个名为CliMB-DC的框架，该框架结合了多代理推理系统和LLM推理，旨在解决医疗保健领域中的数据挑战。论文的核心在于其创新的多代理推理系统，包括动态规划的战略协调器和精确执行的工作代理，这明显属于Agent（代理）领域的应用。虽然LLM在框架中起到了重要作用，但论文的重点在于代理系统的设计和实现，因此更适合归类为Agent。`

> Towards Human-Guided, Data-Centric LLM Co-Pilots

# 摘要

> # 摘要
机器学习（ML）有望彻底改变医疗保健领域，但其应用常因领域专家需求与ML工具开发之间的脱节而受阻。尽管基于LLM的副驾驶系统为非技术专家普及ML带来了新进展，但这些系统仍偏重模型层面，忽视了数据层面的关键挑战。在复杂的现实场景中，原始数据常包含缺失值、标签噪声等复杂问题，需要定制化处理。为此，我们推出了CliMB-DC，一个以人为中心、数据驱动的LLM副驾驶框架，结合先进的数据工具与LLM推理，实现稳健且上下文感知的数据处理。CliMB-DC的核心是一个创新的多代理推理系统，包含动态规划的战略协调器和精确执行的工作代理，并通过人在环方法系统整合领域知识。我们为副驾驶必须应对的关键数据挑战制定了分类法，并将前沿数据工具集成到可扩展的开源架构中，便于社区添加新工具。通过真实医疗数据集，我们验证了CliMB-DC将原始数据转化为ML就绪格式的能力，显著优于现有副驾驶基线。CliMB-DC将赋能医疗、金融、社会科学等领域的专家，推动ML在现实世界中的广泛应用。

> Machine learning (ML) has the potential to revolutionize healthcare, but its adoption is often hindered by the disconnect between the needs of domain experts and translating these needs into robust and valid ML tools. Despite recent advances in LLM-based co-pilots to democratize ML for non-technical domain experts, these systems remain predominantly focused on model-centric aspects while overlooking critical data-centric challenges. This limitation is problematic in complex real-world settings where raw data often contains complex issues, such as missing values, label noise, and domain-specific nuances requiring tailored handling. To address this we introduce CliMB-DC, a human-guided, data-centric framework for LLM co-pilots that combines advanced data-centric tools with LLM-driven reasoning to enable robust, context-aware data processing. At its core, CliMB-DC introduces a novel, multi-agent reasoning system that combines a strategic coordinator for dynamic planning and adaptation with a specialized worker agent for precise execution. Domain expertise is then systematically incorporated to guide the reasoning process using a human-in-the-loop approach. To guide development, we formalize a taxonomy of key data-centric challenges that co-pilots must address. Thereafter, to address the dimensions of the taxonomy, we integrate state-of-the-art data-centric tools into an extensible, open-source architecture, facilitating the addition of new tools from the research community. Empirically, using real-world healthcare datasets we demonstrate CliMB-DC's ability to transform uncurated datasets into ML-ready formats, significantly outperforming existing co-pilot baselines for handling data-centric challenges. CliMB-DC promises to empower domain experts from diverse domains -- healthcare, finance, social sciences and more -- to actively participate in driving real-world impact using ML.

[Arxiv](https://arxiv.org/abs/2501.10321)
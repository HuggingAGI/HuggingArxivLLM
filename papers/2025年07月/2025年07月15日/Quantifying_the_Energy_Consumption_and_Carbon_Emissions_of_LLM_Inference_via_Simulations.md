# 基于模拟研究，测算大型语言模型推理过程中的能耗与碳排放

发布时间：2025年07月15日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在推理阶段的环境影响，特别是碳排放问题，并提出了一种仿真框架来评估能源消耗和碳排放。这属于LLM的实际应用和优化，因此归类为LLM应用。` `能源系统`

> Quantifying the Energy Consumption and Carbon Emissions of LLM Inference via Simulations

# 摘要

> 大型语言模型（LLMs）的环境影响日益显著，其中推理阶段的碳排放已占其全生命周期排放的一半以上。然而，目前用于优化LLM部署的仿真框架普遍缺乏对功耗的考量，因而无法准确估算推理相关的碳排放。我们提出了一种仿真框架，旨在评估不同部署条件下LLM推理的能源和碳排放影响。首先，我们通过引入基于利用率指标估算功耗的GPU功耗模型，扩展了一个高保真度的LLM推理仿真器，从而能够分析批量大小、序列长度及模型并行性等关键配置参数。其次，我们将仿真结果整合到能源系统协同仿真环境中，以量化特定电网条件下的碳排放，并探索碳感知调度的潜力。通过场景分析，我们的框架揭示了推理参数对能源需求和碳足迹的影响，展示了在示例部署中高达69.2%的可再生能源抵消潜力，并为未来的碳感知推理基础设施设计奠定了基础。

> The environmental impact of Large Language Models (LLMs) is rising significantly, with inference now accounting for more than half of their total lifecycle carbon emissions. However, existing simulation frameworks, which are increasingly used to determine efficient LLM deployments, lack any concept of power and, therefore, cannot accurately estimate inference-related emissions. We present a simulation framework to assess the energy and carbon implications of LLM inference under varying deployment setups. First, we extend a high-fidelity LLM inference simulator with a GPU power model that estimates power consumption based on utilization metrics, enabling analysis across configurations like batch size, sequence length, and model parallelism. Second, we integrate simulation outputs into an energy system co-simulation environment to quantify carbon emissions under specific grid conditions and explore the potential of carbon-aware scheduling. Through scenario-based analysis, our framework reveals how inference parameters affect energy demand and carbon footprint, demonstrates a renewable offset potential of up to 69.2% in an illustrative deployment case, and provides a foundation for future carbon-aware inference infrastructure design.

[Arxiv](https://arxiv.org/abs/2507.11417)
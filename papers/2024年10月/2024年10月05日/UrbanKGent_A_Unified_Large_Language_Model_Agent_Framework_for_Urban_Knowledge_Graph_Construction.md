# UrbanKGent：一个统一的大语言模型智能体框架，专为城市知识图谱构建而设计

发布时间：2024年10月05日

`LLM应用` `知识图谱`

> UrbanKGent: A Unified Large Language Model Agent Framework for Urban Knowledge Graph Construction

# 摘要

> 城市知识图谱作为一种新兴的构建模块，正在从多源城市数据中提取关键知识，以支持多样化的城市应用场景。尽管其潜力巨大，但城市知识图谱构建（UrbanKGC）仍严重依赖人工 effort，限制了其发展。本文提出了UrbanKGent，一个统一的大型语言模型代理框架，用于城市知识图谱构建。具体来说，我们通过异质感知和地理空间增强的指令生成，构建了适用于UrbanKGC任务（如关系三元组抽取和知识图谱补全）的知识指令集。此外，我们提出了一种工具增强的迭代轨迹精炼模块，以优化从GPT-4中提取的轨迹。通过对Llama 2和Llama 3系列进行混合指令微调，并结合增强后的轨迹，我们获得了UrbanKGC代理家族，包括UrbanKGent-7/8/13B版本。我们在两个真实世界数据集上进行了全面评估，采用人工和GPT-4自评估相结合的方法。实验结果表明，UrbanKGent家族不仅在UrbanKGC任务中显著优于31个基线模型，而且在成本仅为GPT-4约1/20的情况下，性能超过当前最先进的LLM（GPT-4）10%以上。与现有基准相比，UrbanKGent家族可以帮助构建具有数百倍更丰富关系的城市知识图谱，且仅需1/5的数据量。我们的数据和代码可在https://github.com/usail-hkust/UrbanKGent获取。

> Urban knowledge graph has recently worked as an emerging building block to distill critical knowledge from multi-sourced urban data for diverse urban application scenarios. Despite its promising benefits, urban knowledge graph construction (UrbanKGC) still heavily relies on manual effort, hindering its potential advancement. This paper presents UrbanKGent, a unified large language model agent framework, for urban knowledge graph construction. Specifically, we first construct the knowledgeable instruction set for UrbanKGC tasks (such as relational triplet extraction and knowledge graph completion) via heterogeneity-aware and geospatial-infused instruction generation. Moreover, we propose a tool-augmented iterative trajectory refinement module to enhance and refine the trajectories distilled from GPT-4. Through hybrid instruction fine-tuning with augmented trajectories on Llama 2 and Llama 3 family, we obtain UrbanKGC agent family, consisting of UrbanKGent-7/8/13B version. We perform a comprehensive evaluation on two real-world datasets using both human and GPT-4 self-evaluation. The experimental results demonstrate that UrbanKGent family can not only significantly outperform 31 baselines in UrbanKGC tasks, but also surpass the state-of-the-art LLM, GPT-4, by more than 10% with approximately 20 times lower cost. Compared with the existing benchmark, the UrbanKGent family could help construct an UrbanKG with hundreds of times richer relationships using only one-fifth of the data. Our data and code are available at https://github.com/usail-hkust/UrbanKGent.

[Arxiv](https://arxiv.org/abs/2402.06861)
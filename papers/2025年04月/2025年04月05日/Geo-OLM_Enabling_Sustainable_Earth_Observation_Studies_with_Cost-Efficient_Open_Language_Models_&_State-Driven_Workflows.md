# Geo-OLM：开源语言模型与状态驱动工作流助力可持续地球观测研究

发布时间：2025年04月05日

`Agent` `地理空间` `环境科学`

> Geo-OLM: Enabling Sustainable Earth Observation Studies with Cost-Efficient Open Language Models & State-Driven Workflows

# 摘要

> 地理空间协管员（Geospatial Copilots）在地球观测（EO）和气候监测自动化方面潜力巨大，但其对大规模模型（如GPT-4o）的依赖却带来了一个矛盾：旨在支持可持续性研究的工具往往导致难以承受的成本。在地理空间应用中使用智能体AI框架可能产生数千美元的API费用，或需要昂贵且高能耗的GPU支持，这为研究人员、政策制定者和非政府组织设置了障碍。然而，当地理空间协管员与开源语言模型（OLMs）结合使用时，性能通常会下降，因为它们依赖于针对GPT优化的逻辑。本文中，我们推出了Geo-OLM，一款工具增强型地理空间智能体，它基于创新的“基于状态的LLM推理”范式，实现了任务进展与工具调用的解耦。通过减轻工作流推理的负担，我们的方法使资源有限的OLMs能够更高效地完成地理空间任务。当缩减至70亿参数以下的小型模型时，Geo-OLM的成功查询完成率比最强的先前地理空间基线高出32.8%。我们的方法与专有模型的表现相当，结果与GPT-4o相差不到10%，同时将推理成本降低了两个数量级，从$500-$1000降至不到$10。我们通过地理空间下游基准进行了深入分析，为从业者有效部署OLMs用于EO应用提供了关键见解。

> Geospatial Copilots hold immense potential for automating Earth observation (EO) and climate monitoring workflows, yet their reliance on large-scale models such as GPT-4o introduces a paradox: tools intended for sustainability studies often incur unsustainable costs. Using agentic AI frameworks in geospatial applications can amass thousands of dollars in API charges or requires expensive, power-intensive GPUs for deployment, creating barriers for researchers, policymakers, and NGOs. Unfortunately, when geospatial Copilots are deployed with open language models (OLMs), performance often degrades due to their dependence on GPT-optimized logic. In this paper, we present Geo-OLM, a tool-augmented geospatial agent that leverages the novel paradigm of state-driven LLM reasoning to decouple task progression from tool calling. By alleviating the workflow reasoning burden, our approach enables low-resource OLMs to complete geospatial tasks more effectively. When downsizing to small models below 7B parameters, Geo-OLM outperforms the strongest prior geospatial baselines by 32.8% in successful query completion rates. Our method performs comparably to proprietary models achieving results within 10% of GPT-4o, while reducing inference costs by two orders of magnitude from \$500-\$1000 to under \$10. We present an in-depth analysis with geospatial downstream benchmarks, providing key insights to help practitioners effectively deploy OLMs for EO applications.

[Arxiv](https://arxiv.org/abs/2504.04319)
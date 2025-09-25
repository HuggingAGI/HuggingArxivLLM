# AI推理能耗：效率路径与测试时计算

发布时间：2025年09月24日

`LLM应用` `能源与环保`

> Energy Use of AI Inference: Efficiency Pathways and Test-Time Compute

# 摘要

> 随着AI推理规模扩展至数十亿次查询，新兴的推理与智能体工作流推高了token需求，每查询能耗的可靠估算对容量规划、排放核算及效率优先级排序愈发关键。然而现有公开估算常不一致且夸大能耗——因其仅基于有限基准外推，未能体现规模效应带来的效率提升潜力。本文提出一种自底向上的方法，基于token吞吐量估算大规模LLM系统的每查询能耗。在真实工作负载、GPU利用率及PUE限制下，运行于H100节点的前沿规模模型（>2000亿参数）每查询能耗中位数为0.34瓦时（四分位距：0.18-0.67），这与生产级配置测量结果一致，同时揭示非生产环境的估算可能夸大能耗4-20倍。当扩展到典型查询token数增加15倍的测试时扩展场景时，能耗中位数上升13倍至4.32瓦时，表明在此场景下优化效率将实现全集群最大节省。我们在模型、服务平台及硬件层面量化了可实现的效率提升：单独优化可使每查询能耗中位数降低1.5-3.5倍，综合改进则有望实现8-20倍降幅。从系统级影响来看，处理10亿次查询的部署基准日能耗为0.8吉瓦时/天；若10%为长查询，需求或增至1.8吉瓦时/天；而通过针对性效率干预，能耗可降至0.9吉瓦时/天，与该规模下网络搜索的能源足迹相当。这呼应了数据中心在互联网与云建设时期通过效率提升缓和能源增长的历史经验。

> As AI inference scales to billions of queries and emerging reasoning and agentic workflows increase token demand, reliable estimates of per-query energy use are increasingly important for capacity planning, emissions accounting, and efficiency prioritization. Many public estimates are inconsistent and overstate energy use, because they extrapolate from limited benchmarks and fail to reflect efficiency gains achievable at scale. In this perspective, we introduce a bottom-up methodology to estimate the per-query energy of large-scale LLM systems based on token throughput. For models running on an H100 node under realistic workloads, GPU utilization and PUE constraints, we estimate a median energy per query of 0.34 Wh (IQR: 0.18-0.67) for frontier-scale models (>200 billion parameters). These results are consistent with measurements using production-scale configurations and show that non-production estimates and assumptions can overstate energy use by 4-20x. Extending to test-time scaling scenarios with 15x more tokens per typical query, the median energy rises 13x to 4.32 Wh, indicating that targeting efficiency in this regime will deliver the largest fleet-wide savings. We quantify achievable efficiency gains at the model, serving platform, and hardware levels, finding individual median reductions of 1.5-3.5x in energy per query, while combined advances can plausibly deliver 8-20x reductions. To illustrate the system-level impact, we estimate the baseline daily energy use of a deployment serving 1 billion queries to be 0.8 GWh/day. If 10% are long queries, demand could grow to 1.8 GWh/day. With targeted efficiency interventions, it falls to 0.9 GWh/day, similar to the energy footprint of web search at that scale. This echoes how data centers historically tempered energy growth through efficiency gains during the internet and cloud build-up.

[Arxiv](https://arxiv.org/abs/2509.20241)
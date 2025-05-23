# 递归卸载在多级网络环境中用于大语言模型服务

发布时间：2025年05月22日

`其他` `云计算` `多级网络`

> Recursive Offloading for LLM Serving in Multi-tier Networks

# 摘要

> 异构设备-边缘-云计算架构在电信运营商和广域网（WAN）中广泛应用，为新兴智能服务提供了多级计算支持。随着大型语言模型（LLM）服务的普及，如何在多级网络架构中高效协调推理任务并减少通信开销成为关键挑战。现有LLM服务范式存在局限：设备端受硬件限制仅支持轻量级LLM，而以云为中心的部署则面临资源拥塞和高峰时段的通信开销问题。尽管基于模型级联的推理策略更适应多级网络，但其对人工调整阈值的依赖使其难以应对动态网络条件和任务复杂度的变化。

为解决这些挑战，我们提出RecServe，一个专为多级网络中LLM服务设计的递归卸载框架。RecServe采用基于任务特定分层置信度评估机制，通过推断任务复杂度，引导设备、边缘和云端不同层级的LLM逐步扩展规模进行卸载决策。为了实现跨层级的智能任务路由，RecServe采用了基于滑动窗口的动态卸载策略，结合分位数插值，实时追踪历史置信度分布并进行自适应的卸载阈值调整。

实验结果表明，RecServe在服务质量和通信效率方面均优于CasServe，并将通信负载相较于集中式云端服务降低了50%以上。

> Heterogeneous device-edge-cloud computing infrastructures have become widely adopted in telecommunication operators and Wide Area Networks (WANs), offering multi-tier computational support for emerging intelligent services. With the rapid proliferation of Large Language Model (LLM) services, efficiently coordinating inference tasks and reducing communication overhead within these multi-tier network architectures becomes a critical deployment challenge. Existing LLM serving paradigms exhibit significant limitations: on-device deployment supports only lightweight LLMs due to hardware constraints, while cloud-centric deployment suffers from resource congestion and considerable prompt communication overhead caused by frequent service requests during peak periods. Although the model-cascading-based inference strategy adapts better to multi-tier networks, its reliance on fine-grained, manually adjusted thresholds makes it less responsive to dynamic network conditions and varying task complexities. To address these challenges, we propose RecServe, a recursive offloading framework tailored for LLM serving in multi-tier networks. RecServe integrates a task-specific hierarchical confidence evaluation mechanism that guides offloading decisions based on inferred task complexity in progressively scaled LLMs across device, edge, and cloud tiers. To further enable intelligent task routing across tiers, RecServe employs a sliding-window-based dynamic offloading strategy with quantile interpolation, enabling real-time tracking of historical confidence distributions and adaptive offloading threshold adjustments. Experiments on eight datasets demonstrate that RecServe outperforms CasServe in both service quality and communication efficiency, and reduces the communication burden by over 50\% compared to centralized cloud-based serving.

[Arxiv](https://arxiv.org/abs/2505.16502)
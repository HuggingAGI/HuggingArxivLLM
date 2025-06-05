# NetPress：为网络应用动态生成的LLM基准测试

发布时间：2025年06月03日

`LLM应用` `网络运维`

> NetPress: Dynamically Generated LLM Benchmarks for Network Applications

# 摘要

> 尽管人们对大型语言模型（LLMs）及智能体在特定领域的基准测试兴趣日增，现有的评估手段仍受限于静态、小规模数据集，尤其在需要高可靠性的任务（如网络运维）中。我们推出NetPress——一个专为评估LLM代理在网络应用中表现而设计的自动化基准生成框架。通过引入基于状态与动作的统一抽象模型，NetPress实现了多样化查询集及其对应 ground truth 的动态生成。运行时，用户可自定义基准配置，实时生成海量查询。除了动态构建基准，NetPress还与网络仿真器无缝集成，提供真实环境反馈，从而全面评估正确性、安全性和延迟表现。我们基于三个代表性应用场景实现了NetPress，揭示了静态、仅关注正确性的基准测试常常忽略的智能体行为细微差别。NetPress推动了LLM在以基础设施为中心领域的评估迈向现实化、可扩展化测试，助力缩小基准性能与实际部署准备度之间的差距。代码已开源，访问地址：https://github.com/Froot-NetSys/NetPress。

> Despite growing interest in domain-specific benchmarking of large language models (LLMs) and agents, current evaluations remain limited to static, small-scale datasets, especially in high-stakes tasks like network operations that demand reliability for deployments. We present NetPress, an automated benchmark generation framework for evaluating LLM agents in network applications. NetPress introduces a unified abstraction with state and action, enabling dynamic generation of diverse query sets along with corresponding ground truths. At runtime, users can specify benchmark configurations to generate millions of queries on the fly. In addition to dynamic benchmark construction, NetPress integrates with network emulators to provide realistic environment feedback, supporting comprehensive evaluation across correctness, safety, and latency. We instantiate NetPress on three representative applications, revealing interesting fine-grained differences in agent behavior that static, correctness-only benchmarks often miss. NetPress moves LLM evaluation toward realistic, scalable testing in infrastructure-centric domains, helping close the gap between benchmark performance and real-world deployment readiness. Code is available at https://github.com/Froot-NetSys/NetPress.

[Arxiv](https://arxiv.org/abs/2506.03231)
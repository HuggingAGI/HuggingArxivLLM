# GUIDE：一款用于在异构环境中部署大型语言模型的全球统一推理引擎

发布时间：2024年12月06日

`LLM应用` `人工智能` `模型部署`

> GUIDE: A Global Unified Inference Engine for Deploying Large Language Models in Heterogeneous Environments

# 摘要

> 在现实场景中高效部署大型语言模型（LLMs）一直是个关键难题，主要归因于硬件的多样性、推理框架的局限以及工作负载的复杂性。这些难题往往造成内存利用效率低、延迟和吞吐量不佳，阻碍了 LLMs 的有效部署，对非专业人士来说尤其如此。通过大量实验，我们找出了关键的性能瓶颈，像内存利用率骤降、不同批量大小下的延迟波动以及多 GPU 配置效率低下等。这些发现揭示了由硬件、框架和工作负载参数复杂交互形成的巨大优化空间。这凸显了需要一套系统的方法来优化 LLM 推理，从而促成了我们框架 GUIDE 的设计。GUIDE 借助动态建模和基于模拟的优化来解决这些问题，在批量延迟、TTFT 和解码吞吐量等关键指标上实现了 25%至 55%的预测误差。通过有效弥合理论性能与实际部署之间的差距，我们的框架赋予从业者，特别是非专业人员以能力，让他们能够做出数据驱动的决策，在异构环境中以低成本充分释放 LLMs 的潜力。

> Efficiently deploying large language models (LLMs) in real-world scenarios remains a critical challenge, primarily due to hardware heterogeneity, inference framework limitations, and workload complexities.Efficiently deploying large language models (LLMs) in real-world scenarios remains a critical challenge, primarily due to hardware heterogeneity, inference framework limitations, and workload complexities. These challenges often lead to inefficiencies in memory utilization, latency, and throughput, hindering the effective deployment of LLMs, especially for non-experts. Through extensive experiments, we identify key performance bottlenecks, including sudden drops in memory utilization, latency fluctuations with varying batch sizes, and inefficiencies in multi-GPU configurations. These insights reveal a vast optimization space shaped by the intricate interplay of hardware, frameworks, and workload parameters. This underscores the need for a systematic approach to optimize LLM inference, motivating the design of our framework, GUIDE. GUIDE leverages dynamic modeling and simulation-based optimization to address these issues, achieving prediction errors between 25% and 55% for key metrics such as batch latency, TTFT, and decode throughput. By effectively bridging the gap between theoretical performance and practical deployment, our framework empowers practitioners, particularly non-specialists, to make data-driven decisions and unlock the full potential of LLMs in heterogeneous environments cheaply.

[Arxiv](https://arxiv.org/abs/2412.04788)
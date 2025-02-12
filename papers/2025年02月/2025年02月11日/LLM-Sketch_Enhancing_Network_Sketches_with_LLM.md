# LLM-Sketch：借助 LLM 提升网络设计

发布时间：2025年02月11日

`LLM应用` `网络运维` `网络流量分析`

> LLM-Sketch: Enhancing Network Sketches with LLM

# 摘要

> 网络流挖掘是网络运维中的基础性工作。数据摘要作为一种内存占用低且精度可控的紧凑型数据结构，在网络流挖掘领域展现出巨大潜力。近期研究尝试运用机器学习优化数据摘要，但这些方法在适应动态网络环境和控制训练成本方面仍存在瓶颈。本文提出LLM-Sketch，其核心理念是：除了数据包头中的流ID外，其他字段也能为推断流大小提供有效信息。通过采用两级数据结构并对大流和小流分别记录，LLM-Sketch在提升准确性的同时大幅降低了内存占用。此外，它巧妙地运用微调后的大型语言模型（LLMs）来可靠地估计流大小。我们在三个典型任务上对LLM-Sketch进行了评估，结果表明LLM-Sketch比现有最优方法实现了【数学公式】的准确率提升，展现出显著优势。


> Network stream mining is fundamental to many network operations. Sketches, as compact data structures that offer low memory overhead with bounded accuracy, have emerged as a promising solution for network stream mining. Recent studies attempt to optimize sketches using machine learning; however, these approaches face the challenges of lacking adaptivity to dynamic networks and incurring high training costs. In this paper, we propose LLM-Sketch, based on the insight that fields beyond the flow IDs in packet headers can also help infer flow sizes. By using a two-tier data structure and separately recording large and small flows, LLM-Sketch improves accuracy while minimizing memory usage. Furthermore, it leverages fine-tuned large language models (LLMs) to reliably estimate flow sizes. We evaluate LLM-Sketch on three representative tasks, and the results demonstrate that LLM-Sketch outperforms state-of-the-art methods by achieving a $7.5\times$ accuracy improvement.

[Arxiv](https://arxiv.org/abs/2502.07495)
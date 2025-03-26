# 大型推理模型的权衡分析：探究基础能力之上的审慎推理与自适应推理

发布时间：2025年03月23日

`LLM应用` `推理模型` `计算资源管理`

> Trade-offs in Large Reasoning Models: An Empirical Analysis of Deliberative and Adaptive Reasoning over Foundational Capabilities

# 摘要

> 近期，OpenAI 的 o1/o3 和 DeepSeek-R1 等大型推理模型（LRMs）通过模拟人类的深思熟虑和长链推理，在专业推理任务中表现突出。然而，我们对 DeepSeek、Qwen 和 LLaMA 等多个模型家族，以及 70 亿到 6710 亿参数规模的系统性评估发现，获取这种深思熟虑的推理能力会显著削弱模型的基础性能，不仅导致有用性和无害性明显下降，推理成本也大幅攀升。值得强调的是，我们提出了一种自适应推理方法，通过采用零思考、少思考和总结思考等多种模式，能够有效缓解这些弊端。我们的研究发现凸显了开发更 versatile 的大型推理模型的迫切需求，这些模型能够根据具体任务特性动态分配推理计算资源。

> Recent advancements in Large Reasoning Models (LRMs), such as OpenAI's o1/o3 and DeepSeek-R1, have demonstrated remarkable performance in specialized reasoning tasks through human-like deliberative thinking and long chain-of-thought reasoning. However, our systematic evaluation across various model families (DeepSeek, Qwen, and LLaMA) and scales (7B to 671B) reveals that acquiring these deliberative reasoning capabilities significantly reduces the foundational capabilities of LRMs, including notable declines in helpfulness and harmlessness, alongside substantially increased inference costs. Importantly, we demonstrate that adaptive reasoning -- employing modes like Zero-Thinking, Less-Thinking, and Summary-Thinking -- can effectively alleviate these drawbacks. Our empirical insights underline the critical need for developing more versatile LRMs capable of dynamically allocating inference-time compute according to specific task characteristics.

[Arxiv](https://arxiv.org/abs/2503.17979)
# # 冷却很重要：基准测试大型语言模型与视觉-语言模型在液体冷却与风冷H100 GPU系统上的性能

发布时间：2025年07月22日

`其他` `数据中心`

> Cooling Matters: Benchmarking Large Language Models and Vision-Language Models on Liquid-Cooled Versus Air-Cooled H100 GPU Systems

# 摘要

> 人工智能（AI）工作负载的空前增长，主要由大型语言模型（LLMs）和视觉语言模型（VLMs）推动，使得数据中心的供电和散热需求急剧增加。本研究在两个HGX节点上对LLMs和VLMs进行了基准测试，每个节点配备8个NVIDIA H100 GPU，分别采用液冷和风冷。通过GPU Burn、Weights and Biases以及IPMItool工具，我们收集了详细的热、功耗和计算数据。结果显示，液冷系统在负载下将GPU温度维持在41-50摄氏度，而风冷系统则在54-72摄氏度之间波动。液冷系统的这种热稳定性带来了17%的更高性能（每GPU 54 TFLOPs vs. 每GPU 46 TFLOPs），提升了每瓦性能，减少了能源消耗，提高了系统效率。这些发现突显了液冷的能源和可持续性优势，为超大规模数据中心提供了极具吸引力的前进方向。

> The unprecedented growth in artificial intelligence (AI) workloads, recently dominated by large language models (LLMs) and vision-language models (VLMs), has intensified power and cooling demands in data centers. This study benchmarks LLMs and VLMs on two HGX nodes, each with 8x NVIDIA H100 graphics processing units (GPUs), using liquid and air cooling. Leveraging GPU Burn, Weights and Biases, and IPMItool, we collect detailed thermal, power, and computation data. Results show that the liquid-cooled systems maintain GPU temperatures between 41-50 degrees Celsius, while the air-cooled counterparts fluctuate between 54-72 degrees Celsius under load. This thermal stability of liquid-cooled systems yields 17 percent higher performance (54 TFLOPs per GPU vs. 46 TFLOPs per GPU), improved performance per watt, reduced energy overhead, and greater system efficiency than the air-cooled counterparts. These findings underscore the energy and sustainability benefits of liquid cooling, offering a compelling path forward for hyperscale data centers s

[Arxiv](https://arxiv.org/abs/2507.16781)
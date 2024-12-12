# 关于 GPU 加速节点上 AI 训练电力需求的实证度量

发布时间：2024年12月11日

`其他` `云计算` `人工智能`

> Empirical Measurements of AI Training Power Demand on a GPU-Accelerated Node

# 摘要

> 人工智能（AI）应用的不断拓展促使对计算基础设施的投入大幅增加，尤其是云计算供应商。要量化这一基础设施的能源足迹，就需要依据训练期间 AI 硬件的功率需求来构建参数化模型。我们通过实践测量了在训练开源图像分类器（ResNet）和大型语言模型（Llama2-13b）时 8 个 GPU 的 NVIDIA H100 HGX 节点的瞬时功率。所观测到的最大功率约为 8.4 千瓦，比制造商给出的 10.2 千瓦额定值低 18%，即便 GPU 近乎满负荷运行。在保持模型架构不变的情况下，将 ResNet 的批量大小从 512 张图像提升至 4096 张，总训练能耗降低了 4 倍。这些发现可为数据中心运营商的容量规划以及研究人员对能源使用的估算提供参考。未来的工作将探究冷却技术和碳感知调度对 AI 工作负载能源消耗的影响。

> The expansion of artificial intelligence (AI) applications has driven substantial investment in computational infrastructure, especially by cloud computing providers. Quantifying the energy footprint of this infrastructure requires models parameterized by the power demand of AI hardware during training. We empirically measured the instantaneous power draw of an 8-GPU NVIDIA H100 HGX node during the training of open-source image classifier (ResNet) and large-language models (Llama2-13b). The maximum observed power draw was approximately 8.4 kW, 18% lower than the manufacturer-rated 10.2 kW, even with GPUs near full utilization. Holding model architecture constant, increasing batch size from 512 to 4096 images for ResNet reduced total training energy consumption by a factor of 4. These findings can inform capacity planning for data center operators and energy use estimates by researchers. Future work will investigate the impact of cooling technology and carbon-aware scheduling on AI workload energy consumption.

[Arxiv](https://arxiv.org/abs/2412.08602)